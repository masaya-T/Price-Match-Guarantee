# Price-Match-Guarantee
画像から 2 つの製品が同じかどうかを判断するタスク

#コンテストのデータセット
[train/test].csv：トレーニングセットのメタデータ。
・posting_id：データID
・image：画像ID（画像名）
・image_phash：画像の知覚ハッシュ
・title：商品説明
・label_group 同じ商品にマッピングされるすべての投稿の ID コード

[train/test]images：データに関連付けられた画像。

sample_submission.csv：正しい形式のサンプル提出ファイル。 
・posted_id ：データの ID コード。 
・matche：データに一致するすべての投稿 ID のスペース区切りのリスト。データは常に自己一致し、グループ サイズは 50 に制限されている。
#コンテストリンク
https://www.kaggle.com/competitions/shopee-product-matching
