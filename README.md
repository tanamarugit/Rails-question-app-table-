# Rails-question-app-table-

users テーブル
------------
id: integer
name: integer
email: integer
password: integer
created_at: datetime
updated_at: datetime
-------------



questions テーブル
----------------
id: integer
title: integer
body: text
created_at: datetime
updated_at: datetime
---------------
↑に誰が投稿したかわかるように、user_idを紐付ける。



answers テーブル
--------------
id: integer
body: text
question_id: integer
created_at: datetime
updated_at: datetime
---------------
↑に誰が投稿したかわかるように、user_idを紐付ける。
どの質問に対する答えかわかるように、question_idを紐付ける。
