# 超絶技巧プログラミングコード
CML_quine.rb

## 概要
本プログラムは超絶技巧プログラミングによって作られています。
特徴1.プログラミングコード自体がアスキーアート
特徴2.コードを出力する自己言及的なコード(quine)
特徴3.出力するたびに実行結果が変わる(※)

## 使い方
コードを見る：cat CML_quine.rb
コードを実行：ruby CML_quine.rb

※ 本サイトではteeが実装されていないのですが、
ローカル環境などで実行される際は
ruby CML_quine.rb | tee CML_quine2.rb
といった形で出力結果を別ファイルで保存することで、
実行結果が変わる様子をお楽しみいただけます。

ruby CML_quine.rb | tee CML_quine2.rb
ruby CML_quine2.rb | tee CML_quine3.rb
ruby CML_quine3.rb | tee CML_quine4.rb
…
と繰り返すと、
CML_quine4.rbは再びCML_quine.rbと同じファイルになります。

catで開いたコードをコピー＆ペーストして
ローカルでも是非お楽しみください。
