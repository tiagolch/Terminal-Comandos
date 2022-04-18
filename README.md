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
#### Apagar diretórios e arquivos
  - `rmdir <diretório>`
  - `rm arquivo.txt`
  - `rm -r <diretório>` (Parametro -r necessário para apagar de forma recursiva caso diretório não esteja vazio)
#### Manipular diretórios e arquivos
  - Copiar:    
    - `cp <arquivo> <arquivo2>`
    - `cp <arquivo> <diretorio/arquivo>`
    - `cp -r <diretorio> <diretorio2>` (parametro -r necessário em cso de diretório)
  - Mover:
    - `mv <arquivo> <diretorio/>`
    - `mv <arquivo> <diretorio/arquivo2>` (Movendo e trocando nome do arquivo)
#### Compactar diretórios
  - ZIP (compactando)
    - `zip -r <nomeDiretorioZipado.zip> <diretorio>`
  - UNZIP (descompactando)
    - `unzip <nomeDiretorioZipado.zip>`
  - TAR (compactando)
    - `tar -cz <diretorio> > <nomeDiretorioZipado.tar.gz>`
    - `tar -czf <nomeDiretorioZipado.tar.gz> <diretorio>`
  - TAR (descompactando)
    - `tar -xz < <nomeDiretorioZipado.tar.gz>`
    - `tar - xzf <nomeDiretorioZipado.tar.gz>`
  
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
- HEAD
  - `head -n <n_de_linhas> arquivo.txt` (Apresenta cabeçalho do texto e paramtro n para mostrar o numero de linhas)
- TAIL
  - `tail -n <n_de_linhas> arquivo.txt` (Apresenta rodapé do texto e paramtro n para mostrar o numero de linhas)
- LESS
  - ` less arquivo.txt` (Navega pelo texto)
- VI
  - `vi arquivo.txt` (Abre o arquivo no terminal onde consegue adicionar ou remover clicando em "i" no teclado. Para sair da interação basta clicar em "esc". Para fechar ":wq" onde o "w" Salva e o "q" sai)
    - `i` Interage com o arquivo na posição atual.
    - `a` Adiciona na posição posterior
    - `Shift + A` Adiciona no fim da Linha.
    - `x` Remove caracteres (n * x remove *n caracteres)
    - `dd` Remove uma linha (n * dd remove *n linhas)
    - `Shift + g` Ir para ultima linha do texto.
    - `n``Shift + g` Para ir a uma linha especifica digita-se o numero e depois shift + g.
    - `Shift + $` Para ir para o final da linha.
    - `0` Para o inicio da linha
    - `/<palavraASerBuscada>` Quando precisa buscar no texto e depois `n` para ir para a proxima ocorrencia e `Shift + n` para voltar a ocorrencia anterior.
    - `yy` Para copiar a linha
    - `p` Para colar o que foi copiado.
  
  
  
