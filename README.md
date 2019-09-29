# scala-vscode-example

<p align="center">
<img src="https://habrastorage.org/webt/ud/yh/jp/udyhjpz93gmj1miboy94qfnquug.png"/>
</p>

Простой пример Scala проекта, настроенный на работу с Metals + VSCode. Процесс установки и настройки Metals подробно описан в [этой статье на Хабре](https://habr.com/ru/sandbox/133255/).

Создание проекта осуществляется командой:

```shel
$ sbt 
```

Для работы также нужно установить [bloop](https://scalacenter.github.io/bloop/docs/what-is-bloop). 

После завершения компиляции, приложение можно запустить командой:

```shel
$ bloop run scala-vscode-example 
```