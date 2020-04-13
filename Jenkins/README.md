# Automação com Jenkins

- Com o objetivo de criar um processo de automação no Deploy das alterações feitas pelos desenvolvedores, resolvi incluir uma instância com o Jenkins.
- Nesta instância o Jenkins irá idêntificar através de um webhook, as alterações feitas. Através de um arquivo chamado DEPLOY, o desevolvedor que efetuou as alterações, pode sinalizar ao Jenikins se as alterações feitas no código terão que ser aplicadas.
- O commit fará com que o Jenkins baixe o código em seu repositório.
- A condição do arquivo DEPLOY  indicará se o Jenkins mate os containers que está sendo executado e suba um novo com as alterações. Ou que nada seja feito.
