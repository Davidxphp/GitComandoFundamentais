# GitComandoFundamentais
Informações referente ao resumo do Code Education - para meu aprendizado - divulgar conhecimento

### Configurando usuário no git

- git config --global user.name "Seu Nome"
- git config --global user.email "Seu E-mail"

### Iniciando uma pasta local para controle de versão do git

- git init

### verficar se existe arquivos incluidos ou alterados na pasta

- git status

### adionar arquivos incluidos ou alterados para controle do git

- git add .  (todos arquivos)
- git add nome_do_arquivos (adiciona um arquivo)

### Salvar os arquivos alterados ou incluidos na pasta controlada pelo git e informar uma mensagem com notivo

- git commit -m "arquivos alterados em algum lugar para atender uma demanda etc"

### Desfazendo commits - com revert - cria um novo commit

-  git log (Este comando exibi o histórico de commits, com seu HASH ou código de indentifica)

-  git revert seu HAASH ou código

### Criar um repositório remoto 

- criar uma conta
- criar repositório
- linkar o repositório local com remoto conforme segue:

### Linkar repositório local com remoto 

- git remote add origin https://github.com/nome_usuário/nome_repositorio.git

### Enviar repositório local para remoto

- git push -u origin master

### Enviar repositório remoto para local

- git pull origin master

### Trabalhando com outras Branch (Ramificação) além da Master

##### Criar uma branch

- git branch nome_local

##### Trocar para uma branch

- git switch nome_local

### Unificando (merge) Branch e revendo conflitos

- git fetch origin

- git checkout -b branch_local origin/branch_remota

- git merge master

- Obs.: se houver conflito, corrigir, e depois seguir com comandos:

- git add  nome_arquivo

- git commit -m "Resolvendo conflito"

- git checkout master

- git merge branch_nova

- git push origin master

- git log


