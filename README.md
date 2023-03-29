# Test Docker + Flask(Python) + HTML + CSS

Esse código foi desenvolvido como um estudo de aplicações onde o Docker pode ser utilizado. 


## 🔧 Ferramentas Utilizadas

- Docker: plataforma de contêineres que permite que os desenvolvedores empacotem seus aplicativos em contêineres portáteis que podem ser executados em qualquer ambiente. Isso torna a implantação e a execução de aplicativos muito mais fáceis e eficientes, pois as dependências e o ambiente de execução são encapsulados no contêiner.
- Flask: framework de aplicativos web para a linguagem de programação Python.
- HTML:  linguagem de marcação utilizada na construção de páginas na Web.
- CSS: mecanismo para adicionar estilos a uma página web, aplicado diretamente nas tags HTML ou ficar contido dentro das tags "<style>".

## ⚙️ Como Funciona

- O usuário deve upar a aplicação em um servidor ao upar a aplicação o usuário deverá acessar a aplicação no seguinte link: http://localhost:5000.
- Aplicação mostra somente dois textos em uma página web.

## 💻 Como executar o código

- Instalar Python
- Abra o prompt de comando
- caminhe até a pasta raiz do programa e contém os arquivo "app.py", "requirements.txt", "docker-compose.yml" e "Dockerfile".
- Você precisa inicialmente criar uma imagem Docker a partir do Dockerfile. Utilize o seguinte comando "**docker build -t myproject .**".
- Para executar o arquivo (**docker run -p 5000:5000 myproject**) e entre no link **http://localhost:5000**.
