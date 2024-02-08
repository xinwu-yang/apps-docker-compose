# Camunda 初めて

### ドキュメントに関して

- [Quick Start](https://docs.camunda.org/get-started/quick-start/)

- [Camunda Docs](https://docs.camunda.org/manual/7.20/)

- [REST API Docs](https://docs.camunda.org/rest/camunda-bpm-platform/7.20/)

- [Desktop Modeler](https://docs.camunda.io/docs/components/modeler/desktop-modeler/install-the-modeler/)

### フォルダの中身説明

|  ファイル  |  説明  |
| ---- | ---- |
|  docker-compose.yml  |  camunda docker設定  |
|  default.yml  |  camunda アプリ設定  |
|  init.sql  |  DB新規SQL  |
|  payment.bpmn payment.dmn payment.form |  支払い流れのbpmn  |

### DockerでCamundaサービスを構築

1. 「docker-compose.yml」がdocker-composeで起動される

```shell
docker-compose up -d
```

> DB アカウント：「postgres」、パスワード：「chengxun」

> Camundaサービスに関するDBとテーブルを自動で生成する

2. URL「http://localhost:8080/」を聞く

> Camunda アカウント：「admin」、パスワード：「camunda」