## 自動販売機（データ構造と各種処理）のミニレポート
### Q5-1. 自動販売機の商品データついて説明せよ。
* データ構造（各項目とその説明）
* id:商品番号、商品を識別するためのコード
* name:商品の名前、目に見えて分かる
* price:値段
* stock:在庫数
* 
* 連想配列の配列として定義するメリット
* 商品番号、商品の名前、値段、在庫数などの複数の情報を一つにまとめることができる。
* 
* 
* 
### Q5-2. showItemListの処理内容について説明せよ。
* 配列の繰り返し処理
* for構文で一つずつ取り出している
* 
* 連想配列の参照方法
* item.キー名で商品の情報を取りだしている
* 
### Q5-3. buyItemの処理内容について説明せよ。
* 商品購入の可否判定
* stockを参照し、1以上であれば購入でき、0だとできなくなる
* 
* 商品在庫を減らす処理
* 購入できた時にstock--をすることでstockを一つ減らす
* 
* 商品番号のエラー処理
* 商品番号がおかしい場合はエラーメッセージを出すようにする
* 
### Q5-4. プログラムの考察
* データ構造について
* 連想配列を使うことで複数の情報を一つにまとめることができ、扱いやすいデータ構造である
* 
* 商品一覧表示と購入処理を関数化したメリット
* プログラムが見やすいため管理しやすい
* 
### Q5-5. 感想
* 今回の課題で苦労したこと
* showItemListで、すべての商品番号などが出せるようにする文章が結構長いのと同じ文章が続くので打ち間違えが多かった
* 
* 演習を通して理解できたこと
* memberで合体させた情報の呼びだし方
* 簡単そうな文でも合体させずに一個ずつ文にして書くことの重要さ
* 
* この自動販売機プログラムの追加機能や課題など
* 客が購入したものを記録して得たお金の総量をまとめる機能
