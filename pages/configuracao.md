
[voltar](../README.md)

### Utilizando o Git

Primeiramente iremos realizar a instalação do Git no Ubuntu.

#### Instalando o Git

Siga os passos abaixo para fazer a instalação:

1. Atualizar os pacotes de instalação:

```shell
sudo apt update
```

2. Atualizar os pacotes de instalação:

```shell
sudo apt install git
```

3. Verificar a versão instalada do Git:

```shell
git --version
```
#### Configurando o GitHub

Agora voce deverá criar uma conta no [github.com](https://github.com/).

> Este passo não iremos descrever as instruções pois envolve acesso ao seu e-mail pessoal ou institucional e alguns passos de validação, então ficará sob sua responsabilidade criar a conta, mas o Esdras e Thiago estarão em auxilio à voces.

#### Configurando sua conta GitHub

Com a conta devidamente criada e verificada; voce pode voltar para a configuração e incluir suas credenciais para poder enviar seu código para a nuvem quando concluir
 suas atividades.

4. Adicione suas credenciais do GitHub
```shell
git config --global user.name "Seu Name"
git config --global user.email "seuemail@dominio.com"
```
5. Verifique suas credenciais no arquivo de configuração.

```shell
nano ~/.gitconfig
```








