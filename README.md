# Pet-Collab
# Guarda Compartilhada de Pets

Este é um projeto de um site para gestão de guarda compartilhada de pets. O site permite que os usuários gerenciem a guarda de seus pets, visualizem informações dos pets e atualizem seus perfis. O site é responsivo e foi projetado para funcionar bem em dispositivos móveis e desktops.

## Funcionalidades

- **Página de Login**: Tela inicial onde os usuários podem fazer login na plataforma.
- **Página de Criação de Usuário**: Permite que novos usuários criem uma conta.
- **Página Principal**: Exibe um resumo das atividades de guarda compartilhada e a lista de pets do usuário.
- **Página de Meus Pets**: Exibe detalhes dos pets do usuário.
- **Página de Controle de Guarda Compartilhada**: Permite que os usuários visualizem, editem e excluam atividades de guarda compartilhada.
- **Página de Perfil**: Permite que os usuários visualizem e editem suas informações de perfil.

## Tecnologias Utilizadas

- **HTML**: Estrutura das páginas web.
- **CSS**: Estilização das páginas web.
- **Font Awesome**: Ícones utilizados nas páginas.

## Estrutura do Projeto

```plaintext

├── index.html                 # Página de Login
├── registro.html              # Página de Criação de Usuário
├── home.html                  # Página Principal
├── meuspets.html              # Página de Meus Pets
├── guarda_compartilhada.html  # Página de Controle de Guarda Compartilhada
├── perfil.html                # Página de Perfil
├── /css                       # Arquivo de estilos CSS
└── README.md                  # Documentação do projeto
```
## Como Utilizar

1. Clone o repositório para o seu ambiente local:
    ```bash
    git clone https://github.com/seu-usuario/guarda-compartilhada-pets.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd guarda-compartilhada-pets
    ```

3. Abra o arquivo `index.html` em um navegador web para acessar a página de login.

## Ajustes de Responsividade

O site foi projetado para ser responsivo, com ajustes específicos para diferentes tamanhos de tela:

- **iPhone SE (320px)**: Ajustes para fontes e margens para melhor visualização.
- **iPhone X (375px)**: Ajustes adicionais para fontes e espaçamentos para melhor usabilidade.
- **Desktops**: Layouts com maior espaçamento e tamanhos de fonte para melhor visualização.

### Exemplo de Ajustes de Responsividade no CSS

```css
/* Ajustes para telas menores que 375px */
@media only screen and (max-width: 375px) {
    header h1 {
        font-size: 20px;
    }
    nav ul li {
        margin: 0 5px;
    }
    nav ul li a {
        font-size: 14px;
    }
}

