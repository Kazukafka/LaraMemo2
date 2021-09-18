# LaraMemo
dev
npm run development

development
cross-env NODE_ENV=development node_modules/webpack/bin/webpack.js --progress --hide-modules --config=node_modules/laravel-mix/setup/webpack.config.js

[webpack-cli] Error: Unknown option '--hide-modules'
[webpack-cli] Run 'webpack --help' to see available commands and options

スクリーンショット 2021-09-17 19.04.22.png

ーーー追記ーーー
https://qiita.com/yutarou/items/e00a05b4d84ed40dc444
↑のリンクを参考に
[webpack-cli] Error: Unknown option '--hide-modules'
のエラーは解決しました

今は、２つ目のエラーの解決に取り組んでいます

現在のエラー

dev
npm run development

development
cross-env NODE_ENV=development node_modules/webpack/bin/webpack.js --progress --config=node_modules/laravel-mix/setup/webpack.config.js

sh: 1: cross-env: not found

現在の画面
スクリーンショット 2021-09-17 19.28.58.png

ーーー追記ーーー
https://akamist.com/blog/archives/2827
↑のリンクを参考に２つ目のエラー解決ができました
ご助力ありがとうございました
# LaraMemo2
