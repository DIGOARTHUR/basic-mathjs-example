
<!--  docs: update Readme   -->





<!-- VISUALIZAR NO README VSCODE  CTRL + K  V -->

<!-------------------------------------------------------------------->
<!-- COMO CONSTRUIR BADGES ---------
<!--------------------------------------------------------------------
https://www.youtube.com/watch?v=cRoBt6AZgjc
https://dev.to/envoy_/150-badges-for-github-pnk

    BUILD 
      https://shields.io
    ICONS
    https://simpleicons.org/?q=react

     EXEMPLO
     <a href="https://devdigoarthur.notion.site/Map-a87c73417a064372b122bf448f4c6ed4"> ![Alt ou título da imagem](https://img.shields.io/badge/-JavaScript-/?logo=JavaScript&logoColor=white&color=yellow)<a/>

# JavaScript - Nome que aparece na Bag
# logo=JavaScript - Muda a logo vide <https://simpleicons.org/?q=react>
# color=yellow - Define a cor da bag vide <https://shields.io>
# logoColor=white - Define a cor do icone
-->







<!------------------------------------ LANGUAGE BUTTONS-->
<!--
<div align="right">
<a href="https://github.com/DIGOARTHUR/github-automated-repos#readme">
    <img  height="35" src="https://github-production-user-asset-6210df.s3.amazonaws.com/59892368/257623321-95c81f57-b751-4956-b0ab-7a804ae44506.svg" alt="language_USA" border="0">
<a/>
<br/>
<a href="https://github.com/DIGOARTHUR/github-automated-repos/blob/main/README_PT.md">
<img  alt="language_Brazil"  height="35" src="https://github-production-user-asset-6210df.s3.amazonaws.com/59892368/277121999-ebbd8cff-f85a-49a6-aa6b-acd3fde2adb8.svg">
<a/>

</div>
-->


<!-------------------------------------------------------------------->
 <!------------------------------------BANNER PROJECT----------------->
<!-------------------------------------- 280 x 1400 ------------------------------>







<h1 align="center">
  Construa seu pacote/biblioteca NPM
</h1>

<p align="center">
  <!-------------------------------------------------------------------->
  <!------------------------------------PROJECT ICON-------------------->
  <!-------------------------------------------------------------------->
  <img height="200px" alt="bashftreactgit" title="bashftreactgit" src="https://github-production-user-asset-6210df.s3.amazonaws.com/59892368/283223606-f9bea4a6-699c-4e7b-8d9a-ca968fb017c0.svg" />
  <br>
  <br>
  <i>De forma fácil e prática! Utilize Javascript <img height="15px" alt="bashftreactgit" title="bashftreactgit" src="https://github-production-user-asset-6210df.s3.amazonaws.com/59892368/283226388-6bd63b03-9906-4da0-8a4b-d06c900e97b1.svg" /> / Typescript <img height="15px" alt="bashftreactgit" title="bashftreactgit" src="https://github.com/DIGOARTHUR/how-to-build-NPM-package/assets/59892368/6f5dc450-35f9-47b3-8da1-74223764fa07.svg" /> e React <img height="15px" alt="bashftreactgit" title="bashftreactgit" src="https://github.com/DIGOARTHUR/how-to-build-NPM-package/assets/59892368/d0e89ec9-e557-40e8-842b-e817af6df9b7.svg" /> para criar funções, componentes, hooks e etc... </i>
	

  <br>

</p>

<h1 align="center">

</h1>

<!-------------------------------------------------------------------->
 <!------------------------------------BADGES PROJECT  ---------------->
 <!-------------------------------------------------------------------->

  ![GitHub last commit](https://img.shields.io/github/last-commit/digoarthur/how-to-build-NPM-package
)
  ![GitHub](https://img.shields.io/github/license/digoarthur/how-to-build-NPM-package
)
  
  
<!-------------------------------------------------------------------->
 <!------------------------------------STACKS && TOOLS --------->
  <!-------------------------------------------------------------------->
  

  
  
<!-------------------------------------------------------------------->
<!------------------------------------SUMMARY------------------------->
<!-------------------------------------------------------------------->
<p align="center">
  <a href="https://github.com/DIGOARTHUR/how-to-build-NPM-package/tree/main#--sobre-a-aplicação">Sobre a aplicação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/DIGOARTHUR/how-to-build-NPM-package#--configurando-ambiente"> Configurando Ambiente</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/DIGOARTHUR/how-to-build-NPM-package#--build"> Construindo Pacote</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/DIGOARTHUR/how-to-build-NPM-package#--install-pacote---local"> Instalação Pacote - LOCAL</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
	</p>  
 
 <p align="center">
  <a href="https://github.com/DIGOARTHUR/how-to-build-NPM-package#--deploy-npm-remoto"> Deploy NPM</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="https://github.com/DIGOARTHUR/how-to-build-NPM-package#--install-pacote---remoto"> Instalação Pacote - REMOTO</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>  

   <!-------------------------------------------------------------------->
   <!------------------------------------DESCRIPTION--------------------->
   <!---write here : talk a little about project: what's does, example.  -->
   
# <img  alt="skills"  width="40" height="40" src="https://user-images.githubusercontent.com/59892368/148622497-164365e8-f6b0-4f40-bc75-a0ed4da6059b.png">  Sobre a aplicação 
---
> Teve uma ideia de funcionalidade super interessante, quer colocar em prática e disponibilizar para a comunidade usar? A plataforma NPM te dá essa possibilidade. Neste repositório
> darei os passos para a construção do seu `pacote`/`biblioteca` para que possa criar suas `Funções`, `Componentes`,`Hooks`  etc, e mostrar para o Mundo! Passo a passo de forma prática e clara.

---

  <br>   <br>  

 <!-------------------------------------------------------------------->
  <!------------------------------------CONTENT------->
  <!-------------------------------------------------------------------->

<br>   <br>  

# <img  alt="skills"  width="40" height="40" src="https://github-production-user-asset-6210df.s3.amazonaws.com/59892368/265221445-3a17120c-8847-4987-95ba-2014dc8d2e5f.png">  Configurando Ambiente


  
## `1.` git init

para inicializar o arquivo (`.git`) de versionamento GIT

```powershell
git init
```
## `2.` npm init 
para inicializar o arquivo `package.json`

```powershell
npm init
```
- **_package name_**: insira aqui o nome do seu projeto. ( todas letras minúsculas)

- **_version_**: a versão inicial é a 1.0.0 (pode deixar a que estiver)

- **_description_**: descreva resumidamente sobre o que é o seu projeto, do que se trata.

- **_entry point_**: nomear o arquivo principal, o arquivo que quando for feita a importação da sua bibilioteca os arquivos serão localizados nele. Pode nomear /src/index.js (caso use Javascript) ou /src/index.ts (caso use Typescript)

- **_test command_**: iremos configurar em outra etapa, deixe em branco.

- **_git repository_**: coloque aqui a URL do repositório criado lá no GitHub para este projeto 

- **_keywords_**: coloque aqui separado por virgulas, palavras chaves que tenha relação com seu projeto.

- **_author_**: insira seu nome, apelido…

- **_license_**: nome da licença que dá direito a cópia, reprodução, melhorias etc… Pode colocar MIT.

	- Arquivo **`package.json`** ficará assim, por exemplo:

	```json
	{
  "name": "how-to-build-npm-package",
  "version": "1.0.0",
  "description": "projeto feito para exemplificar a criação de pacotes/bibliotecas NPM.",
  "main": "index.ts",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "https://github.com/DIGOARTHUR/how-to-build-NPM-package.git"
  },
  "keywords": [
    "NPM",
    "Tutorial",
    "Building",
    "Package"
  ],
  "author": "@digoarthur",
  "license": "MIT",
  "bugs": {
    "url": "https://github.com/DIGOARTHUR/how-to-build-NPM-package/issues"
  },
  "homepage": "https://github.com/DIGOARTHUR/how-to-build-NPM-package#readme",
	}
	```

## `3.` Configurando arquivo `package.json`

Adicione as seguinte propriedades:


- **_main_**: altere o caminho para src/index.ts ou index.js”. Assim o import do pacote poderá ser feito apenas pelo o nome dele.

- **_typings_**: insira o caminho ./dist/index.d.ts. O erro indicando algo sobre a tipagem irá desaparecer.

Acrescente outras propriedades mas agora nos **_scripts_**:
- **_scripts_**:
	- **_clean_**: insira o seguinte código abaixo, é um código [bash](https://github.com/DIGOARTHUR/bash-commands-tricks) que apagará a pasta dist no processo de build para que um novo seja criado.
 	```json
	"clean": "rm -rf dist",
	```
  	- **_build_**: insira o seguinte código abaixo, é um comando que removerá o arquivo dist principal, rodará o typescript, irá mover os arquivos package.json README.md para pasta./dist.
 	```json
	"build": "npm run clean && tsc && cp package.json README.md ./dist",
	```
  	- Arquivo **`package.json`** ficará assim, por exemplo:

	```json
	{
  "name": "how-to-build-npm-package",
  "version": "1.0.0",
  "description": "projeto feito para exemplificar a criação de pacotes/bibliotecas NPM.",
  "main": "/src/index.ts",
  "typings": "./dist/index.d.ts",
  "scripts": {
    "clean": "rm -rf dist",
    "build": "npm run clean && tsc && cp package.json README.md ./dist",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/DIGOARTHUR/how-to-build-NPM-package.git"
  },
  "keywords": [
    "NPM",
    "Tutorial",
    "Building",
    "Package"
  ],
  "author": "@digoarthur",
  "license": "MIT",
  "bugs": {
    "url": "https://github.com/DIGOARTHUR/how-to-build-NPM-package/issues"
  },
  "homepage": "https://github.com/DIGOARTHUR/how-to-build-NPM-package#readme",
	}
	```

 ## `4.` Instalando bibliotecas base

 ### `4.1` React
Para criação de Componentes será preciso instalar o React


```bash
yarn add -D react
```

 ### `4.2` Typescript
Instalação do Typescript, instale-o e nao se esqueça de instalar os @types React.


```bash
yarn add -D typescript
```

#### `4.2.1` inicializar o arquivo `tsconfig.json`
Arquivo responsável pela as configurações do Typescript. Este  Pode copiar e colar essa configurações no arquivo.

```powershell
npx tsc --init
```

```json
{
  "compilerOptions": {
    "strict": true,
    "jsx": "react",
    "declaration": true,
    "esModuleInterop": true,
    "outDir": "dist",
    "target": "es6",
    "module": "es6",
    "lib": ["es6", "dom", "es2017"],
    "moduleResolution": "node"
  },
  "include": ["src/**/*"]
}
```

 ### `4.3` Instalar tipagem React
Instalar a tipagem de funções React por estar utilizando Typescript
 
```bash
yarn add -D @types/react
```

#  Estrutura de arquivos/pastas
	
    lib-project
   		├── .git (oculto)
    	├── node_modules	
    	├── package.json
    	└── tsconfig.json
     




  <br>   <br>  
  
# <img  alt="skills"  width="40" height="40" src="https://github-production-user-asset-6210df.s3.amazonaws.com/59892368/284266592-ae612623-650a-4d12-817c-9d92312db091.svg">  Construindo Pacote

## `1.` Crie uma pasta source src
As pastas e arquivos de construção de funcionalidades da biblioteca serão colocados aqui.

 ### `1.1` Crie as funcionalidades da biblioteca
 Voce pode criar, por exemplo:

- Funções
- Componentes
- Hooks
- Etc…

### `1.2.` Crie o arquivo configurado no package.json (main) _index.js_ ou _index.ts_ dentro da pasta src.

#### `1.2.1` Exporte aqui as Funções, Componentes, Hooks criados por você, para que seja possivel fazer o import no momeneto da instalação do seu pacote/biblioteca. Abaixo exemplo da biblioteca criada aqui neste repositório:

```tsx
export {TableGenerator} from './Components/TableGenerator';
export { Division } from './Math/division/division';
export { Multiplication } from './Math/multiplication/multiplication';
export { Subtraction } from './Math/subtraction/subtraction';
export { Sum } from './Math/sum/sum';
```

## `2.` Testes (Componentes, Funcoes, Hooks, etc...)
O teste é opcional mas, como boas práticas, é essecial introduzi-lo nos seus projetos. Aqui é aplicado o `Jest`.
Este teste se tem muito contato direto na plataforma de resolução de algoritmos [exercism.org](exercism.org/).
Um exemplo aplicado são das funcoes matemáticas, onde é importado a funcao e aplicado o teste em um arquivo.

### `2.1.` Instalando o Jest e o @types

```bash
yarn add -D jest ts-jest @types/jest
```


Será criado um arquivo `jest.config.js`

```javascript
{
module.exports = {
    preset: "ts-jest",
    testEnvironment: "node",
  };
}

```

## `2.2` Configurando arquivo `package.json`
Para todar o teste será preciso fazer uma configuração na propriedade:
- **_scripts_**
	- **_teste_**:"jest"

```json
	{
  "name": "how-to-build-npm-package",
  "version": "1.0.0",
  "description": "projeto feito para exemplificar a criação de pacotes/bibliotecas NPM.",
  "main": "/src/index.ts",
  "types": "./dist/index.d.ts",
  "scripts": {
    "clean": "rm -rf dist",
    "build": "npm run clean && tsc && cp package.json README.md ./dist",
    "test": "jest"
  },
  "repository": {
  ...
  ...
``` 




## `2.2` Criando arquivo para teste
Aqui eu criei o arquivo no mesmo local que a função. Nomeei: `nomeDaFuncao.test.ts` , um exemplo aqui, `division.teste.ts`.
Importei a funcao no arquivo criado e então apliquei um possibilidade do que realmente deve ocorrer caso seja aplicado o teste.

```javascript
import { Division } from './division';

test('division two numbers correctly', () => {
  const result = Division(4, 2);
  expect(result).toBe(2);
});

```

### `2.2.` Rodando teste.

```bash
yarn test
```
Por exemplo

<div align="center">
	
![image](https://github.com/DIGOARTHUR/how-to-build-NPM-package/assets/59892368/cde877c5-c26a-4347-8d14-5147f5860241)

</div>


#  Estrutura de arquivos/pastas

    lib-project
     ├── .git (oculto)
     ├── node_modules
     ├── `src`
     │    └── `Components`
     │    │   	├── TableGenerator.tsx
     │    │   	├── style.css
     │    │ 
     │    └── `Functions`
     │      │    ├── ...
     │      └── `Hooks`
     │      │    ├── ...
     │      └── `index.ts`
     │
     ├── package.json
     ├── tsconfig.json
    

  <br>   <br>  

```bash
yarn add -D @types/jest
```


  
# <img  alt="skills"  width="40" height="40" src="https://github-production-user-asset-6210df.s3.amazonaws.com/59892368/284275442-d1112329-3b00-47fb-9fe1-b519bc654889.svg">  Build
O Build é muito importante após qualquer alteração no código, pois ele gerará os arquivos .js na pasta `dist` para que seja possivel a intepretação da linguagem Typescript.

Rodar este comando no `Git Bash Here` que emula um termninal Linux, para que aqueles comandos configurados no `package.json` possam rodar.

<div align="center">
<img  alt="skills"   src="https://github.com/DIGOARTHUR/how-to-build-NPM-package/assets/59892368/ed0a2c59-6aeb-4c5a-9c7d-de96ef3e8464.png">

</div>


```powershell
npm run build
```

#  Estrutura de arquivos/pastas

    lib-project
     ├── .git (oculto)
     ├── `dist`
     ├── node_modules
     ├── src
     │    └── Components
     │    │   	├── TableGenerator.tsx
     │    │   	├── style.css
     │    │ 
     │    └── Functions
     │      │    ├── ...
     │      └── Hooks
     │      │    ├── ...
     │      └── index.ts
     │
     ├── package.json
     ├── tsconfig.json




  <br>   <br>  
  
# <img  alt="skills"  width="40" height="40" src="https://github.com/DIGOARTHUR/how-to-build-NPM-package/assets/59892368/74f44c47-891a-4276-a2c6-d4153bd8aed5">  Install Pacote - `LOCAL` 


## `1.` Publicação `local`  
Ainda no `Git Bash Here`, rode o comando para disponibilizar o pacote de forma local, para que voce possa testá-lo já rondado um projeto React.

```powershell
npx yalc publish
```
## `2.` Instalação biblioteca `local` 
Agora na aplicação React, rode o seguinte comando para que possa executar uma instalação local:
```powershell
npx yalc add <nome da biblioteca>
```
## `3.`  Importe sua biblioteca
As Funções, Componentes, Hooks, etc… são importados daquele arquivo index.js ou index.ts. Aqui um exemplo da biblioteca deste repositório…
```powershell
import {TableGenerator} from 'how-to-build-npm-package'
```
# <img  alt="skills"  width="40" height="40" src="https://github-production-user-asset-6210df.s3.amazonaws.com/59892368/284279944-e6593b0e-e98c-407a-9ab6-493243f10442.svg">  Deploy NPM `REMOTO`

## `1.` Crie uma conta na plataforma NPM

## `2.` Login NPM

 No diretório do seu projeto pode ser um CMD, PowerShell, Gitbash e até o terminal do Vscode, rode seguinte comando:
 
```powershell
npm login
```

Aperta ENTER e abrirá uma página de login do NPM, caso nao esteja logado.

## `3.` Publicação Pacote `remoto`

```powershell
npm publish
```

  <br>   <br>  
  
# <img  alt="skills"  width="40" height="40" src="https://github-production-user-asset-6210df.s3.amazonaws.com/59892368/284280005-211554fa-5cac-45cb-8184-30c97ccecc58.svg">  Install Pacote - `REMOTO`

Agora na aplicação React, rode o seguinte comando para que possa executar uma instalação da sua biblioteca:
 

```powershell
yarn add <nome do pacote>
```

```powershell
npm install <nome do pacote>
```
