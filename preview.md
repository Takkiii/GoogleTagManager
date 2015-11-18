# バージョン
## イントロダクション
GoogleTagManagerではバージョン管理に加えて、プレビュー機能が付属しており誰でもタグを作成し、デバッグを行い、安全な状態で公開することができます。

### プレビューモードの開始
<a id="user-content-バージョン" class="anchor" href="#バージョン" aria-hidden="true"><span class="octicon octicon-link"></span></a><a href="https://github.com/sho0110/GoogleTagManager/blob/master/version.md">バージョン</a>の項で説明した【公開】ボタンの横に矢印のようなボタンがあり、【公開】【プレビューとデバッグ】【バージョンを作成】という項目があります。その中の【プレビューとデバッグ】を押すとプレビューモードに移り、管理画面上にオレンジ色のプレビューのブロックが表示されます。プレビューを確認するためには、GoogleTagManagerを使用しているサイトにアクセスします。プレビューが開始されている場合にはサイト下にGoogleTagManagerのコンソール画面が表示されます。また、この時のプレビュー画面は自身のPCからしか閲覧することができず、他人にもプレビュー画面を共有したい場合は【プレビューの共有】という項目からURLを共有しましょう。
### GoogleTagManagerコンソール
コンソール上では一番上に【Summary】の項目があり、GoogleTagManagerで設定したタグの動作履歴を確認することができます。例えばサイトを閲覧した時にページビューをレポートするようタグを設定していた場合、【Tags Fired On This Page】という項目の下にそのタグが表示されます。他にもクリックイベントで作動するタグが実装されていた場合、ページがロードされたタイミングでは作動しないはずなので[Tags Not Fired On This Page]という項目の下に表示されます。aタグを押した際に作動するタグの場合、リンクをクリックするとページが遷移してしまいコンソール上で確認できなくなってしまうのでcommand + Clickで別タブでリンクさせましょう。タグが作動する度にsummaryの下には履歴が追加されていきます。複数のレポーティングタグを設定している場合は、動作すべきタグとすべきでないタグはよく確認しましょう。
![GoogleTagManager](https://github.com/sho0110/GoogleTagManager/blob/master/images/console.png)
