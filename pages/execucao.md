[voltar](../README.md)

# Hands On

## Criação de projeto distribuido

Primeiramente para ques os times possam trabalhar de forma remotas, em tarefas paralelas; é necessário um projeto comum aos times.

Então, o time deverá criar um projeto no GitHub e cada equipe deverá obter uma cópia do projeto remoto, ou seja cada equipe deverá obter sua cópia do repositório remoto do projeto.

## Criando um projeto no GitHub

> Esta etapa iremos realizar de forma síncrona, ou seja, iremos realizar juntos após a conclusão de criação de usuários no GitHub.

### Inicialização de Projeto

Nest ponto voce tem um projeto vazio no repositório remoto, como ele está vazio, precisaremos criar arquivos nele para que possamos cloná-lo nos computadores dos membros da equipe.

1. Na área de destaque `Quick Setup`, clique no link README para criar um arquivo de instruções no projeto.
2. Na nova janela que se abriu, clique no botão `Commit new file`, este comnado irá criar a primeira versão do projeto, um diretório com um arquivo `README.md` em seu interior.
3. Clique no botão `<> Code` e copie o link de seu projeto remoto.

#### Clone o projeto localmente

Agora que voce ja tem o link do repositório; siga os passos abaixo:
1. Acesse o shell do Ubuntu, selecione uma pasta de sua preferencia;
2. Realize o clone com o comando abaixo:

```shell
git clone link_do_seu_repositorio
cd nome_do_seu_repositorio
git remote -v
```


