# repositorio_modelo
## Boas Práticas

- O nome do repositório precisa ter o mesmo nome do projeto. por exemplo: Projeto Siga
- Todo arquivo README precisa informar:
  - Visão geral do projeto
  - Tecnologias utilizadas
  - Como instalar ou utilizar esse projeto
  - Contribuições (Equipe)
  - Como pode contribuir? (Comunidade externa)

  ## Organização de Pastas
- Toda linguagem de programação ou framework exige uma
organização em pastas. Em comum todas elas tem essa estrutura:

  - /src -> A pasta indicada para colocar o código fonte do projeto.
  - /test -> A pasta é indicada para colocar os testes unitários.
  - /public -> A pasta é indicada para colocar o Front-End ou qualquer arquivo que precisa ficar à nível público. A nível de API, teriamos os ENDPOINTs (Rotas de acesso).
  - /config -> (ou scripts) arquivos de configuração ou instalação das bibliotecas do projeto. Pode ficar também na raiz do projeto - config é uma pasta opcional.
  - /docs -> A pasta é indicada para guardar imagens ou documentos relacionados ou projeto. Por exemplo: Diagramas, Fluxogramas, Mapa mentais, Canva e etc.

  ## Utilizar boas práticas em Commits

  - É necessário realizar os dois:

  - Commit Atômico: Realizar commits pequenos -> a unidade de trabalho.
  - Commit Semântico: É informar com sufixo e em poucas palavras o que foi realizado nessa unidade de trabalho.

  ## Na raíz do projeto

- É necessário ter 
- o gitignore: é utilizado para informar ao git quais extensões ou pastas que precisam ser ignoradas 
- license: é informado qual é a licença do projeto (obrigatório quando o projeto é público)
- contribuiting: é informado quem são os atores e quem pode contribuir
- changelog: é utilizado para informar o histórico de versões do projeto.

## Gerenciar Branchs

- Um projeto pode ter dessas branchs abaixo:
- main (ou master): Versão estável do projeto (Ou aquilo que o público está utilizando no moomento).
- homolog: Versão posterior a de desenvolvimento, ou seja, é a de testes. Anterior a main. Normalmente antecipa a main
- develop: 
  - Versão em desenvolvimento, normalmente é utilizado por desenvolvedores do projeto. 
  - Centralizadora das modificações realizadas pelos devs.

- Branchs relacionadas ao card do kanban (branch de trabalho)
  - [sufixo-atomic]/[nome-card]
  - cada card do kanban vai ter uma branch
  - cada dev pega um ou N cards do kanban
  - cada branch é baseada da develop
  - no final ela é mesclada a develop


- Flow das branchs: 
  - branch de trabalho -> develop -> homolog -> mai
n

 

