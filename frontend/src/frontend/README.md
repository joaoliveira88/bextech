# Frontend Python

Como consigo realizar o build da aplicação?

* Garanta que o **python** esteja instalado
* Utilize o comando **virtualenv** e ative um ambiente virtual.
* Instale as dependências descritas em **requirements.txt**
* Use o python para rodar o arquivo **frontend**.py

# Linha de raciocínio para o Backend.
- Criado um Dockerfile com o Python. Nesta inclui a execução do frontend.py e a instalação dos requerimentos.
- Imagem criada a partir do comando: docker build -t bex-frontend {Dockerfile path}
- Executando o container pelo comando: docker run -d -p 8080:8080 bex-frontend --name bex-frontend-app