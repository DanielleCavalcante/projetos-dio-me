# DIO | RESUMOS Git e GitHub

Repositório para armazenar resumos sobre Git e Github do curso Versionamento de Código com Git E Github [Digital Innovation One](https://www.dio.me/).

## 🗒️ Documentação

- [Documentação GitHub](https://docs.github.com/pt)
- [Documentação Git](https://git-scm.com/doc)

## 📝 Resumo das aulas

```
mkdir -> criar nova pasta
```
```
git init -> iniciar o diretório
```
```
cd + diretório -> acessar diretório
```
```
cd .. -> voltar
```
```
git clone [URL] nome-diretório-local (opcional)-> clonar um repositório
```
```
git status -> verificar status do diretório
```
```
cat config -> mostrar informações de configurações
```
```
git remote -v -> verificar diretório remoto
```
```
git remote add origin [URL] -> vincular repositório remoto ao local
```
```
git commit --amend -m "nova mensagem" -> alterar mensagem do último 
```
```
rm -rf -> remover versionamento do diretório e todo o conteúdo
```
```
git restore -> restaurar última modificação salva (apaga a nova)
```
```
touch -> criar arquivo de texto
```
```
git reset nome-arquivo.extensao -> remover arquivo
```
```
git add . -> adiciona todas as novas alterações
```
```
git push -u origin main -> envia as alterações do repositório local para o remoto
```
```
git pull  -> puxar informações do remoto para o local
```
## Branch (ramo) 
- É como um universo paralelo do seu projeto, onde você pode testar novas ideias sem prejudicar o projeto oficial.

### 🛣️ Comandos em Branch

```
git checkout -b teste -> trocar branch que estamos para essa "teste"
```
```
echo "#commit-3-branch-teste" > commit-3-branch-teste.txt -> commit na branch
```
```
git branch -v -> mostra o último commit de cada branch
```
```
git merge teste -> mescla a branch teste com a branch principal main
```
```
git branch -> mostra as branchs no repositório
```
```
git branch -d teste -> exclui a branch teste (nome)
```
