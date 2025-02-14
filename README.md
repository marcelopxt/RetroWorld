# 🎮 RetroWorld
<p align="center">
  <img src="https://github.com/user-attachments/assets/fae0ffab-66fe-49f6-b044-c94e38325f31" alt="RetroWorld Banner">
</p>
 
**RetroWorld** é um site de jogos retrô que permite aos usuários jogarem diretamente pelo navegador através de iframes. O projeto inclui um sistema de login com diferentes níveis de usuário e segue o padrão MVC.

## 🚀 Recursos

- 🎮 Jogabilidade diretamente pelo navegador via iframes
- 🔐 Sistema de login com níveis de acesso:
  - **Admin**: Criar, editar, visualizar e excluir jogos
  - **Usuário comum**: Acessar e jogar os jogos
- 📦 Armazenamento de dados no MongoDB
- 🌎 Interface responsiva com BootStrap e CSS
- 🏗️ Estruturado no padrão MVC

## 🛠️ Tecnologias Utilizadas

- **Frontend:** JavaScript, HandleBars, BootStrap, CSS
- **Backend:** Node.js, Express
- **Banco de Dados:** MongoDB

## 📸 Capturas de Tela

<table style="width: 100%; text-align: center; border-collapse: collapse;">
  <tr>
    <td style="padding: 10px;">
      <img src="https://github.com/user-attachments/assets/732657a6-a284-4dd0-964a-21de0d4570a1" alt="Tela Inicial" style="max-width: 100%; height: auto;">
      <p align="center">Tela Inicial</p>
    </td>
    <td style="padding: 10px;">
      <img src="https://github.com/user-attachments/assets/a3f671bf-b498-4b77-b4f6-182419cca8a7" alt="Tela Admin" style="max-width: 100%; height: auto;">
      <p align="center">Logado como Admin</p>
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">
      <img src="https://github.com/user-attachments/assets/3049def7-eac3-459f-8ead-f4b7cff4dfcc" alt="Tela Cadastro" style="max-width: 100%; height: auto;">
       <p align="center">Cadastro de Novo Usuário</p>
    </td>
    <td style="padding: 10px;">
      <img src="https://github.com/user-attachments/assets/60f1a370-50dc-49d3-afc8-3dd2174a4f87" alt="Tela Jogo" style="max-width: 100%; height: auto;">
       <p align="center"> Jogando 🎮</p>
    </td>
  </tr>
</table>



## 📥 Instalação e Uso

1. Clone este repositório:
   ```bash
   git clone https://github.com/marcelopxt/RetroWorld.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd retroworld
   ```
3. Instale as dependências:
   ```bash
   npm install
   ```
4. Configure as variáveis de ambiente no arquivo `.env` (Exemplo: conexão com o MongoDB)
5. Inicie o servidor:
   ```bash
   npm start
   ```
6. Acesse o site em `http://localhost:3000`

7. É necessário atribuir o Id (ObjectId) do Admin ao controllerIndex.js[linha 5] para que possa usar as funções de Admin.
