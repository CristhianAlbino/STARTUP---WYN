# WYN (What You Need)

O WYN é uma plataforma de serviços on-demand que conecta usuários a prestadores de serviços. O aplicativo funciona de maneira semelhante ao iFood, mas no lugar de pedidos de comida, oferece uma ampla variedade de serviços, desde diaristas até fotógrafos, para facilitar a vida de quem precisa de serviços rápidos e de qualidade.

Este repositório contém o código-fonte para o backend e frontend do projeto WYN, desenvolvido como parte de um projeto acadêmico para a faculdade, mas com potencial para ser a base de uma startup.

## Tecnologias utilizadas

- **Frontend**: React Native (para desenvolvimento de aplicativos Android e iOS)
- **Backend**: Node.js com Express
- **Banco de Dados**: MongoDB
- **Outras tecnologias**: Figma (para protótipos de design)

## Funcionalidades

- Cadastro e login de usuários e prestadores de serviços.
- Busca e filtro de serviços disponíveis.
- Visualização de detalhes dos prestadores de serviços.
- Sistema de avaliações para prestadores.
- Interface simples e intuitiva para uma melhor experiência do usuário.

## Como rodar o projeto localmente

### Backend

1. Clone este repositório:
   ```bash
Entre na pasta do projeto:

cd wyn
Instale as dependências:

npm install
Configure as variáveis de ambiente (.env) para o banco de dados e porta. Exemplo:

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=wyn_project
PORT=3000
Inicie o servidor:

npm start
O backend estará rodando na porta 3000 (ou a porta que você configurar).

Frontend
Clone o repositório do frontend (caso tenha em um repositório separado).

Instale as dependências do projeto:

npm install
Inicie o servidor de desenvolvimento:

npm run start
O frontend será iniciado e estará acessível em um emulador Android/iOS ou dispositivo real, conforme configurado no React Native.

Contribuições
Contribuições são bem-vindas! Para contribuir:

Faça um fork deste repositório.
Crie uma branch para sua feature (git checkout -b feature/nome-da-feature).
Faça as alterações e commit suas modificações.
Envie um pull request para o branch principal.
Licença
Este projeto está licenciado sob a Licença MIT.
