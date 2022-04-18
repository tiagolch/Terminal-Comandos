# Terminal-Comandos
Atalhos aprendidos no curso "LINUX I: CONHECENDO E UTILIZANDO O TERMINAL"


### Conhecer sobre algum comando
`man <comando>` ou `-help <comando>`

### Limpar Terminal:
- `clear` ou `ctrl + l`

### Navegar pelos diretórios

#### Listar diretórios e arquivos
- Listar:
  - `ls`
- Listar com detalhes:
  - `ls -l`
- Listar com detalhes e arquivos ocultos:
  -  `ls -la`
- Conhecer diretorio atual
  - `pwd`
- Criar diretório:
  -  `mkdir <nome_diretório>`
- Entrar no diretório:
  - `cd <diretório>`
- Voltar para diretório anterior:
  - `cd ..` (Cada ponto é um diretório anterior)
  - `cd ~` (Volta para home/<usuario>)
  - `cd /` (Volta para raiz)  
#### Apagar diretório e arquivos
  - `rmdir <diretório>`
  - `rm arquivo.txt`
  - `rm -r <diretório>` (Parametro -r necessário para apagar de forma recursiva caso diretório não esteja vazio)
  
### Arquivo de texto
- Criar arquivo:
  - `echo "Inserido texto no arquivo" > arquivo.txt`
  - `touch arquivo.txt`
- Concatenar a um arquivo existente:
  - `echo "Concatenando novo texto" >> arquivo.txt`

### Lendo arquivo no Terminal.
- CAT
  - `cat arquivo.txt`
  - `cat -n arquivo.txt` (Mostra o numero de linhas)
- VI
  - `vi arquivo.txt`
  
  
