# Vue JS Course
## Installation
```sh
cd projetos
Usando Extensao Live Server
```
## Plugins
| Live Server| Extensao Live Server para rodar aplicação no VS Code|
| ------ | ------ |
| Vetur| Extensao Vetur para facilidade com Vue|
## Conteudos
| Manipulação de eventos||
| ------ | ------ |
| Manipulação de eventos ||
| Implementando modificadores||
| Renderizando elementos condicionalmente|  Para if;else if;else precisa estar no mesmo nivel|
| Renderizando elementos condicionalmente|  v-show, processamento mais rapido, porem deixa elemento no DOM |
| Injeção  de  HTML| v-html,  substitui o conteudo ja existente   |
| Insetindo texto| v-text,  substitui o conteudo ja existente |
| v-once| faz com que elementos HTML sejam renderizados apenas uma vez |
| v-for| laços de repetição |
| v-for| destructuring assingment |

## Informações
CLI: command line interface
Arrow Function (faz referencia ao escopo global ou de função ao utilizar o this)

## Configurações
git config --global user.email "luidigastech@gmail.com"


## Conteudos estudo

*  [x] destructuring assingment
Exemplo:

```javascript
let options = {
  title: "Menu",
  width: 100,
  height: 200
};

let {title, width, height} = options;

alert(title);  // Menu
alert(width);  // 100
alert(height); // 200
```