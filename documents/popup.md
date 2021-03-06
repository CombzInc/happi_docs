# ポップアップ	
## [種類](https://happi.net/function/popup/%e3%83%9d%e3%83%83%e3%83%97%e3%82%a2%e3%83%83%e3%83%97%e3%81%ae%e7%a8%ae%e9%a1%9e%e3%81%a8%e3%83%a1%e3%83%aa%e3%83%83%e3%83%88/)
1. チャット
2. フィードバック
3. フォームA
4. 問い合わせ
5. クーポン
6. 電話
7. 商品質問
8. スタッフ紹介
9. プッシュ通知インセンティブ
10. ページ移動

## 出現方法
1. 右下出現（頭出しと５秒後のアップ）
2. 右下固定
3. 左下出現（頭出しと５秒後のアップ）
4. 左下固定
5. 右中央固定
6. 中央特大モーダル（レスポンシブ）
7. 中央特大モーダル（大きさ固定）
8. 全面
9. 中央出現（スマートフォン向け・横幅指定）
10. 中央出現（スマートフォン向け）
11. 中央モーダルプッシュ通知購読インセンティブ用


## 設置

**ステップ１：[ポップの新規作成](https://happi.net/function/popup/%e3%83%9d%e3%83%83%e3%83%97%e3%82%92%e6%96%b0%e8%a6%8f%e4%bd%9c%e6%88%90%e3%81%99%e3%82%8b/?preview=true)**
1. 右中央にある［+ポップの新規作成］をクリックします。
2. エフェクトテンプレートを［使用する］を選択します。
3. 出現方法を選択します。
4. HTMLテンプレートを［使用する］を選択します。
5. 希望のポップのテンプレートを選択します。
6. ポップのテンプレートが出現するのでクリックします。
7. テンプレートに設定する属性値を入力します。
8. ［url］に個人情報取り扱いページのURLを入力します。
9. その他、必要箇所の入力をします。
10. 作成ボタンをクリックします。

同様の手順でポップは複数作成可能です。


**ステップ２：[ポップの編集](https://happi.net/function/popup/%e3%83%9d%e3%83%83%e3%83%97%e3%82%92pc%e3%81%a8%e3%82%b9%e3%83%9e%e3%83%9b%e3%81%a7%e5%8c%ba%e5%88%a5%e3%81%97%e3%81%a6%e8%a1%a8%e7%a4%ba%e3%81%95%e3%81%9b%e3%81%9f%e3%81%84/)**
1. 作成したポップのタイトルをクリックします。
2. ［画面幅による表示］から表示させたいサイズを選択できます。  
   ・選択した場合、更新ボタンをクリックします。  
3. ［HTML］の右上の［+HTMLを追加］からPC表示とスマートフォン表示を区別して設定できます。  
   ・作成したポップと同じテンプレートを選択します。  
   ・スマホ向けのテンプレートをクリックします。（初めにPC用を作成した場合）  
   ・［このテンプレートでhtmlを作成する］をクリックします。  
   ・グリッドの設定をします。  
   　PC用はsm～xl、スマートフォン用はxsを選択し、更新ボタンをクリックします。
4. ［エフェクト］の右上の［+エフェクトを追加］からPC表示とスマートフォン表示を区別して設定できます。  
   ・エフェクトのテンプレートを［使用する］を選択します。  
   ・［エフェクトの効果］から［中央出現（スマートフォン向け）］を選択します。（初めにPC用を作成した場合）  
   ・［ポップエフェクトを作成する］をクリックします。  
   ・グリッドの設定をHTMLと同様に設定し、更新ボタンをクリックします。  
   
複数のポップアップを1つのWEBサイトに設置したい場合は、複数のサービスを使い、それぞれにポップアップの設定を行います。	


**ステップ３：[シナリオを設定](https://happi.net/function/scenario/%e3%83%9d%e3%83%83%e3%83%97%e3%82%92%e5%a4%89%e6%9b%b4%e3%81%97%e3%81%9f%e3%81%84/)**  
```
例1：ポップから送信があったら、ポップの種類を変更したい場合。    
```
1. シナリオ画面を表示します。  
2. 右中央にある［+シナリオ追加］をクリックします。  
3. トリガーの［ポップアップから送信：設定したいポップ］を選択します。  
4. アクションの［ポップアップ変更：設定したいポップ］を選択します。  
5. タイトル、メモを入力します。（後で編集可能）  
6. ［登録する］をクリックします。  

```
例2：ポップから送信があったら、送信者に対してメールを送りたい場合    
```
1. シナリオ画面を表示します。  
2. 右中央にある［+シナリオ追加］をクリックします。  
3. トリガーの［ポップアップから送信：設定したいポップ］を選択します。  
4. アクションの［メール送信：設定したいメール］を選択します。  
5. タイトル、メモを入力します。（後で編集可能）  
6. ［登録する］をクリックします。  

## 初めて訪れたビジターのポップアップ
表示させたいポップを選択し、更新ボタンをクリックします。

［リセット］をクリックし、更新ボタンをクリックすると選択が解除され、ポップを表示させないようにできます。


## iマーク（インフォメーションマーク）	
iマークを表示するかどうかを設定できます。

リンク先の設定も可能です。（例：個人情報取り扱いのページなど）
