#  VKT
## Volume de tráfego das capitais brasileiras e suas Regiões Metropolitanas



É muito fácil colocar algumas palavras em ** negrito ** e outras palavras em * itálico * com Markdown. Você pode até [link para o Google!] (Http://google.com)

Às vezes você quer listas numeradas:

1 um
2. Dois
3. Três

Às vezes você quer pontos de bala:

* Comece uma linha com uma estrela
* Lucro!

Alternativamente,

- Traços funcionam tão bem
- E se você tiver subpontos, coloque dois espaços antes do travessão ou estrela:
  - Assim
  -
  - 
  -
  -
  -            E isto
Se você deseja incorporar imagens, faça o seguinte:

! [Imagem de Yaktocat] (https://octodex.github.com/images/yaktocat.png)

Se você deseja incorporar imagens, faça o seguinte:

! [Imagem de Yaktocat] (https://octodex.github.com/images/yaktocat.png)

Existem muitas maneiras diferentes de estilizar o código com a marcação do GitHub. Se você tiver blocos de código embutidos, envolva-os em crases: `var example = true`. Se você tem um bloco de código mais longo, pode recuar com quatro espaços:

    if (isAwesome) {
      retornar verdadeiro
    }

O GitHub também oferece suporte a algo chamado code fencing, que permite várias linhas sem indentação:

`` `
if (isAwesome) {
  retornar verdadeiro
}
`` `

E se você quiser usar o realce de sintaxe, inclua o idioma:

`` `javascript
if (isAwesome) {
  retornar verdadeiro
}

O GitHub oferece suporte a muitos extras no Markdown que ajudam você a fazer referência e se conectar com as pessoas. Se você quiser dirigir um comentário a alguém, pode prefixar o nome dela com o símbolo @: Ei, @kneath - adorei seu suéter!

Mas tenho que admitir, listas de tarefas são minhas favoritas:

- [x] Este é um item completo
- [] Este é um item incompleto

Ao incluir uma lista de tarefas no primeiro comentário de um problema, você verá uma barra de progresso útil em sua lista de problemas. Ele também funciona em solicitações pull!

E, claro, emoji!

Guia de sintaxe
Esta é uma visão geral da sintaxe do Markdown que você pode usar em qualquer lugar no GitHub.com ou em seus próprios arquivos de texto.

Cabeçalhos
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
Ênfase
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
Listas
Não ordenado
* Item 1
* Item 2
  * Item 2a
  * Item 2b
Ordenado
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
Imagens
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
Links
http://github.com - automatic!
[GitHub](http://github.com)
Citações em bloco
As Kanye West said:

> We're living the future so
> the present is our past.
Código inline
I think you should use an
`<addr>` element here instead.

GitHub Flavored Markdown
GitHub.com usa sua própria versão da sintaxe Markdown que fornece um conjunto adicional de recursos úteis, muitos dos quais facilitam o trabalho com conteúdo em GitHub.com.

Observe que alguns recursos do GitHub Flavored Markdown estão disponíveis apenas nas descrições e comentários de Issues e Pull Requests. Isso inclui @ menções, bem como referências a hashes SHA-1, problemas e solicitações de pull. As listas de tarefas também estão disponíveis nos comentários do Gist e nos arquivos Gist Markdown.

Realce de sintaxe
Aqui está um exemplo de como você pode usar o realce de sintaxe com GitHub Flavored Markdown :

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
Você também pode simplesmente recuar seu código em quatro espaços:

    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
Aqui está um exemplo de código Python sem realce de sintaxe:

def foo():
    if not bar:
        return True
Listas de Tarefas
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
Se você incluir uma lista de tarefas no primeiro comentário de um problema, obterá um indicador de progresso útil em sua lista de problemas. Ele também funciona em solicitações pull!

Mesas
Você pode criar tabelas reunindo uma lista de palavras e dividindo-as com hifens -(para a primeira linha) e, em seguida, separando cada coluna com uma barra vertical |:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
Se tornaria:

Primeiro Cabeçalho	Second Header
Conteúdo da célula 1	Conteúdo da célula 2
Conteúdo na primeira coluna	Conteúdo na segunda coluna
Referências SHA
Qualquer referência a um hash SHA-1 do commit será automaticamente convertido em um link para aquele commit no GitHub.

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac
Referências de problemas dentro de um repositório
Qualquer número que se refira a um problema ou solicitação pull será automaticamente convertido em um link.

#1
mojombo#1
mojombo/github-flavored-markdown#1
Nome de usuário @ menções
Digitar um @símbolo, seguido por um nome de usuário, notificará essa pessoa para vir e ver o comentário. Isso é chamado de “@ menção ”, porque você está mencionando o indivíduo. Você também pode @ mencionar equipes dentro de uma organização.

Vinculação automática para URLs
Qualquer URL (como http://www.github.com/) será automaticamente convertido em um link clicável.

Tachado
Qualquer palavra agrupada com dois tis (como ~~this~~) aparecerá riscada.

Emoji
GitHub suporta emoji !

Para ver uma lista de todas as imagens que apoiamos, verifique a folha de referências de Emoji .





