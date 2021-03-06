# Introdução ao Git :computer:

### Primeiramente precisamos entender o que é o Git:

-Git e um sistema de versionamento de código distribuído , criado em 2005 pelo Linus Torvalds, que ajuda a monitorar e criar diferentes versões do nosso código, dentro da nossa maquina.



### Navegação via command line interface e instalação :blue_book:

##### Command-line interface(CLI): 

- É um meio de interagir com um programa de computador, onde o utilizador emite comandos para o programa sob formas sucessivas linhas de texto.



### Comandos Básicos de Navegação:

- **Dir** -Primeiro comando para poder listar e entender em qual local estamos e o comando "**Dir**", que ira trazer uma lista de diretórios contidos na pasta onde estamos situados.	No Linux o comando e diferente ao invés de usar o "**Dir**" utiliza-se o comando "**LS**"
- **Comando CD** - este comando possibilita que a gente navegue entre as pastas e ele e igual para todos os sistemas operacionais.
- **Comando Echo** - É utilizado para exibir uma mensagem na tela para a pessoa usuária.
- **CLS** - Comando utilizado para fazer a limpeza do terminal para deixar a tela mais limpa. no Linux utiliza o "**clear**".
- **mkdir** - Comando utilizado para fazer a criação de uma pasta. O comando no Linux e igual.
- **Del** - Comando para deletar arquivos de uma pasta, não serve para deletar requisitórios.
- **rmdir** - Comando para deletar requisitórios. No Linux para deletar arquivo e requisitórios utiliza-se "**RM-RF**" .

Um atalho para completar os comandos e o "**TAB**" que ajuda a completar o nome das pastas.



### Flags

- **O que são Flags?**: Todos os comandos que formos usar eles possuem variâncias, eles possuem **Flags** que são complementos que passamos para estes comandos, que **acrescentam**, **modificam** ou **formatam** a forma que estes comandos são devolvidos para a gente.



### Entendendo como funciona o Git :man_technologist:

**SHA1** - A sigla SHA significa **Secure Hash Algorithm (Algoritimo de Hash Seguro)**, é um conjunto de funções hash criptografadas projetadas pela **NSA** (Agencia de Segurança Nacional dos EUA).

A encriptação gera conjunto de caracteres identificador de 40 digitos, é um conjunto unico que serve como identificação. É a forma curta de representar um arquivo.





### Objetos Internos do Git :black_circle:



- **Blobs**
- **Trees**
- **Commits**



**Blobs** - Cada arquivo no Git e armazenado um objeto Blob, por exemplo, a partir do conteúdo do arquivo logo.png ele gera um hash que será armazenado em algum lugar endereçável. Serve para armazenar arquivos binários, dentro da blob conta metadados.

**Exemplo**:

![Introdução a Git](data:image/png;base64,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) 



- Todo Blob contem o tipo do objeto
- tamanho do arquivo
- \0
- Conteúdo seja Texto ou binário



**Trees** - É um diretório ( e seus arquivos subdiretórios) em seu sistema de arquivos que esta associado a um repositório. Esta cheio de arquivos que você edita, onde você adiciona novos arquivos, e remove arquivos desnecessários. Aponta para o **Blob** ( Que tem um SHA1).

**A Tree também guarda o nome do arquivo**.

**Estrutura básica de Tree:**

![O Livro da Comunidade Git. Um recurso Git aberto combinados juntos pela  comunidade inteira. - PDF Free Download](data:image/png;base64,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)

**Outro exemplo de estrutura basica de Tree**:



**![Objetos do Git · git](http://git-scm.com/figures/18333fig0901-tn.png)**



- **Tree apontam para blobs ou para outras Trees**.





**Commit** - É o objeto que vai junto de tudo, que vai dar sentido para a alteração que voce esta fazendo. O commit aponta para uma Tree, o commit aponta para um parente ou seja ele aponta para o ultimo commit realizado antes dele, o commit aponta para o autor, o commit aponta para uma mensagem tambem. O commit tem tambem um **timestamp** que é um carimbo de tempo, então este objeto recebe uma data, um horário de quando foi criado.

Os commits possuem tambem um SHA1.

**O SHA1 desse commit e o hash de toda essa informação**.



**Estrutura de um commit**:



![Git #3: Tags, Branches e comando remotos | Café com Leite](https://edermfl.files.wordpress.com/2016/01/git_commit.png?w=640)





