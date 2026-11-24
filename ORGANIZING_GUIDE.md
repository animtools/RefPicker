# 資料の整理ガイド — タグと分類の付け方の例

RefPicker に資料を入れたあと、**何をタグにして、何を分類軸にするか**を決めるための例をまとめました。
操作の手順は [ユーザーガイド](USER_GUIDE.md) にあります。ここでは、アニメ制作の資料ごとに「どう付けると探しやすいか」だけを扱います。

- **読む人**: プロジェクトを整える人（配る側（共有元）・共同編集者）と、自分の資料を自分で整理する人
- **費用**: 自由タグ・自由タグのグループ・カスタム分類軸を作ることは、ライセンス認証なしでできます。分類タグの付け外しの扱いは [ユーザーガイド 4.2](USER_GUIDE.md#42-切り抜きタグ) の表のとおりです
- ここに並べた分類軸・分類・フォルダ名は**例**です。作品や部署の呼び方に合わせて、名前を直して使ってください
- 表の中の見方: <span class="rp-t">主人公A</span> は**自由タグ**、<span class="rp-v"><span class="rp-ax">季節</span>夏</span> は**分類**（小さい字はその分類軸）、<span class="rp-a">季節</span> は**分類軸**、`作監` のような枠の語はフォルダ名・ファイル名に一致させる**フィルタ語**です

## 1. 3つの整理方法 — フォルダ名とファイル名・自由タグ・分類タグ

資料を探す手がかりは、次の3つの整理方法のどれかで持たせます。

| <span class="rp-nw">整理方法</span> | 向いているもの | 例 | 絞り込み方法 |
|---|---|---|---|
| <span class="rp-nw">**フォルダ名と**</span><br><span class="rp-nw">**ファイル名**</span> | フォルダやファイルの名前で既に分かれているもの | 作品名・話数・カット番号・資料の種類（作監修正・設定・美術ボードなど） | フィルタ語。ファイルの**相対パス**（フォルダ名とファイル名）にも一致するので、`03話` や `C045` と打てば絞れます。頭に `#` を付けるとタグにだけ一致するので、ここでは付けません |
| <span class="rp-nw">**自由タグ**</span> | 名前。作品が進むほど増えるもの | キャラ名・場所名・衣装や小物の名前<br><span class="rp-t">主人公A</span> <span class="rp-t">通学路</span> <span class="rp-t">鞄</span> | フィルタ語・自由タグのピッカー・「分類」ペインの **関連** タブ |
| <span class="rp-nw">**分類タグ**</span> | フォルダ名やファイル名では分けるのが難しく、分類の数が決まっている性質 | <span class="rp-a">顔</span> <span class="rp-a">表情</span> <span class="rp-a">季節</span> <span class="rp-a">時間帯</span> <span class="rp-a">天気</span> | 「分類」ペインのボタン。付け忘れは **「未分類」** で見つかります |

**どの整理方法を使うか迷ったときの判断の目安:**

| 資料の性質 | <span class="rp-nw">整理方法</span> | 理由 |
|---|---|---|
| 分類の数が決まっていて、全部の資料に付けたい | <span class="rp-nw">**分類タグ**</span> | 分類のボタンが並ぶので書き方がばらつかず、付けていない資料が「未分類」に残ります |
| これから増える名前 | <span class="rp-nw">**自由タグ**</span> | 打った語が次から入力候補に出ます。数が増えたら、設定の **「タグの管理」** タブで自由タグのグループ（「キャラ」「場所」など）に分けます（[ユーザーガイド 4.9](USER_GUIDE.md#49-自由タグを整理するタグの管理自由タグのグループ)） |
| フォルダ名やファイル名に既にある | <span class="rp-nw">**付けない**</span> | フィルタ語で絞れます |
| ファイルの種類で分かる（動画か 3D か） | <span class="rp-nw">**付けない**</span> | 一覧で動画はその場で再生でき、3D には「3D」の印が出ます |

分類軸は小さく始めて構いません。分類の名前はあとから直せます。要らなくなった分類は **「別の分類にまとめる…」** で別の分類へ移せます（[ユーザーガイド 4.8](USER_GUIDE.md#48-分類軸を作るプロジェクトのカスタム分類軸)）。

## 2. タグ（分類タグ）をファイルに付けるか、切り抜きに付けるか

| 対象 | 向いているもの | 例 |
|---|---|---|
| **ファイル** | 1枚全体に言えること | 季節・時間帯・天気・場所名 |
| **切り抜き** | 1枚の中で、部分ごとに違うこと | 顔の向き・表情・キャラ名 |

- 画像のファイルに付けたタグは、その画像の切り抜きに引き継がれます。美術ボードから切り抜きを作っても、季節や時間帯は画像に1回付ければ足ります（[ユーザーガイド 4.5](USER_GUIDE.md#45-ファイルにタグを付けるファイルタグ)）
- 切り抜き自身がその分類軸の分類を持っていれば、その分類軸では切り抜きの分類が使われます
- 動画・3D は切り抜きを作れないので、ファイルに付けます

## 3. 分類軸

### 3.1 アプリ内蔵の分類軸

どのプロジェクトにもはじめから入っている分類軸です。付けられる分類は1つだけで、**部位**だけは複数付けられます。

| 分類軸 | 分類 | 主に使う資料 |
|---|---|---|
| <span class="rp-a">顔</span> | 横の向き8つ <span class="rp-v">正面</span> <span class="rp-v">右前45</span> <span class="rp-v">右真横</span> <span class="rp-v">右後45</span> <span class="rp-v">真後ろ</span> <span class="rp-v">左後45</span> <span class="rp-v">左真横</span> <span class="rp-v">左前45</span><br>× 縦の向き3つ <span class="rp-v">あおり45</span> <span class="rp-v">水平</span> <span class="rp-v">俯瞰45</span><br>の組み合わせ（例 <span class="rp-v"><span class="rp-ax">顔</span>左前45・あおり45</span>）と、<span class="rp-v">真俯瞰</span> <span class="rp-v">真あおり</span> | 作監修正・原画・キャラ設定の切り抜き |
| <span class="rp-a">感情</span><br><span class="rp-note">（表情のタブ）</span> | <span class="rp-v">中立</span> <span class="rp-v">怒り</span> <span class="rp-v">嫌悪</span> <span class="rp-v">恐怖</span> <span class="rp-v">喜び</span> <span class="rp-v">悲しみ</span> <span class="rp-v">驚き</span> <span class="rp-v">照れ</span> <span class="rp-v">困り</span> <span class="rp-v">その他</span> | 作監修正・表情集の切り抜き |
| <span class="rp-a">目</span><br><span class="rp-note">（表情のタブ）</span> | <span class="rp-v">開き</span> <span class="rp-v">見開き</span> <span class="rp-v">半目</span> <span class="rp-v">閉じ</span> <span class="rp-v">片目閉じ</span> | 同上 |
| <span class="rp-a">口</span><br><span class="rp-note">（表情のタブ）</span> | <span class="rp-v">開き</span> <span class="rp-v">大開き</span> <span class="rp-v">閉じ</span> <span class="rp-v">歯口</span> | 同上 |
| <span class="rp-a">ショット</span> | <span class="rp-v">ロングショット</span> <span class="rp-v">フルフィギュア</span> <span class="rp-v">ニーショット</span> <span class="rp-v">ウエストショット</span> <span class="rp-v">バストショット</span> <span class="rp-v">アップショット</span> <span class="rp-v">クローズアップ</span> <span class="rp-v">ディテール</span><br>細かく決めないときは <span class="rp-v">ロング</span> <span class="rp-v">ミディアム</span> <span class="rp-v">アップ</span> | レイアウト・作監修正（どの大きさで描かれた絵か） |
| <span class="rp-a">部位</span><br><span class="rp-note">（複数可）</span> | <span class="rp-v">手</span> <span class="rp-v">足</span> <span class="rp-v">髪</span> <span class="rp-v">顔ディテール</span> <span class="rp-v">耳</span> <span class="rp-v">衣装</span> <span class="rp-v">小物</span> | 手・髪などの修正、衣装・小物の設定の切り抜き |

- どの分類軸にも **「対象外」** があります。顔の写っていない切り抜きなどに付けると、「未分類」に出なくなります
- 新しく作ったプロジェクトでは、はじめから **ショット** が非表示です。使うときは、設定の **「分類」** タブの目のアイコンで表示に戻します（[ユーザーガイド 4.7](USER_GUIDE.md#47-タブに出す分類軸を選ぶ常に表示する分類軸)）
- 使わない分類軸は、同じ目のアイコンで隠せます。背景だけを扱う人なら、顔・表情・部位を隠しておくとタブが減ります

### 3.2 分類軸にする性質

次の3つを全部満たす性質を、分類軸にします。アプリ内蔵の分類軸は、どれも満たしています。

| 条件 | 満たす例 | 満たさない例 |
|---|---|---|
| **フォルダをまたいで現れる** | 顔の向き（どの話数の作監修正にもある） | 資料の種類・工程（フォルダやファイル名で分かれている） |
| **フォルダ名やファイル名、自由タグでは分けるのが難しい** | 表情・季節・時間帯・天気 | 動画か 3D か（ファイル名の拡張子で分かる）・屋内か屋外か（場所名の自由タグで決まる） |
| **分類の数が決まっている** | 季節（春・夏・秋・冬） | キャラ名・衣装の名前・動きの名前（増えていく。自由タグにする） |

フォルダで分けた資料を、フォルダをまたいで分類で絞り込むのが分類軸の役目です。フォルダ名やファイル名で分かることを分類軸にしても、絞り込める範囲は増えません。

### 3.3 カスタム分類軸

アプリ内蔵の分類軸で足りない分け方は、プロジェクトのカスタム分類軸として作ります（[ユーザーガイド 4.8](USER_GUIDE.md#48-分類軸を作るプロジェクトのカスタム分類軸)）。

| 分類軸の例 | <span class="rp-nw">選択方式</span> | 分類の例 | <span class="rp-nw">付ける対象</span> |
|---|---|---|---|
| <span class="rp-a">季節</span> | <span class="rp-nw">1つだけ</span> | <span class="rp-v">春</span> <span class="rp-v">夏</span> <span class="rp-v">秋</span> <span class="rp-v">冬</span> | <span class="rp-nw">ファイル</span> |
| <span class="rp-a">時間帯</span> | <span class="rp-nw">1つだけ</span> | <span class="rp-v">朝</span> <span class="rp-v">昼</span> <span class="rp-v">夕方</span> <span class="rp-v">夜</span> | <span class="rp-nw">ファイル</span> |
| <span class="rp-a">天気</span> | <span class="rp-nw">1つだけ</span> | <span class="rp-v">晴れ</span> <span class="rp-v">曇り</span> <span class="rp-v">雨</span> <span class="rp-v">雪</span> <span class="rp-v">霧</span> | <span class="rp-nw">ファイル</span> |

- 資料の種類・工程・屋内外は、分類軸にしないほうがよい例です。フォルダ名・ファイル名・場所名で分かります（3.2）

## 4. 資料ごとの例

### 4.1 何に何を付けるか

| 資料 | 対象 | 分類タグ | 自由タグ |
|---|---|---|---|
| **作監修正・原画** | 切り抜き（キャラごと） | <span class="rp-a">顔</span> <span class="rp-a">表情</span> <span class="rp-a">ショット</span> | キャラ名 <span class="rp-t">主人公A</span>・衣装の名前 <span class="rp-t">制服</span> |
| **キャラ設定** | 切り抜き（三面図の向きごと・手や髪の描き込みごと） | <span class="rp-a">顔</span> <span class="rp-a">部位</span> | キャラ名・衣装の名前 |
| **表情集** | 切り抜き（表情ごと） | <span class="rp-a">表情</span> | キャラ名 |
| **小物設定** | 切り抜き（小物ごと） | — | 小物の名前 <span class="rp-t">鞄</span> |
| **背景・ロケハン写真** | ファイル | <span class="rp-a">季節</span> <span class="rp-a">時間帯</span> <span class="rp-a">天気</span> | 場所名 <span class="rp-t">通学路</span> <span class="rp-t">主人公の家</span> <span class="rp-t">駅前</span> |
| **注意事項・指南書** | ファイル | — | 中身を表す語 <span class="rp-t">影</span> <span class="rp-t">髪のハイライト</span>・キャラ名 |
| **芝居の参考動画・3D** | ファイル | — | 動きの名前 <span class="rp-t">走り</span> <span class="rp-t">振り向き</span> <span class="rp-t">髪のなびき</span> |

- <span class="rp-a">顔</span> は顔の向き、<span class="rp-a">表情</span> は感情・目・口です
- 分類タグが「—」の資料は、フォルダ名・ファイル名と自由タグで足ります

### 4.2 絞り込みの例

フォルダ名のフィルタ語で範囲を決めてから、分類と自由タグで中身を絞ります。`作監` や `ロケハン` は例です。実際のフォルダの名前に置き換えてください。

| 資料 | 押す・打つ | 並ぶもの |
|---|---|---|
| **作監修正** | `作監` ＋ <span class="rp-t">主人公A</span> ＋ <span class="rp-v"><span class="rp-ax">顔</span>左前45・あおり45</span> | 作監修正のうち、主人公Aの同じ向きの修正だけ |
| **キャラ設定** | `設定` ＋ <span class="rp-t">主人公A</span> ＋ <span class="rp-v"><span class="rp-ax">顔</span>右真横・水平</span> | 設定のうち、主人公Aの真横向きの絵だけ（三面図の横） |
| **表情集** | `表情集` ＋ <span class="rp-v"><span class="rp-ax">感情</span>照れ</span> ＋ <span class="rp-v"><span class="rp-ax">目</span>半目</span> | 照れていて半目の表情だけ |
| **背景・ロケハン写真** | `ロケハン` ＋ <span class="rp-v"><span class="rp-ax">季節</span>夏</span> ＋ <span class="rp-v"><span class="rp-ax">時間帯</span>夕方</span> ＋ <span class="rp-t">通学路</span> | 夏の夕方の通学路の写真だけ |
| **注意事項・指南書** | `注意事項` ＋ <span class="rp-t">影</span> | 影についての注意事項だけ |
| **芝居の参考動画・3D** | `参考動画` ＋ <span class="rp-t">振り向き</span> | 振り向きの参考動画だけ（一覧の中で再生できます） |

### 4.3 資料ごとの補足

- **作監修正・原画**: 話数・カット番号は、フォルダ名かファイル名にあれば付ける必要がありません
- **背景・ロケハン写真**: 背景の担当の人は、**常に表示する分類軸**のセットを季節・時間帯・天気だけにしておくと、タブが背景の分類軸だけになります（[ユーザーガイド 4.7](USER_GUIDE.md#47-タブに出す分類軸を選ぶ常に表示する分類軸)）
- **注意事項・指南書**: 並べられるのは、画像・動画・3D のファイルです（[ユーザーガイド「扱えるファイル」](USER_GUIDE.md#対象範囲)）。PDF は並びません
- **芝居の参考動画・3D**: 動きの種類は数が決まらないので、分類ではなく自由タグにします

## 5. 組み合わせて絞り込む

「分類」ペインの絞り込みモードでは、押し方で組み合わせが変わります（[ユーザーガイド 4.2](USER_GUIDE.md#42-切り抜きタグ)）。

| したいこと | 押し方 | 例 |
|---|---|---|
| 両方に当てはまるものだけ | クリック（AND） | <span class="rp-v"><span class="rp-ax">季節</span>夏</span> ＋ <span class="rp-v"><span class="rp-ax">時間帯</span>夕方</span> |
| どちらかに当てはまるもの | `Ctrl`＋クリック（OR） | <span class="rp-v"><span class="rp-ax">季節</span>夏</span> か <span class="rp-v"><span class="rp-ax">季節</span>秋</span> |
| 除く | `Alt`＋クリック（NOT） | <span class="rp-v"><span class="rp-ax">天気</span>雨</span> を除く |
| 付け忘れを探す | **「未分類」** | 季節が付いていない背景の写真 |

フィルタ語（フォルダ名・キャラ名・場所名・話数）と分類のボタンは、同時に効きます。

## 6. 分類軸を配る・そろえる

| したいこと | やり方 | 詳しくは |
|---|---|---|
| チームに同じ分類軸を届ける | 共有します。分類軸の定義も受け取る人に届きます。受け取る人は直せず、共同編集者は直せます | <span class="rp-nw">[共有ガイド](SYNC_GUIDE.md)</span> |
| 別のプロジェクトで同じ分類軸を使う | **「書き出し…」** で分類軸の定義ファイル（`.refaxes`）にして、そちらで **「読み込み…」** します | <span class="rp-nw">[ユーザーガイド 4.8](USER_GUIDE.md#48-分類軸を作るプロジェクトのカスタム分類軸)</span> |
| 使わない分類軸を隠す | 設定の **「分類」** タブの目のアイコンで非表示にします。付いているタグは消えません | <span class="rp-nw">[ユーザーガイド 4.7](USER_GUIDE.md#47-タブに出す分類軸を選ぶ常に表示する分類軸)</span> |
| 自由タグの書き方をそろえる | **「タグの管理」** タブの **「別のタグにまとめる…」** でそろえます | <span class="rp-nw">[ユーザーガイド 4.9](USER_GUIDE.md#49-自由タグを整理するタグの管理自由タグのグループ)</span> |
