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
- Remove o versionamento (a pasta) do git. **se você der git init na pasta errada**
```
rm -rf .git
```
- Retorna a situação do repositório Git.
```
git status
```
- Sobe todos os arquivos do Working Directory (Arquivos que foram modificados ou adicionados a pasta, e que não estejam vazios) para o repositório Git.
```
git add .
```
- Sobre o arquivo selecionado para o repositório git.
```
git add "NOME DO ARQUIVO"
```
- Restaura as alterações anteriores desde a ultima mudança.
```
git restore "NOME DO ARQUIVO"
```
- Mostra o histórico dos commits
```
git log
```