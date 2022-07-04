### Alguns Comandos Básicos Para o Git/Github e Prompt :computer:

- Para saber quais arquivos tem no computador/ usuário principal pelo prompt de comando usar o comando **dir**.

- Para ir para base do diretório usar o comando **cd /** .

- Para entrar na pasta do Windows é só usar o comando **cd Windows**.

- Para voltar pro diretório anterior "no caso atual a base do diretório" basta usar o **cd..**. 

- Para limpar o prompt de comando basta usar o comando **cls** ou no GitBash **ctrl L**.

- Se aperta o **tab** no com apenas uma letra de uma pasta existente o **tab** completa o nome da pasta.

- Para criar uma pasta pelo prompt de comando usa-se o comando **mkdir**.

- Comando **echo** printa de volta no terminal uma frase ou texto. para criar um arquivo pelo prompt usasse o **echo 'frase ou texto desejado' ** 

- Nome do arquivo que quero **criar.txt (para formatos txt)**.

- Para deletar algum arquivo ou todos os arquivos de uma pasta usar o comando **del 'nome da pasta'**.

- Para remover o depositório (pasta) com todos os arquivos que tem dentro usar o comando **rmdir 'nome da pasta' /S /Q**.

- Serve para codificar os arquivos usando o comando **openssl sha1** nome do arquivo.txt.

- **init** cria um novo repositório do Git. Ele também pode ser usado para converte projetos existentes e não versionado em um repositório do Git ou inicializar um novo repositório vazio.

  ### Para criar a senha ssh comandos.

- ** ssh-kaygen -t ed25519 -c 'email' **.

- ** ssh-keygen -N 'senha' **.

- Depois disso você vai pro diretório que se encontra a chave, logo após usa o comando **ls** para lista as chaves que tem nesse diretório.

- Logo em seguida pega essa chave e coloca no site do github e então ativa o **agent pid 1612** >>depois>>  **ssh-add ** nome dado na senha criptográfica " e colocar a senha que você preferir".

  ### Fazendo um Commit.

-  (no primeiro acesso fazendo um commit você precisa dessas configurações).

- **git config --global** (pode ser global ou exclusiva para o repositório)  **user.email "email"** 

- **git config --global user.name** "Nome escolhido por você"

- **git add** adiciona todas as alterações que você fez nos arquivos para que esses arquivos possam ser colocados em Staged.

- Agora usando o comando **git commit -m "Seu comentário"**

- Git romote estabelece uma conexão entre seu repositório local e um repositório remoto com o comando **git remote add < nomecurto > < url >**  

  ### Conflitos no Github

- Quando você precisa baixar as mudanças criadas por outros membros do seu projeto colaborativo, você precisa do comando **git fetch**.

- Conflitos de arquivos que está no Github você deve puxar o arquivo que está salvo no repositório do Github com o comando **git pull origin master**.

- então ajeitar as linhas que estão em conflito e mandar novamente para o repositório do Github.
