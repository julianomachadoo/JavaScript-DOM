# Apontamentos 

## 1. Selecionando elementos

O DOM (Document Object Model) e o JavaScript, juntos, possuem grande poder de modificar dinamicamente a estrutura de um documento HTML. Sendo possível, por exemplo:


- Adicionar/modificar/remover tags, textos, imagens e qualquer elemento no HTML.

- Alterar estilos CSS da página.

- Criar novos eventos HTML.


Vamos conferir formas de realizar os itens listados no tópico acima.

__Métodos para selecionar elementos no HTML__

* `document.getElementByID(id)`- Selecionar um elemento pelo ID. 
* `document.getElementsByTagName(name)` - Selecionar um elemento pelo nome.
* `document.getElementsByClassName(name)` - Selecionar um elemento pelo nome da classe.

__Propriedades e métodos para alterar elementos no HTML__

* `element.innerHTML` - Esta propriedade obtém ou altera qualquer elemento no HTML, inclusive tags.
* `element.innerText` - Esta propriedade permite inserir textos no HTML.
* `element.attribute` - Esta propriedade altera o valor de um elemento HTML.
* `element.setAttribute(atributo, valor)` - Este método altera o valor de um atributo de um elemento HTML.

__Adicionando e excluindo elementos__

* `document.write()` - Escreve no fluxo de saída do HTML.
* `document.appendChild()` - Adiciona um elemento HTML.
* `document.removeChild()` - Remove um elemento HTML.
* `document.replaceChild()` - Substitui um elemento HTML.
* `document.createElement()` - Cria um elemento HTML.