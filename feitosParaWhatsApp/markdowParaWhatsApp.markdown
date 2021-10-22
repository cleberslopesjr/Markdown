## Sabor* Markdown do WhatsApp

Segue abaixo um estudo rápido das marcações Markdown aceitas pelo WhatsApp.

### 1. Ao que parece o WhatsApp aceita apenas as quatro marcações Markdown abaixo:

#### 1.1. **Negritando** (HTML: \<strong\>)

Coloque a palavra que deseja **negritar** entre duas aspas:

\**negrito\**: **negrito**

**Obs:** ao negritar você está adiconando semântica ao texto.

#### 1.2. _Itálico_ (letra ligeiramente inclinada para a direita) (equivalente ao \<i\>\** em HTML)

Coloque a palavra que deseja em _itálico_ entre dois caracteres de sublinhado (\_):

\_italico\_: _itálico_

**Obs:** Apesar do equivalente em HTML, \<i\> não dar semântica ao texto, a palavra marcada em italico com Markdown, exemplificado acima, ganha semântica equivalente ao \<em\> em HTML.

#### 1.3. ~Tachado~

Coloque a palavra entre dois tils (~):

\~Tachado\~: ~Tachado~

#### 1.4. ```Monoespaçado```:

Coloque a palavra entre três sinais graves (\```):

\```Monoespaçado\```: ```Monoespaçado```


### 2. Todas as outras marcações Markdown não são aceitas pelo WhatsApp. Seguem alguns exemplos:

#### 2.1. Títulos:

# Título de nível 1
## Título de nível 2
### Título de nível 3
#### Título de nível 4
##### Título de nível 5
###### Título de nível 6

#### 2.2. Lista numerada (em HTML lista ordenada, "\<ol\>"):

1. Primeira linha da lista numerada 
2. Segunda linha da lista numerada
3. Terceira linha da lista numerada

#### 2.3. Lista não numerada (em HTML lista não ordenada, "\<ul\>"):

* Primeira linha da lista não numerada
* Segunda linha da lista não numerada
* Terceira linha da lista não numera

----------
##### Notas de Rodapé

\* Um "sabor Markdown" é uma versão dele. Cada aplicação implementa sua própria versão (sabor), e isso é o torna o Markdown confuso.

\** Está entrando em desuso. Atualmente a forma correta de colocar uma palavra em itálico é usando a propriedade CSS: "font-style: italic;"

*Demonstração:* ```p {font-style: italic;}```

###### Para uma perfeita visualização:

1. Instale uma extenção apropriada para a rendenização de arquivos Markdown no seu navegador;

**Obs:** eu instalei a extenção "[Markdown Viewer Webext](https://addons.mozilla.org/pt-BR/firefox/addon/markdown-viewer-webext/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search)" no Firefox, mas você pode escolher outra estenção, assim como outro navegador para visualizar.

2. Abra esse documento no Navegador após a instalação e ativação da extenção.
*******
Observação:
Fiz todo esse texto utilizando a marcação Markdown.
*******
Autor: [Cleber Lopes](https://github.com/cleberslopesjr)