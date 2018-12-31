git 手順
local環境で開発したものをlocal repositoryのindexに追加する。
local repositoryにcommitする。
githubにpushする。

githubでnew repository
local環境にrepository作成（mkdir）
そのdirにgit init

単体のファイルはgit add test.txt
複数のファイルはgit add .

最後にgit commit -m "変更点"

そのdirに対してgit remote add origin repository-url
git push origin master

