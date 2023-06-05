# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
*リモートリポジトリはネット上で共有されるリポジトリ
*ローカルリポジトリは各PC上のリポジトリ
*リポジトリはさまざまなデータ、情報、知識や成果物を蓄積するデータベースやアーカイブ。


## プッシュとマージの違いは何でしょうか？
*プッシュは各ブランチのローカル変更点を、リモートのブランチへ反映させる。
*マージは作業用に分けていたブランチをリモートリポジトリのブランチに取り込む作業


## コミットとプッシュの違い
*コミットはローカルリポジトリでコード変更などを、Gitのリポジトリに変更内容を保存する。プッシュは各ブランチのローカル変更点を、リモートのブランチへ反映させる。


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
*一目で変更内容がわかるようなものにする。コミットメッセージは各チームやプロジェクトでルールがある場合が多いので、必ずその決まりに準拠したメッセージにする。


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
*ローカルでマージする際は、ローカルでの変更内容をリモートブランチへプッシュ、その後、リモートのマスターブランチにプッシュされたリモートブランチに取り込む。
*プルリクエストは、ローカルリポジトリの作業用ブランチをリモートリポジトリにプッシュする。リモートリポジトリの作業用ブランチをマスターブランチに取り込む際にプルリクエストを作成し、コードチェックをしてもらい、責任者からマージしてもらう。



## コンフリクトを起こしてしまった場合、どう対処すべきですか？
*1.先にマージされた変更内容を取り込む
*2.後にマージしようとしている変更内容を取り込む
*3.どちらの変更内容も取り込む
