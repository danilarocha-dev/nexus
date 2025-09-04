# Organizador de Times

Este projeto é uma aplicação web simples desenvolvida em React para gerenciar e visualizar colaboradores organizados por equipes. Ele permite adicionar novos membros com suas informações e atribuí-los a equipes pré-definidas, exibindo-os de forma clara e organizada em cards.

[Ver Projeto](http://localhost:3000)

## Funcionalidades

*   **Cadastro de Colaboradores:** Adicione novos membros informando nome, cargo, URL da imagem e selecionando uma equipe.
*   **Organização por Equipes:** Colaboradores são automaticamente agrupados e exibidos sob suas respectivas equipes.
*   **Visualização em Cards:** Cada colaborador é representado por um card visualmente atraente, exibindo sua foto, nome e cargo.
*   **Equipes Pré-definidas:** O sistema já vem com uma lista de equipes como Programação, Front-End, Data Science, DevOps, UX e Design, Mobile e Inovação e Gestão.

## Tecnologias Utilizadas

*   **React.js:** Framework JavaScript para construção de interfaces de usuário. (Versão 19.1.0)
*   **JavaScript:** Linguagem de programação principal.
*   **CSS:** Para estilização e layout dos componentes.
*   **Create React App:** Ferramenta para configurar ambientes de desenvolvimento React.

## Estrutura do Projeto

A estrutura principal do projeto é organizada da seguinte forma:

```
.
├── public/                 # Arquivos estáticos (HTML, imagens, etc.)
├── src/                    # Código fonte da aplicação
│   ├── App.js              # Componente principal da aplicação
│   ├── index.js            # Ponto de entrada da aplicação
│   ├── index.css           # Estilos globais
│   └── componentes/        # Componentes reutilizáveis da UI
│       ├── Banner/
│       ├── Botao/
│       ├── CampoTexto/
│       ├── Colaborador/
│       ├── Formulario/
│       ├── ListaSuspensa/
│       └── Time/
└── package.json            # Metadados do projeto e dependências
```

## Como Executar o Projeto

Para configurar e executar este projeto em sua máquina local, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone <url-do-repositorio>
    ```
    (Substitua `<url-do-repositorio>` pela URL real do seu repositório Git.)

2.  **Navegue até o diretório do projeto:**
    ```bash
    cd nexus
    ```

3.  **Instale as dependências:**
    ```bash
    npm install
    ```

4.  **Inicie a aplicação em modo de desenvolvimento:**
    ```bash
    npm start
    ```
    A aplicação será aberta automaticamente no seu navegador padrão em `http://localhost:3000`. O navegador recarregará automaticamente se você fizer edições.

### Scripts Disponíveis

No diretório do projeto, você pode executar:

*   `npm start`: Inicia a aplicação em modo de desenvolvimento.
*   `npm build`: Compila a aplicação para produção na pasta `build`.
*   `npm test`: Executa os testes da aplicação.
*   `npm eject`: Remove a dependência de build única e copia todas as configurações de build e scripts de dependência diretamente para o seu projeto. (Use com cautela, é uma operação irreversível).

## Como Usar

1.  Ao iniciar a aplicação, você verá um formulário na parte superior da página.
2.  Preencha os campos "Nome", "Cargo" e "Imagem" (com uma URL válida para a foto do colaborador).
3.  Selecione a "Time" desejada na lista suspensa.
4.  Clique no botão "Criar Card".
5.  O novo colaborador será adicionado à seção da equipe correspondente abaixo do formulário.

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões de melhorias ou encontrar algum bug, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## ✍️ Autor

Desenvolvido por **Danila Rocha**
