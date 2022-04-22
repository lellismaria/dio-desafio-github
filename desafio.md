# Desafio sobre Github - DIO
Repositório criado para desafio Github na DIO

## Passo a passo
1. Criar um repositório no Github
2. Criar um arquivo chamado readme.md 
3. Clonar o repositório em uma pasta local na sua máquina
    - Pegar o https na opção "Clone" do seu repositório
    - Abrir o Git Bash na pasta local que você criou na sua máquina
    - Clonar o repositório: `git clone hhttps://github.com/lellismaria/dio-desafio-github`
4. Subir arquivo no Github
    - Criar um arquivo qualquer dentro da pasta clonada no PC
    - Ver o status do repositório local: `git status`. O novo arquivo será apontando como disponível para commit.
    - Adicionar o novo arquivo para iniciar o commit: `git add .`
    - Fazer commit do novo arquivo: `git commit -m "Subida de arquivo no Github"`
    - Fazer push do commit para, de fato, o novo arquivo subir para o Gitub: `git push origin main`
    - A repetição da verificação de status do repositório local a cada comando executado, mostrará a situação do repositório. `git status`