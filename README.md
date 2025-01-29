# Dio | Resumo Git e Github

Repostitório para resumo do curso da [DIO](https://www.dio.me/) sobre Git e Github.

## 📕 Documentação
- [Documentação Git](https://git-scm.com/docs/git/pt_BR)
- [Documentação Github](https://docs.github.com/)
- [Documentação MarkDown](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

## 💻 Resumos
- Inicia o Repostitório local.
```
git init
```
- Remove o versionamento (a pasta) do git **se você der git init na pasta errada.**
```
rm -rf .git
```
- Retorna a situação do repositório Git.
```
git status
```
- Sobe todos os arquivos do Working Directory (Arquivos que foram modificados ou adicionados a pasta, e que não estejam vazios) para ficarem prontos para serem commitados (Adicionados ao repositório).
```
git add .
```
- Seleciona o arquivo especifico para entrar na área de espera para ser commitado (Adicionado ao repositório).
```
git add NOME DO ARQUIVO
```
- Restaura as alterações anteriores desde a ultima mudança.
```
git restore NOME DO ARQUIVO
```
- Mostra o histórico dos commits.
```
git log
```
- Realiza um commit levando  as mudanças o ambiente local pro repositório git.
```
git commit -m"MENSAGEM"
```
- Modifica a mensagem do ultimo commit feito.
```
git commit --amend -m"NOVA MENSAGEM"
```
- Abre o editor (Tambem serve para editar mensagens de commits). **Aperta a tecla i para editar e pra sair aperta "Esc" e digita ":wq"**
```
git commit --amend
```
- Faz o Commit voltar do repositório e ir para a área de preparação (Área verde onde se prepara para ser commitado).
```
git reset --soft HASH DO COMMIT
```
O HASH é o código em amarelo que aparece ao lado do commit quando você dá "git log"

- Faz o commit voltar seus arquivos como Untracked files (Arquivos que o git não conhece, e que não estão na área de preparação).
```
git reset --mixed HASH DO COMMIT ou git reset HASH DO COMMIT
```
- Faz o commit ser totalmente apagado do repositório e apaga **todos os arquivos do commit**.
```
git reset --hard HASH DO COMMIT
```
- Remove o arquivo especifico da área de preparação e vai para o "Arquivos Desconhecidos".
```
git reset NOME DO ARQUIVO
```
- Dá um histórico detalhado das alterações feitas.
```
git reflog
```
## 🤖 Comandos Github
- Deixa o repositório local vinculado com o repositório remoto.
```
git remote add origin URL DO REPOSITÓRIO GITHUB
```
- Clona apenas a branch que você desejar.
```
git clone URL DO REPOSITORIO --brach NOME DA BRANCH --single-branch
```
- Mostra todas as branchs e os últimos commits feitos nela.
```
git branch -v
```
- Transfere as alterações do repositório remoto para o repositório local.
```
git pull
```
- Transfere as alterações do repositório local para o remoto.
```
git push -u origin main
```
- Força o Git a aceitar a mesclagem dos históricos diferentes.
```
git pull origin main --allow-unrelated-histories
```
- Força a fazer um push na branch que você deseja.
```
git push origin +BRANCH QUE VOCÊ DESEJA ALTERAR
```
## ⭐ Comandos extras
- Entra na pasta selecionada.
```
cd PASTA SELECIONADA
```
- Cria uma pasta dentro da pasta selecionada.
```
mkdir NOME DA PASTA
```
- Cria arquivos vazios.
```
touch NOME DO ARQUIVO
```
