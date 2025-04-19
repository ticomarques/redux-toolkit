# Redux-Toolkit

Neste repositorio consta um refactory do repositorio [redux](https://github.com/ticomarques/redux), onde consta um todo list, que foi desenvolvido usando o antigo redux.

Neste projeto está sendo usado o redux-toolkit, que é uma atualização do redux (projeto citado acima).

Consta também um repositorio teste do redux-toolkit, que foi nomeado como RTK [RTK](https://github.com/ticomarques/RTK).



## Metodologia usada

1 - Inicialmente foi testado o redux-toolkit para validar as novas funcionalidades. Esse repositorio é RTK [RTK](https://github.com/ticomarques/RTK).

2 - Em comparação o repositorio com o antigo redux foi criado, que é o repositorio [redux](https://github.com/ticomarques/redux). Neste repositorio consta um todo list, que foi desenvolvido usando o antigo redux.

3 - O repositorio [redux-toolkit](https://github.com/ticomarques/redux-toolkit) é refactory que atualiza o projeto todo list (usando redux antigo), para o redux-toolkit.

## Pontos relevantes

Atualizar um projeto escrito em redux para redux-toolkit é um processo simples, que pode ser feito em poucos passos.

1 - Instalar o redux-toolkit:


2 - Criar um arquivo store.js:

Neste arquivo o store será criado, que é o estado global da aplicação.

3 - Criar um arquivo slice.js:

Neste arquivo o slice será criado, que é a parte do estado global da aplicação que será atualizada.

4 - Criar um arquivo index.js (main.js):

Neste arquivo o index será criado a conexao com o store usando o Provider do redux-toolkit.

5 - Atualizar o arquivo App.js:

Neste arquivo o App será atualizado para usar o redux-toolkit. Onde inicialmente o useSelector e o useDispatch serão importados.

O useSelector é usado para acessar o estado global da aplicação, que vem do arquivo main.js (index.js) pelo Provider.

O useDispatch é usado para atualizar o estado global da aplicação.

* O arquivo main.js (index.js) nem se conecta com o store.js.

A importação dos reducers vindas do store.js (slices).

## Workflow

Store > Provider (main.js) > App (App.js) > useSelector > useDispatch > reducer (slice.js) 





