# 資料の整理ガイド — タグと分類の付け方の例

RefPicker に資料を入れたあと、**何をタグにして、何を分類軸にするか**を決めるための例をまとめました。
操作の手順は [ユーザーガイド](USER_GUIDE.md) にあります。ここでは、アニメ制作の資料ごとに「どう付けると探しやすいか」だけを扱います。

- **読む人**: プロジェクトを整える人（配る側（共有元）・共同編集者）と、自分の資料を自分で整理する人
- **費用**: 自由タグ・自由タグのグループ・カスタム分類軸を作ることは、ライセンス認証なしでできます。分類タグの付け外しの扱いは [ユーザーガイド 4.2](USER_GUIDE.md#42-切り抜きタグ) の表のとおりです
- ここに並べた分類軸と分類は**例**です。作品や部署の呼び方に合わせて、名前を直して使ってください
- 表の中のチップの見方: <span class="rp-t">ハル</span> は**自由タグ**、<span class="rp-v"><span class="rp-ax">季節</span>夏</span> は**分類**（小さい字はその分類軸）、<span class="rp-a">季節</span> は**分類軸**です

## 1. 3つの置き場 — フォルダ・自由タグ・分類タグ

資料を探す手がかりは、3つの置き場のどれかに置きます。

| 置き場 | 向いているもの | 例 | 探し方 |
|---|---|---|---|
| **フォルダ名** | フォルダで既に分かれているもの | 作品名・話数・カット番号 | フィルタ語。ファイルの**相対パス**にも一致するので、`#03` や `C045` と打てば絞れます |
| **自由タグ** | 名前。作品が進むほど増えるもの | キャラ名・場所名・小物の名前<br><span class="rp-t">ハル</span> <span class="rp-t">通学路</span> <span class="rp-t">鞄</span> | フィルタ語・自由タグのピッカー・「分類」ペインの **関連** タブ |
| **分類タグ** | 作品が変わっても同じ並びで使える性質 | <span class="rp-a">顔</span> <span class="rp-a">表情</span> <span class="rp-a">季節</span> <span class="rp-a">時間帯</span> <span class="rp-a">資料の種類</span> | 「分類」ペインのボタン。付け忘れは **「未分類」** で見つかります |

**迷ったときの目安:**

| こういうもの | 置き場 | なぜ |
|---|---|---|
| 並びが決まっていて、全部の資料に付けたい | **分類タグ** | 分類のボタンが並ぶので書き方がばらつかず、付けていない資料が「未分類」に残ります |
| これから増える名前 | **自由タグ** | 打った語が次から入力候補に出ます。数が増えたら、設定の **「タグの管理」** タブで自由タグのグループ（「キャラ」「場所」など）に分けます（[ユーザーガイド 4.9](USER_GUIDE.md#49-自由タグを整理するタグの管理自由タグのグループ)） |
| フォルダ名に既にある | **付けない** | フィルタ語で絞れます |

分類軸は小さく始めて構いません。分類の名前はあとから直せます。要らなくなった分類は **「別の分類にまとめる…」** で別の分類へ移せます（[ユーザーガイド 4.8](USER_GUIDE.md#48-分類軸を作るプロジェクトのカスタム分類軸)）。

## 2. ファイルに付けるか、切り抜きに付けるか

| 付ける先 | 向いているもの | 例 |
|---|---|---|
| **ファイル** | 1枚全体に言えること | 資料の種類・季節・時間帯・場所名 |
| **切り抜き** | 1枚の中で、部分ごとに違うこと | 顔の向き・表情・キャラ名 |

- 画像のファイルに付けたタグは、その画像の切り抜きに引き継がれます。1枚に何人も描かれた修正でも、「資料の種類」は画像に1回付ければ足ります（[ユーザーガイド 4.5](USER_GUIDE.md#45-ファイルにタグを付けるファイルタグ)）
- 切り抜き自身がその分類軸の分類を持っていれば、その分類軸では切り抜きの分類が使われます
- 動画・3D は切り抜きを作れないので、ファイルに付けます

## 3. 例で使う分類軸

アプリが持つ分類軸（顔・表情・ショット・部位）に、次のカスタム分類軸を足す例です。

| 分類軸 | 付け方 | 分類の例 | 付ける先 |
|---|---|---|---|
| <span class="rp-a">資料の種類</span> | 1つだけ | <span class="rp-v">作監修正</span> <span class="rp-v">原画</span> <span class="rp-v">キャラ設定</span> <span class="rp-v">表情集</span> <span class="rp-v">小物設定</span> <span class="rp-v">美術設定</span> <span class="rp-v">美術ボード</span> <span class="rp-v">色指定</span> <span class="rp-v">注意事項</span> <span class="rp-v">参考動画</span> <span class="rp-v">3D</span> | ファイル |
| <span class="rp-a">衣装</span> | 1つだけ | <span class="rp-v">制服</span> <span class="rp-v">私服</span> <span class="rp-v">体操服</span> | 切り抜き（衣装が1枚で同じならファイル） |
| <span class="rp-a">工程</span> | 複数可 | <span class="rp-v">レイアウト</span> <span class="rp-v">原画</span> <span class="rp-v">作監</span> <span class="rp-v">動画</span> <span class="rp-v">仕上げ</span> <span class="rp-v">背景</span> <span class="rp-v">撮影</span> | ファイル |
| <span class="rp-a">季節</span> | 1つだけ | <span class="rp-v">春</span> <span class="rp-v">夏</span> <span class="rp-v">秋</span> <span class="rp-v">冬</span> | ファイル |
| <span class="rp-a">時間帯</span> | 1つだけ | <span class="rp-v">早朝</span> <span class="rp-v">朝</span> <span class="rp-v">昼</span> <span class="rp-v">夕方</span> <span class="rp-v">夕暮れ</span> <span class="rp-v">夜</span> <span class="rp-v">深夜</span> | ファイル |
| <span class="rp-a">天気</span> | 1つだけ | <span class="rp-v">晴れ</span> <span class="rp-v">曇り</span> <span class="rp-v">雨</span> <span class="rp-v">雪</span> <span class="rp-v">霧</span> | ファイル |
| <span class="rp-a">屋内外</span> | 1つだけ | <span class="rp-v">屋内</span> <span class="rp-v">屋外</span> <span class="rp-v">車内</span> | ファイル |

- **資料の種類**は、ほかの節の全部にまたがる分類軸です。フォルダが工程ごとに分かれていない資料も、種類で引けるようになります
- 部位の分類軸にも **衣装**・**小物** があります。部位は「切り抜きに何が写っているか」、カスタム分類軸の衣装は「どの衣装か」です
- 背景の分類軸（季節・時間帯・天気・屋内外ほか）は、分類軸の定義ファイル（`.refaxes`）にまとめて **「読み込み…」** で入れられます

## 4. 資料ごとの例

### 4.1 何に何を付けるか

| 資料 | 付ける先 | 分類タグ | 自由タグ |
|---|---|---|---|
| **作監修正・原画** | 切り抜き（キャラごと）。資料の種類だけファイル | <span class="rp-a">顔</span> <span class="rp-a">表情</span> <span class="rp-a">ショット</span> <span class="rp-a">衣装</span> <span class="rp-v"><span class="rp-ax">資料の種類</span>作監修正</span> <span class="rp-v"><span class="rp-ax">資料の種類</span>原画</span> | キャラ名 <span class="rp-t">ハル</span> |
| **設定資料**（キャラ・小物・美術） | ファイル。1枚に複数のキャラや小物があれば、切り抜きに自由タグを足す | <span class="rp-v"><span class="rp-ax">資料の種類</span>キャラ設定</span> <span class="rp-v"><span class="rp-ax">資料の種類</span>表情集</span> <span class="rp-v"><span class="rp-ax">資料の種類</span>小物設定</span> <span class="rp-v"><span class="rp-ax">資料の種類</span>美術設定</span> <span class="rp-v"><span class="rp-ax">資料の種類</span>色指定</span> | キャラ名・小物の名前・場所名 |
| **背景・ロケハン写真** | ファイル | <span class="rp-a">季節</span> <span class="rp-a">時間帯</span> <span class="rp-a">天気</span> <span class="rp-a">屋内外</span> <span class="rp-v"><span class="rp-ax">資料の種類</span>美術ボード</span> など | 場所名 <span class="rp-t">通学路</span> <span class="rp-t">主人公の家</span> <span class="rp-t">駅前</span> |
| **注意事項・指南書** | ファイル | <span class="rp-v"><span class="rp-ax">資料の種類</span>注意事項</span> <span class="rp-a">工程</span>（その注意が効く工程。複数可） | 中身を表す語 <span class="rp-t">影</span> <span class="rp-t">髪のハイライト</span>・キャラ名 |
| **芝居の参考動画・3D** | ファイル | <span class="rp-v"><span class="rp-ax">資料の種類</span>参考動画</span> <span class="rp-v"><span class="rp-ax">資料の種類</span>3D</span> | 動きの名前 <span class="rp-t">走り</span> <span class="rp-t">振り向き</span> <span class="rp-t">髪のなびき</span> |

作監修正・原画の <span class="rp-a">顔</span> は顔の向き、<span class="rp-a">表情</span> は感情・目・口です。

### 4.2 こう絞り込む

| 資料 | 押す・打つ | 並ぶもの |
|---|---|---|
| **作監修正・原画** | <span class="rp-t">ハル</span> ＋ <span class="rp-v"><span class="rp-ax">顔</span>左前45・あおり45</span> ＋ <span class="rp-v"><span class="rp-ax">衣装</span>制服</span> | 同じ向き・同じ衣装の修正だけ |
| **設定資料** | <span class="rp-v"><span class="rp-ax">資料の種類</span>小物設定</span> ＋ <span class="rp-t">ハル</span> | そのキャラの持ち物の設定だけ |
| **背景・ロケハン写真** | <span class="rp-v"><span class="rp-ax">季節</span>夏</span> ＋ <span class="rp-v"><span class="rp-ax">時間帯</span>夕方</span> ＋ <span class="rp-t">通学路</span> | 夏の夕方の通学路だけ |
| **注意事項・指南書** | <span class="rp-v"><span class="rp-ax">資料の種類</span>注意事項</span> ＋ <span class="rp-v"><span class="rp-ax">工程</span>原画</span> | 原画に効く注意事項だけ |
| **芝居の参考動画・3D** | <span class="rp-v"><span class="rp-ax">資料の種類</span>参考動画</span> ＋ <span class="rp-t">振り向き</span> | 振り向きの参考動画だけ（一覧の中で再生できます） |

### 4.3 資料ごとの補足

- **作監修正・原画**: 話数・カット番号は、フォルダ名にあれば付けません
- **背景・ロケハン写真**: 背景の担当の人は、**常に表示する分類軸**のセットを季節・時間帯・天気・屋内外だけにしておくと、タブが背景の分類軸だけになります（[ユーザーガイド 4.7](USER_GUIDE.md#47-タブに出す分類軸を選ぶ常に表示する分類軸)）
- **注意事項・指南書**: 並べられるのは、画像・動画・3D のファイルです（[ユーザーガイド「扱えるファイル」](USER_GUIDE.md#対象範囲)）。PDF は並びません
- **芝居の参考動画・3D**: 動きの種類は数が決まらないので、分類ではなく自由タグにします

## 5. 組み合わせて絞り込む

「分類」ペインの絞り込みモードでは、押し方で組み合わせが変わります（[ユーザーガイド 4.2](USER_GUIDE.md#42-切り抜きタグ)）。

| したいこと | 押し方 | 例 |
|---|---|---|
| 両方に当てはまるものだけ | クリック（AND） | <span class="rp-v"><span class="rp-ax">季節</span>夏</span> ＋ <span class="rp-v"><span class="rp-ax">時間帯</span>夕方</span> |
| どちらかに当てはまるもの | `Ctrl`＋クリック（OR） | <span class="rp-v"><span class="rp-ax">季節</span>夏</span> か <span class="rp-v"><span class="rp-ax">季節</span>秋</span> |
| 除く | `Alt`＋クリック（NOT） | <span class="rp-v"><span class="rp-ax">資料の種類</span>作監修正</span> を除く |
| 付け忘れを探す | **「未分類」** | 資料の種類が付いていないファイル |

フィルタ語（キャラ名・場所名・話数）と分類のボタンは、同時に効きます。

## 6. 分類軸を配る・そろえる

| したいこと | やり方 | 詳しくは |
|---|---|---|
| チームに同じ分類軸を届ける | 共有します。分類軸の定義も受け取る人に届きます。受け取る人は直せず、共同編集者は直せます | [共有ガイド](SYNC_GUIDE.md) |
| 別のプロジェクトで同じ分類軸を使う | **「書き出し…」** で分類軸の定義ファイル（`.refaxes`）にして、そちらで **「読み込み…」** します | [ユーザーガイド 4.8](USER_GUIDE.md#48-分類軸を作るプロジェクトのカスタム分類軸) |
| 使わない分類軸を隠す | 設定の **「分類」** タブの目のアイコンで非表示にします。付いているタグは消えません | [ユーザーガイド 4.7](USER_GUIDE.md#47-タブに出す分類軸を選ぶ常に表示する分類軸) |
| 自由タグの書き方をそろえる | **「タグの管理」** タブの **「別のタグにまとめる…」** でそろえます | [ユーザーガイド 4.9](USER_GUIDE.md#49-自由タグを整理するタグの管理自由タグのグループ) |
