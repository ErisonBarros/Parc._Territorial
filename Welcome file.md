# Bem-vindo ao StackEdit!

Oi! Sou seu primeiro arquivo Markdown no ** StackEdit ** . Se você quiser aprender sobre StackEdit, você pode me ler. Se você quiser jogar com Markdown, você pode me editar. Depois de terminar comigo, você pode criar novos arquivos abrindo o ** explorador de arquivos ** no canto esquerdo da barra de navegação.


# Arquivos

StackEdit armazena seus arquivos em seu navegador, o que significa que todos os seus arquivos são salvos automaticamente localmente e estão recuperados ** offline! **

## Crie arquivos e pastas

O explorador de arquivos pode ser acessado usando o botão no canto esquerdo da barra de navegação. Você pode criar um novo arquivo clicando no botão ** Novo arquivo ** no explorador de arquivos. Você também pode criar pastas clicando no botão ** Nova pasta ** .

## Mudar para outro arquivo

Todos os seus arquivos e pastas são alternativos como uma árvore no explorador de arquivos. Você pode alternar de um para outro clicando em um arquivo na árvore.

## Renomear um arquivo

Você pode renomear o arquivo atual clicando no nome do arquivo na barra de navegação ou clicando no botão ** Renomear ** no gerenciador de arquivos.

## Excluir um arquivo

Você pode excluir o arquivo atual clicando no botão ** Remover ** no explorador de arquivos. O arquivo será movido para o ** Lixo ** macarrão e automaticamente excluído 7 dias de inatividade.

## Exportar um arquivo

Você pode exportar o arquivo atual clicando em ** Exportar para disco ** no menu. Você pode apresentar por exportar o arquivo como Markdown simples, como HTML usando um modelo de barras de guia ou como um PDF.


# Sincronização

Synchronization is one of the biggest features of StackEdit. It enables you to synchronize any file in your workspace with other files stored in your **Google Drive**, your **Dropbox** and your **GitHub** accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow... The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.

There are two types of synchronization and they can complement each other:

- The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.
	> To start syncing your workspace, just sign in with Google in the menu.

- The file synchronization will keep one file of the workspace synced with one or multiple files in **Google Drive**, **Dropbox** or **GitHub**.
	> Before starting to sync files, you must link an account in the **Synchronize** sub-menu.

## Open a file

You can open a file from **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Open from**. Once opened in the workspace, any modification in the file will be automatically synced.

## Save a file

You can save any file of the workspace to **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.

## Synchronize a file

Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.

If you just have modified your file and you want to force syncing, click the **Synchronize now** button in the navigation bar.

> **Note:** The **Synchronize now** button is disabled if you have no file to synchronize.

## Manage file synchronization

Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking **File synchronization** in the **Synchronize** sub-menu. This allows you to list and remove synchronized locations that are linked to your file.


# Publication

Publishing in StackEdit makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **WordPress** and **Zendesk**. With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.

> Before starting to publish, you must link an account in the **Publish** sub-menu.

## Publish a File

You can publish your file by opening the **Publish** sub-menu and by clicking **Publish to**. For some locations, you can choose between the following formats:

- Markdown: publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).

## Update a publication

After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the **Publish now** button in the navigation bar.

> **Note:** The **Publish now** button is disabled if your file has not been published yet.

## Manage file publication

Since one file can be published to multiple locations, you can list and manage publish locations by clicking **File publication** in the **Publish** sub-menu. This allows you to list and remove publication locations that are linked to your file.


# Markdown extensions

StackEdit extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

` `  `
 seqüência de sereiaDiagrama 
Alice - >> Bob: Olá Bob, como vai você? 
Bob - >> João: E você John? 
Bob - x Alice: Estou bem, obrigado! 
Bob-x John: Estou bem, obrigado! 
Nota à direita de João: Bob pensa muito <br/> muito tempo, tanto <br/> que o texto <br/> não cabe em uma linha. Bob -> Alice: Checando com o João ... Alice-> João: Sim ... João, como você está? ` ` `





E isso produzirá um fluxograma:

` `  `
 Gráfico sereia LR 
A [retângulo Quadrado] - Texto do elo -> B ((Círculo)) 
A -> C (retângulo Redondo) 
B -> D {Losango} 
C -> D `  ` `

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTMzNjkwOTI1NF19
-->