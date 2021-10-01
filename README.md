
GIT/GIT HUB - BOAS PRÁTICAS

Versionamento de código : Servidor para enviar/baixar alterações

- Criação de um repositório : git init 
- Criação de pastas e navegação entre elas pelo Git Bash : mkdir / cd
- Alterações e commits comentados: git status / git add / git commit -m ""
- Como ignorar um arquivo com .gitignore 
- Acompanhamento através do git log e suas variações
- Criar um repositório de alterações com git init --bare
- Criação de repositórios remotos para push/pull : origem - remoto - destino
- git remote -v <- verificação de chegada/saida
- git clone [endereço] <- copia de um repositório
- git push local master - joga arquivos da pasta origem para o remoto
  git pull local master - puxa arquivos da pasta remoto para destino

BOAS PRÁTICAS : NÃO COMMITAR CÓDIGO QUE NÃO-FUNCIONAL

Definições
- HEAD : estado atual do código
- Working tree : Local onde os arquivos estão sendo armazenados e editados
- index : local onde armazena o que será commitado
