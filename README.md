# GoogleTagManager

## イントロダクション
GoogleAnalyticsタグは従来、計測したい数値やクリック等のイベント毎にアナリティクスタグを設置していました。そして従来では、プロジェクトマネージャやデザイナーが特定の数字を計測したい際や小さなPDCAを回したい際にはエンジニアに依頼をしhtmlにアナリティクスタグを実装するというコストが発生していました。加えて、htmlの至るところにタグが存在し、管理が難しくなるということもしばしばありました。そのような問題を解決するため、タグを一元管理できるGoogleTagManagerを導入しました。GoogleTagManagerの導入により、誰でも、管理画面からタグを追加・編集することができ、タグのメンテナンス性やチーム間での実装コストが軽減されることが期待できます。
【参考URL】
[Googleタグマネージャとは？ そのメリットと特徴を知る](http://web-tan.forum.impressrd.jp/e/2014/12/24/18964)

<h2><a id="user-content-タグについて" class="anchor" href="#タグについて" aria-hidden="true"><span class="octicon octicon-link"></span></a><a href="https://github.com/sho0110/GoogleTagManager/blob/master/tag.md">タグについて</a></h2>
・タグマネージャー経由で新規にタグを追加する際の手順・注意等