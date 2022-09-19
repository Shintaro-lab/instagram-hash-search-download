# instagram-hash-search-download
instagramのgraph APIを利用してハッシュタグ検索をし、検索結果の中で壊れていない画像と当該画像に付加されている投稿をエクセルに整理するプログラム。

# 使い方
property.jsonに検索したいワード、instagram-id(graph apiの利用登録の中で取得可能)、アクセストークンを設定し、pythonプログラムを起動する。
フォルダ体系は下記とすること。

app-dat(エクセルファイルの出力先)
   -etc（propertyファイルの格納先）
   -image（画像のダウンロード先）
   -src（pythonプログラムの格納先）
   -tmp（中間ファイルの出力先）

# 環境
pythonが使用可能であること。
またdatetime、json、openpyxl、os、pathlib、PIL、requestsをimportしているため、インストールしておくこと。
instagram graph apiの利用登録が済んでいること（インターネット上に登録方法に関する情報は多数あるため、参照のこと）。

# 作成者情報
Author:Shintaro Nakai
e-mail:shintaro.nakai7140@gmail.com
