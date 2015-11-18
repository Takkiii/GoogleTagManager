# バージョン
## イントロダクション
GoogleTagManagerではタグやトリガー、変数の新規作成や編集、削除を行う度に新しいバージョンが定義されます。変更を上書きするのではなくバージョンとして管理することで、新規作成や編集でミスが生じ、他のレポーティングに影響を及ぼした場合でも1つ前のバージョンに戻すだけで問題は解決します。

### バージョンの更新
GoogleTagManagerでは変更をバージョンとして管理します。そのため編集を完了し、保存をしたとしても反映はされません。保存をした時点ではまだ1つ前のバージョンのタグが動作しています。GoogleTagManagerでは管理画面から【公開済みのバージョン】と【現在編集中のバージョン】の2つのバージョンが確認できます。【現在編集中のバージョン】を管理画面の右上にある【公開】から公開することで変更が反映されます。≈
### バージョンのロールバック
逆に変更にミスがあり早急にロールバックを行いたい場合、GoogleTagManagerのヘッダー部分にある【バージョン】の項目を選択します。それまでのバージョンがすべて表示されており、右側に【アクション】という項目があります。安全なバージョンのアクションから【公開】を選択し公開すればロールバックが完了します。