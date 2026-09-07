# 購入ドア（安定 URL）

RefPicker のリリースリポ `animtools/RefPicker` の `landing/buy/` に置く。GitHub Pages での URL:

- サブスク: `https://animtools.github.io/RefPicker/landing/buy/subscribe.html`
- 買い切り: `https://animtools.github.io/RefPicker/landing/buy/perpetual.html`
- スタジオ用: `https://animtools.github.io/RefPicker/landing/buy/studio.html`

アプリ側の `.env`（2026-09-06 に焼き込み済み）:

```env
BUNDLED_LANDING_PUBLIC_ORIGIN=https://animtools.github.io/RefPicker/landing
```

→ アプリは `{ORIGIN}/buy/{subscribe,perpetual,studio}.html` を開く。

## 重要

- **出荷済みビルドがこの URL を参照するため、パスを変えない・削除しない。**
  **リポ名の大文字小文字も変えない**（`RefPicker`）。改名は購入導線を殺す
  （[ハブ ADR 0008](../../../../biz-cycle-hub/docs/adr/0008-purchase-doors-live-on-the-product-pages.md)）。
- **404 にしない。**3枚とも配布済みビルドのボタンから開かれる。売らないドアも「案内」で置く。

## 3枚の状態（2026-09-07 時点）

| ドア | 状態 | 根拠 |
|---|---|---|
| `subscribe.html` | **開いている**（checkout へリダイレクト） | ADR 0004 のサブスク条件「解錠される配布物が1本以上実際に取得でき、実際にその配布物で Pro が解錠されること」を **EconTemple が満たしている**（2026-09-02 に v0.10.0-beta を公開し、ダウンロードと SHA-256 照合、実キーでの解錠まで実測）。**RefPicker 自身の段階（test）は条件ではない** |
| `perpetual.html` | 準備中（飛ばさない） | 買い切りの条件は「配布物が取得でき、**かつ価格が確定**」。価格は実演のフィードバック後に決める（[cycles/crossrefpicker.md](../../../../biz-cycle-hub/cycles/crossrefpicker.md) D3） |
| `studio.html` | お問い合わせ（飛ばさない） | 組織向けの条件は上記に加え「**テスターのFBが一巡**し致命的な問題がないこと」。実演前なので満たさない（同 D2）。ただし**受け取り側は無料**なので、使い方に辿り着ける形で残す |

## 金額を書かない

3枚とも金額を持たない。**価格の正典はハブ料金ページ**で、ここに写すと価格改定で片方だけ古くなる。
`subscribe.html` は checkout へ送るだけで、金額は Polar 側が表示する。

## 開けるときの手順（買い切り・スタジオ用）

1. Polar に商品を作る（2026-09-06 にどちらもアーカイブ済み）
2. checkout URL を各 HTML のコメントに記録する
3. `meta refresh` + `location.replace` + CTA の href を、その URL へ差し替える
4. 台帳 `animtools-license-config/README.md` の購入リンク台帳にも記入する
