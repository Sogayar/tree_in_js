# Projeto de Visualização de Árvore com D3.js

Este projeto utiliza a biblioteca D3.js para criar uma visualização interativa de uma estrutura de árvore baseada em dados fornecidos em um arquivo JSON. A estrutura da árvore é organizada hierarquicamente, permitindo a navegação através de pastas e links.

## Estrutura de Pastas
'''
  Public/
      │
      │
	    │── css/
      │    └── arf.css
      │
      │── js/
      │    └── arf.js
	    │    └── d3.v3.min.js
	    │
	    │── arf.json
      │
      └── README.md
'''

### Descrição de Cada Pasta e Arquivo

- **Public/**: Diretório principal que contém todos os arquivos do projeto.

  - **css/**: Contém os arquivos de estilo CSS.
    - **arf.css**: Estilos personalizados para a visualização da árvore, definindo a aparência dos elementos na interface.

  - **js/**: Contém os arquivos JavaScript utilizados para a lógica do projeto.
    - **arf.js**: Script principal que carrega os dados do arquivo JSON e utiliza D3.js para construir e renderizar a árvore.
    - **d3.v3.min.js**: Biblioteca D3.js (versão 3) que permite a criação de visualizações de dados interativas.

  - **arf.json**: Arquivo JSON que contém a estrutura de dados da árvore, definindo a hierarquia de "folders" e "urls". Este arquivo é fundamental para a construção da visualização.

  - **README.md**: Documento que descreve o projeto, sua estrutura e como utilizá-lo.

## Como Funciona o Código

1. **Carregamento de Dados**: O arquivo `arf.json` é carregado usando `d3.json()` no arquivo `arf.js`. Isso traz a estrutura hierárquica que será visualizada.

2. **Construção da Árvore**: Usando a estrutura de dados do JSON, o D3.js cria uma árvore interativa. Cada "folder" pode ser expandido ou colapsado, revelando ou escondendo seus filhos.

3. **Interatividade**: A visualização permite que os usuários cliquem nos nós para explorar mais profundamente a hierarquia ou acessar os links especificados nos nós do tipo "url".

## Como Executar o Projeto

1. **Clone o Repositório**: Faça o download ou clone este repositório em sua máquina.
2. **Abra o index.html**: Abra o arquivo `index.html` em um navegador para visualizar a árvore interativa.
3. **Interaja com a Árvore**: Navegue pela estrutura clicando nos nós para expandir ou colapsar os "folders" e acessar os links.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para me mandar uma mensagem ou abrir uma pull.


