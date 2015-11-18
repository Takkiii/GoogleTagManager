# GoogleTagManager

## イントロダクション
GoogleAnalyticsタグは従来、計測したい数値やクリック等のイベント毎にアナリティクスタグを設置していました。そして従来では、プロジェクトマネージャやデザイナーが特定の数字を計測したい際や小さなPDCAを回したい際にはエンジニアに依頼をしhtmlにアナリティクスタグを実装するというコストが発生していました。加えて、htmlの至るところにタグが存在し、管理が難しくなるということもしばしばありました。そのような問題を解決するため、タグを一元管理できるGoogleTagManagerを導入しました。GoogleTagManagerの導入により、誰でも、管理画面からタグを追加・編集することができ、タグのメンテナンス性やチーム間での実装コストが軽減されることが期待できます。<br>
【参考URL】<br>
[Googleタグマネージャとは？ そのメリットと特徴を知る](http://web-tan.forum.impressrd.jp/e/2014/12/24/18964)

<h2><a id="user-content-タグについて" class="anchor" href="#タグについて" aria-hidden="true"><span class="octicon octicon-link"></span></a><a href="https://github.com/sho0110/GoogleTagManager/blob/master/tag.md">タグについて</a></h2>
・タグマネージャー経由で新規にタグを追加する際の手順・注意等

<h2><a id="user-content-トリガー" class="anchor" href="#トリガー" aria-hidden="true"><span class="octicon octicon-link"></span></a><a href="https://github.com/sho0110/GoogleTagManager/blob/master/trigger.md">トリガー</a></h2>
・タグ設定で使用されるトリガーについて

<h2><a id="user-content-変数" class="anchor" href="#変数" aria-hidden="true"><span class="octicon octicon-link"></span></a><a href="https://github.com/sho0110/GoogleTagManager/blob/master/variable.md">変数</a></h2>
・タグのカテゴリ、アクション設定やトリガーの有効化、配信のタイミング設定で使用することのできる変数について

<h2><a id="user-content-バージョン" class="anchor" href="#バージョン" aria-hidden="true"><span class="octicon octicon-link"></span></a><a href="https://github.com/sho0110/GoogleTagManager/blob/master/version.md">バージョン</a></h2>
・GoogleTagManagerではタグやトリガーの新規作成、編集、削除等をバージョンで管理します。

<h2><a id="user-content-プレビュー" class="anchor" href="#プレビュー" aria-hidden="true"><span class="octicon octicon-link"></span></a><a href="https://github.com/sho0110/GoogleTagManager/blob/master/preview.md">プレビュー</a></h2>
・管理画面からタグを追加し、正常に動作しているか・他のタグに影響を与えていないかなどをチェックするためにバージョンの公開を行う前にプレビュー機能で動作を確認しましょう。