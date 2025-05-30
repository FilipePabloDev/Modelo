# Modelo

## Boas Práticas
 - O nome do rpositório precisa ter o mesmo nome do Projeto. Por exemplo: Projeto SIGA.
 - Todo arquivo README precisa informar:
  - Visão Geral do Projeto
  - As Tecnologias utilizadas
  - Como instalar ou utilizar esse projeto
  - As tecnologias utilizadas
  - Como instalar e utilizar o Software
  - 


## Organização de Pastas

    -Toda Linguagem de Progamação ou Framework exige uma organização em pastas. Em comúm todas elas essa estrutura:

        -/src -> A pasta indicada para colocar o código fonte do projeto (Back-end)
        -/test -> A pasta é indicada para colocar os testes unitários
        -/public -> A pasta é indicada pra colocar o Front-End ou qualquer arquivo que precisa ficar á nível Público. A nível de API,teriamos os ENDPOINTs (Rotas de acesso)
        -/config -> (ou scripts) arquivos de configuração ou instalação de bibliotecas do projeto (isso também pode ficar na raiz do projeto)
        -/docs -> A pasta é indicada para guardar imagens ou docs relacionados ao projeto. Por exemplo: Diagramas, Fluxogramas, Mapa Mentais, Canvas e etc.


## Utilizar boas práticas em Commits
    - Commit Atômicos: Realizar commits pequenos -> a unidade de trabalho

    - Commit Semântico: É informar com sufixo e em poucas palavras o que foi realizado nessa unidade de trabalho


# Na raiz do Projeto

    - É necessário ter
    - o gitignore: é utilizado para informar ao git quais extensões ou pastas que precisam ser ignoradas
    - license: É informado qual é a licença do projeto (obrigatório quando o projeto é público)
    - contribuiting: É informado quem são os autores e como contribuir
    - changelog: é utilizado para informar o Histórico de Versões do projeto

## Gerenciar Branchs
    - um projeto pode ter algumas dessas branchs abaixo:
    
    - main (ou master): 

        - Versão estável do projeto ( ou aquilo que o público está utilizando no momento)
        - Normalmente a main é atualizada no final de cada sprint, recebe tudo que foi realizada na homolog(foi testado e aprovado)
        - no final é meclado tudo para a main

    - Flow das Branchs:

        - branch-de-trabalho -> develop -> homolog -> main
        
    - develop: 

        -Versão em desenvolvimento, normalmente é utilizado por Desenvolvedores do projeto. 
        - Centralizadora das modificações realizadas pelos devs (Criando branchs dentro delas)

    -Branchs relacionadas ao card do kanban:

        - [sufixo-atomic]feat/[nome-card]
        - cada card do kanban vai ter uma branch
        - cada dev pega um ou N cards do Kanban
        - cada branch é baseada da develop

    - homolog: (ou tests): 

        - Versão posterior a de desenvolvimento, ou seja é a de testes. Normalmente ela antecipa a main

    