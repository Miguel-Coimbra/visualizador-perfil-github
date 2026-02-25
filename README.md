# Visualizador de Perfil GitHub

<p align="center">
  <img src="./src/image/preview.png" alt="Preview do projeto" width="650">
</p>

Este é um projeto simples de uma aplicação web que permite aos usuários pesquisar perfis do GitHub e exibir suas informações públicas.

## Descrição

O "Visualizador de Perfil GitHub" é uma ferramenta intuitiva que facilita a busca e visualização de dados de perfis do GitHub. Basta digitar um nome de usuário para ver detalhes como foto de perfil, nome, biografia, número de seguidores, quem o usuário segue, repositórios públicos e uma lista de seus repositórios mais recentes.

## Funcionalidades

*   **Pesquisa de Perfis:** Encontre qualquer perfil do GitHub pelo nome de usuário.
*   **Exibição de Informações:** Mostra foto de perfil, nome de usuário, nome completo e biografia.
*   **Estatísticas:** Visualize rapidamente o número de seguidores, quem o usuário segue e a quantidade de repositórios públicos.
*   **Repositórios Recentes:** Lista os repositórios públicos mais recentes, com links diretos para cada um no GitHub.
*   **Design Responsivo:** Interface adaptável a diferentes tamanhos de tela.

## Tecnologias Utilizadas

*   **HTML5:** Estrutura base da aplicação.
*   **CSS3:** Estilização e responsividade da interface.
    *   `animations.css`: Efeitos de animação.
    *   `reset.css`: Reset de estilos padrão do navegador.
    *   `responsive.css`: Estilos para diferentes dispositivos.
    *   `styles.css`: Estilos principais da aplicação.
*   **JavaScript:** Lógica de programação e interação com a API.
    *   `githubAPI.js`: Funções para consumir a API do GitHub.
    *   `index.js`: Lógica principal da aplicação e manipulação do DOM.
    *   `profileView.js`: Gerencia a exibição das informações do perfil na interface.
*   **GitHub API:** Para buscar os dados dos perfis.

## Como Rodar Localmente

Siga os passos abaixo para configurar e executar o projeto em sua máquina local:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/your-username/visualizador-perfil-github.git
    ```
    (Substitua `your-username` pelo nome de usuário ou organização do repositório, ou o link do seu próprio fork, se aplicável.)

2.  **Navegue até o diretório do projeto:**
    ```bash
    cd visualizador-perfil-github
    ```

3.  **Abra o arquivo `index.html`:**
    Simplesmente abra o arquivo `index.html` em seu navegador web preferido para iniciar a aplicação.

## Estrutura de Arquivos

```
visualizador-perfil-github/
├── index.html
├── README.md
└── src/
    ├── css/
    │   ├── animations.css
    │   ├── reset.css
    │   ├── responsive.css
    │   └── styles.css
    └── js/
        ├── githubAPI.js
        ├── index.js
        └── profileView.js
```
