# Loggerの設定を確認

Slf4j + Log4j 2を確認したい

* Log4jのデフォルトはErrorのみ出力
* Log4jの設定ファイルはlog4j2.properties
* 上記設定に`rootLogger.level = debug`とだけ設定すると、Layoutパターンはなにも設定されていない`info("hoge")` => `hoge`が出る状態になる
* (TODO)設定ファイルにYaml形式を使う場合は、Jacksonが必要になる
* (TODO)出力にJson形式を使う場合にも、Jacksonが必要になる

