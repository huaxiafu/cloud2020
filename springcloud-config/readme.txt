http://config-3344.com:3344/main/config-test.yml
config:
  info: main branch, springcloud-config/config-test.yml version=1


http://config-3344.com:3344/dev/config-dev.yml
config:
  info: dev branch, springcloud-config/config-dev.yml version=1


http://config-3344.com:3344/config/dev/main
{"name":"config","profiles":["dev"],"label":"main","version":"99f626d5519c3b6dec38a79a8444b291c75a7416","state":null,"propertySources":[{"name":"https://github.com/huaxiafu/cloud2020.git/springcloud-config/config-dev.yml","source":{"config.info":"main branch, springcloud-config/config-dev.yml version=1"}}]}