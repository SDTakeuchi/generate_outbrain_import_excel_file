<h1>Adebis→outbrainへの入稿作業の効率化ツール</h1>

<h2>【背景・課題】</h2>

adebis内で作成したクリエイティブの情報を元にoutbrainへの入稿作業を行っていたが、下記の例のようにURL変更の煩雑な作業が必要だったため、その効率化として作成した

例）　https://google.com/index.html?some_parameter

　　　※上記URLの"html"と"?some"の間に"?affiliate=000"という別のパラメータを挿入する必要があった

<h2>【機能】</h2>

１）adebisから入稿したクリエイティブの一覧をCSVで出力しダウンロード
２）exel1.pyと同じディレクトリに１）のファイルをexcel形式に変換したうえで設置し、ソースコード内の記述をコメントに従って変更する
３）exel1.pyを実行し、出力されたファイルをCSVに変更する
４）outbrainの入稿画面でimport CSVを実行
