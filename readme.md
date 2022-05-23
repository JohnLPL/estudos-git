# Estudos git

## O que é?

Git é um sistema de controle de versão para o registro de alterações de um programa em desenvolvimento, afim de se ter organização e segurança do armazenamento de dados para que assim possa alterar e se possivel retornar ao código anterior sem problemas.

## Como surgiu?

O Git foi criado pelo engenheiro de software Linus Torvalds, conhecido por ter desenvolvido, também, o núcleo Linux, feito para atender a uma necessidade que estava em aberto por conta do fim de contrato com uma empresa tercerizada que estava responsável por este tipo de serviço conhecida como BitKeeper.

## Comandos básicos

#### Inicializa o repositório
```
git init
```

#### Verifica o status do repositório
```
git status
```

#### Adiciona um arquivo ao stage
```
git add nome-arquivo.txt
```

#### Adiciona vários arquivos com a mesma extensão ao stage
```
git add *.txt
```

#### Adiciona vários arquivos de uma vez ao stage
```
git add .
git add -A
```

#### Exibe a diferença da mudança
```
git diff
```

#### Cria uma foto das alterações realizadas até o momento
```
git commit -m "Sua mensagem"
```

#### Adiciona ao stage e cria uma foto das alterações realizadas até o momento
```
git commit -am "Sua mensagem"
```

#### Limpar o terminal
```
cls # Apenas no cmd.

clear

ctrl + l
```

Outros, dono, grupo.
Other, owner, group.
Read, write, execute. # rwx

# Referências

1. [Canal William Justen](https://www.youtube.com/watch?v=IBClN6VpJDw&list=PLlAbYrWSYTiPA2iEiQ2PF_A9j__C4hi0A)
2. [Artigo sobre o básico do Git](https://rogerdudler.github.io/git-guide/index.pt_BR.html)
3. [Slide sobre o básico do Git](https://speakerdeck.com/juunegreiros/introducao-ao-git)