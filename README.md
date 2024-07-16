# eproc-UI (Nome a Ser Definido)

## Descrição

O eproc-UI é uma extensão para o navegador google chrome que possibilita a mudança do layout da plataforma eproc disponibilizado através do link [https://eproc.tjmg.jus.br](https://eproc.tjmg.jus.br)

## Informações da Plataforma

- **Ambiente para instalação e execução:** Navegador Google chrome

### Tipos de Usuários

Magistrados, servidores e colaboradores que possuem acesso ao sistema eproc (amplo acesso)

## Principais Funcionalidades (MVP)

- Layout da tela Inicial

## Outras Funcionalidades (Versão 2)

- Feedback de usuários utilizando google forms (QRCode e link no popup da extensão ou na página do eproc) - **A definir**

## Tecnologias Utilizadas no Desenvolvimento do Frontend

1. **Linguagens:**
   - HTML, CSS e JavaScript: Tríade fundamental no desenvolvimento web.

2. **Ambiente de Desenvolvimento:**
   - NodeJS e NPM para instalação de pacotes.

3. **Framework e Bibliotecas:**
   - Vite: Ferramenta para construção de projetos frontend.
   - ReactJS: Biblioteca JavaScript para interfaces.
   - Typescript: Superset do JavaScript para programação robusta.

4. **Estilização:**
   - Styled-components: Para estilização.
   - Material Design: Biblioteca de design para componentes estilizados.

5. **Roteamento:**
   - React-router-dom: Sistema de roteamento para uma navegação eficiente.

6. **Requisições HTTP:**
   - Axios: Biblioteca para realizar requisições HTTP.

7. **Comunicação em Tempo Real:**
   - WebSocket-client: Utilizado para interação em tempo real.

8. **Validação de Formulários:**
   - Yup: Biblioteca para validação de formulários.

9. **Simulação de API:**
   - JSON server: Ferramenta para simular uma API durante o desenvolvimento.

## Guia para Executar o Projeto Localmente

1. **Configurar Ambiente Local:**
   Certifique-se de ter o Node.js e o npm instalados em seu ambiente. Caso não tenha, você pode baixá-los [aqui](https://nodejs.org/).

2. **Clonar o Projeto:**
   Clone este repositório para o diretório desejado em sua máquina.

    ```bash
    git clone https://github.com/uailab-tjmg/execucao-penal-frontend.git
    ```

3. **Instalar Dependências:**
   No prompt de comando, navegue até o diretório do projeto e execute o seguinte comando para baixar as dependências necessárias (pasta `node_modules`).

    ```bash
    npm install
    ```

4. **Executar em Ambiente de Desenvolvimento:**
   Utilize o seguinte comando para iniciar o projeto em modo de desenvolvimento:

    ```bash
    npm run dev
    ```

5. **Acessar no Navegador:**
   Abra o navegador da web e digite o link indicado no terminal. Geralmente, o endereço é [http://localhost:5173](http://localhost:5173).
