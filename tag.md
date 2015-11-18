# タグについて
## イントロダクション
タグは下記のように【追いたい数字・イベント(クリック等)】に対し1つタグを設置します。下記の例では、"GoogleAnalyticsにページビューをレポートするためのユニバーサルアナリティクス"と"クリックイベントの数値を計測するためのRelated_posts"というタグをGoogleTagManager上から設置しています。新しいタグは"新規"から追加できます。
![GoogleTagManager](https://github.com/sho0110/GoogleTagManager/blob/master/images/googletagmanager.png)

## 新規追加
"プロダクトを選択"から使用するプロダクトを選択します。
![GoogleTagManager](https://github.com/sho0110/GoogleTagManager/blob/master/images/タグタグ.png)
### タグの種類を選択
ユニバーサルアナリティクス
### タグを選択
![GoogleTagManager](https://github.com/sho0110/GoogleTagManager/blob/master/images/moreread.png)
【トラッキングID】<br>
  GoogleAnalytics -> アナリティクス設定 -> プロパティ設定 の項目から確認できます。<br>
【ディスプレイ広告向け機能を有効にする】<br>
  使用場面等が謎なのでなしで運用しています。<br>
【トラッキングタイプ】<br>
  計測するシチュエーションや数値によって適するトラッキングタイプを選択します。<br>
トラッキングタイプについて、今回は\<a class="link">もっと見る</a>というリンクがクリックされた数を計測するための例を示します。
トラッキングタイプから"イベント"を選択すると、イベントトラッキングパラメータという項目があります。これはGoogleAnalyticsに【何を何としてレポートするのか】ということを設定するための項目で必須項目は**カテゴリとアクション**です。カテゴリとアクションはAnalyticsの下記画像の部分に相当します。
![GoogleTagManager](https://github.com/sho0110/GoogleTagManager/blob/master/images/analytics.png)
今回、アクションの項目には「/topic/210」など様々な値がレポートされていますが詳細に追う必要がない場合には「クリック」や「リンク」など適当なアクション名を任意に設定することもできます。
また、非インタラクションヒットは、**リンクを踏んで外部サイトへ遷移した際に直帰とみなすか否か**という設定で基本的に**真**に設定しておきます。
#### トラッキングタイプ一覧
・ページビュー: サイトの各ページで配信できる基本的な Google アナリティクス タグです。<br>
・イベント: ボタンのクリックなどの特定の操作やイベントをトラッキングできます。<br>
・トランザクション: e コマース トランザクションをトラッキングできます。<br>
・ソーシャル: ソーシャル インタラクションをトラッキングできます。<br>
・タイミング: ページの読み込み速度をトラッキングできます。<br>
・装飾リンク: <br>
・装飾フォーム: <br>
【配信するタイミング】<br>
Analyticsにレポートを送信するタイミングです。今回はリンクがクリックされた瞬間にレポートを送信したいので、トリガーの種類をクリックにし、related_postsというトリガーを設定しています。トリガーについては別途<a id="user-content-トリガー" class="anchor" href="#トリガー" aria-hidden="true"><span class="octicon octicon-link"></span></a><a href="https://github.com/sho0110/GoogleTagManager/master/trigger.md">トリガー</a>を参照してください。