# PlantUML

GitHub で Markdown を書ける場所（Git管理の *.md コンテンツや、issue, comment, etc.）で下記のようなコードブロックを記述すると…
[GitHub 上で PlantUML をレンダリングするChrome拡張 v1.2.0 をリリースしました](https://dev.classmethod.jp/tool/chrome-extension-plantuml-in-github-markdown-v1-2-0/)


\```uml
@startuml
Alice -> Bob: Authentication Request
Bob --> Alice: Authentication Response

Alice -> Bob: Another authentication Request
Alice <-- Bob: another authentication Response
@enduml
\```


```uml
@startuml
Alice -> Bob: Authentication Request
Bob --> Alice: Authentication Response
 
Alice -> Bob: Another authentication Request
Alice <-- Bob: another authentication Response
@enduml
```
