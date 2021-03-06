# emilcam-client-admin
Projeto desenvolvido em Javascript com a biblioteca React, consistindo numa interface com o usuário administrador da plataforma de gerenciamento de câmeras de videomonitoramento EmilCam. Consome a API emilcam-api.

### Introdução

Estas instruções lhe permitirão obter uma cópia do projeto e executá-lo na sua máquina local para desenvolvimento e testes. Veja as notas de compilação para saber como compilar o projeto.

## Pré-requisitos

Por se tratar de um cliente, este projeto consome os serviços de uma API. No entanto, para testar e desenvolver esse projeto é possível que a API seja emulada pelo JSON SERVER, um programa que pode ser instalado na sua máquina através no comando `npm install json-server -g` e `npm install yarn -g`. O comando NPM, por sua vez, pode ser instalado através do comando `sudo apt install nodejs` (no GNU/LINUX distribuição Debian/Ubuntu/derivados).

Após a instalação das ferramentas mencionadas, devem ser usados os arquivos para emular o banco de dados, seguindo os modelos contidos na pasta raiz `db_*.json` e a [documentação](https://github.com/typicode/json-server/blob/master/README.md) do Json-Server (exemplo no script `rodar_db` na raiz do projeto).

## Instalação

Após o download deste projeto, dentro de sua pasta principal deve ser executado o comando `yarn`, para que seja feito o download e a instalação das dependências do projeto.

Após a instalação das dependências, basta executar os passos informados nas notas a seguir.

## Servidor de desenvolvimento

Execute `yarn start`, no terminal de comando, para iniciar o servidor de desenvolvimento. Acesse o endereço web `http://localhost:3000/`. A aplicação será atualizada automaticamente caso seja alterado o código fonte.

Para parar a execução do servidor de desenvolvimento, pressione `Ctrl + C`, no terminal de comando.

## Compilação

Execute `yarn build` para compilar o projeto. O projeto compilado poderá ser encontrado no diretório build/.

## Ajuda

Para obter mais informações sobre a biblioteca React, acesse [React Docs](https://pt-br.reactjs.org/docs/getting-started.html).

## Licença

Este projeto está licenciado sob os termos da [GNU General Public License v3.0](http://licencas.softwarelivre.org/gpl-3.0.pt-br.html).

## Autor

* **Moacir Costa** - *Desenvolvedor inicial*

## Agradecimentos

* A Jesus Cristo, que me deu fé, coragem, inteligência e determinação para chegar até aqui
* Ao meu irmão, Claudio Costa, que me ensinou a desenvolver sistemas web nos seus momentos de folga

## Status do projeto

* É necessário fazer a validação dos formulários de inserção de informações
* A ferramenta de testes e sincronização TRAVIS está desconfigurada
