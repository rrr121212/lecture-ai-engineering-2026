# 第6回 解答

## 演習

<!-- [tool call] の行は、表示された行をそのまま貼り付けてください。終わらなかった STEP は、空欄のままでかまいません。 -->

- STEP 1 のツールの名前：search_materials
- STEP 2 の [tool call]： glossary_search_glossary({'query': '3レベル'})
- STEP 3 の [tool call]： fetch_fetch({'url': 'https://modelcontextprotocol.io/'})
- STEP 4 の [tool call]：aws_aws___search_documentation({'search_phrase': 'What is versioning in Amazon S3', 'topics': ['general']})
- 気づき・疑問：少し文を書き足すだけで、webページを読み込むことができるようになることに気が付いた。取得することができないwebページはあるのか疑問に思った。

## 宿題

<!-- 基礎・実装・発展のどれか1つに取り組めば完了です。 -->

- 取り組んだレベル：基礎 
- やったこと：演習で使った用語集の MCP サーバーに、（`get_lecture_summary`）というツールをもう 1 つ公開した。
- 結果：  指定した回（1始まりの整数）の講義の要点を五行ほどの箇条書きで返すようになった。さらに、講義の目標も返すようになった。
- 気づき・疑問：この様に様々なツールを導入して、エージェントを改良していくのだということに気づいた。今回はサーバー側だけ書き換えたが、なぜエージェント側は変えなくてよかったのか疑問に思った。
