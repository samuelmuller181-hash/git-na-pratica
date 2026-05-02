# git-na-pratica
principais comandos do git
```git init```                                 *Esse comando inicializa um repositório Git*

```git config user.name```                     *Mostra qual é o nome de usuário salvo*

```git config user.email```                     *Mostra qual é o email salvo*

```git cofig --global user.name "seu nome"```              *configura um novo nome (salva o nome na máquina)*  

```git config --global user.email "seu email"```            *configura um novo email (salva o email na máquina)*

```mkdir <nome da pasta>```                     *make directory - criar um diretório (pasta)*

```cd <nome da pasta>```                        *change directory - muda de diretório*

```cd ..```                                     *retorna a pasta anterior*

```git clone <link do repositorio>```           *puxa o repositório do github para a pasta local da máquina*

```git remote -v```                             *verificar qual o repositório remoto que ele vai puxar para o local*

```git remote add origin <link do repositório>```            *verificar da onde vai ser puxado as informações*

``` gir pull origin <nome da branch> (main ou master)```                      *puxar as informações do remoto o repositório local*

``` git add .```                                 *adiciona todas as alterações realizadas*

``` git add <nome do arquivo>```                 *adiciona um arquivo especifico*

```git commit -m "nome do commit"```             *salvar o nome da versão do projeto referente as alterações realizadas* 

``` git push -u origin (master ou main)```        *verificar de qual origen está puxando*

``` git push --set-upstream origin <nome da branch>```        *configurar qual origem vamos usar*

``` git push```                                    *enviar todas as alterações feitas no local para o remoto*
