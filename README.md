# 🏨 Projeto Flask MVCS - RESTful CRUD Completo

Este projeto foi desenvolvido em **Python (Flask)** seguindo a arquitetura **MVCS (Model-View-Controller-Service)**.  
Ele implementa uma **API RESTful completa**, incluindo **CRUDs**, **autenticação JWT**, **conexão com MySQL** e **interface HTML**.

---

## 🚀 Funcionalidades

- 🔐 Login e autenticação JWT
- 🧍‍♂️ CRUD de hóspedes
- 🏨 CRUD de hotéis
- 📅 CRUD de reservas
- 🧩 Arquitetura MVCS (Model, View, Controller, Service)
- 🗄️ Conexão com banco de dados MySQL
- 🌐 Frontend integrado com páginas HTML no diretório `/static`


Antes de rodar o projeto, você precisa ter instalado:

- 🐍 [Python 3.11+](https://www.python.org/downloads/)
- 🧩 [Flask](https://flask.palletsprojects.com/)
- 🐬 [MySQL Server e XAMPP](https://www.apachefriends.org/pt_br/index.html)
- 🧰 [Git](https://git-scm.com/)
- 📦 Bibliotecas Python (instaladas via `pip`)

---
🚀 Como Executar o Projeto

Para rodar o projeto corretamente, siga os passos abaixo com atenção 👇

Primeiro, abra o arquivo server.py e remova a senha da conexão com o banco de dados 🔐, deixando-a em branco caso o seu MySQL não utilize senha por padrão.

💡 Exemplo:

conexao = mysql.connector.connect(
    host="127.0.0.1",
    user="root",
    password="",  # deixe vazio se não houver senha
    database="seu_banco"
)


Em seguida, vá até a pasta api/database e copie o conteúdo do arquivo database.sql (ou Banco.sql, localizado em api/docs).
Abra o MySQL Workbench, cole esse código na área de query e execute ✅ — isso criará o banco de dados e as tabelas necessárias para o funcionamento do sistema.

Certifique-se de que o MySQL Workbench está conectado ao servidor local:

🌐 Host: 127.0.0.1

🔢 Porta: 3306

👤 Usuário: root


Agora, abra o XAMPP e ligue os dois serviços principais:

Serviço	Status
⚙️ Apache	🟢 Ligado
🗄️ MySQL	🟢 Ligado

Esses dois precisam estar ativos para que o sistema funcione corretamente ⚡

Com o servidor rodando, volte ao terminal e, dentro da pasta principal do projeto, execute o comando abaixo:


python app.py


Após isso, o terminal mostrará uma mensagem parecida com esta:

 * Running on http://127.0.0.1:5000

Clique no link 🌐 ou copie e cole no navegador — e pronto!
Seu sistema estará funcionando perfeitamente 🚀🔥
