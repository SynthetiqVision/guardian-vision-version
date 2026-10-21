Guardian Vision のアプリが、新しいバージョンが出たかを知るために読む version.json だけを置くリポジトリです。
version.json には、いまのバージョンの番号と、その Release のページへのリンクだけを書きます。アプリ本体・判定モデル・ソースは置きません。
version.json は guardian-vision-x-proto の swift/make_dist.sh が Release を作ったあとに書き換えます（手で書き換えません）。
