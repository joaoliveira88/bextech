# Backend Go

Como consigo realizar o build da aplicação?

* Garanta que o **go** esteja instalado
* Instale as dependências descritas no block **import** do arquivo **main**.go
* Realize o build usando o próprio comando **go**

# Linha de raciocínio para o Backend.
Criado um Dockerfile com o Goland e instalando as dependências 
Imagem criada a partir do comando: docker build -t bex-backend {Dockerfile path}
Executando o container pelo comando: docker run -d -p 8080:8080 bex-backend --name bex-backend-app
