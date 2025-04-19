# Desafio de Projeto sobre Git/Github

Bem- Vindo(a):
Vamos criar um do primeiro projeto no Git/Github.

*Após a instalação do Git*.

Para interligar o Git ao GitHub, você precisa interligar o Git ao Github posteriormente, você deve criar um repositório no GitHub. Em seguida, você deve clonar o repositório em sua máquina local usando o comando *git clone <URL do repositório>* 

Depois de fazer as alterações necessárias em seus arquivos, caso seja necessario. Você deve adicionar os arquivos ao índice usando o comando *git add <nome do arquivo>* e, em seguida, fazer um commit usando o comando *git commit -m "mensagem"* (A mensagem seria pertinente ao seu projeto). 

Finalmente, você deve enviar as alterações para o repositório remoto usando o comando *git push*.

**Comandos Adicionais do Git:**

**git status**: Este comando é seu aliado para verificar o estado atual do seu repositório local. Ele informa:
    * Quais arquivos foram modificados e ainda não foram adicionados à área de staging (índice).
    * Quais arquivos estão na área de staging e estão prontos para serem incluídos no próximo commit.
    * Qual branch você está atualmente.
    * Se há commits à frente ou atrás do repositório remoto.

    Exemplo de saída:
    ```
    On branch main
    Your branch is up to date with 'origin/main'.

    Changes not staged for commit:
      (use "git add <file>..." to update what will be committed)
      (use "git restore <file>..." to discard changes in working directory)
            modified:   meu_arquivo.txt

    Untracked files:
      (use "git add <file>..." to include in what will be committed)
            novo_arquivo.js

    no changes added to commit (use "git add" and/or "git commit -a")
    ```

**`git pull`**: Este comando é usado para buscar as últimas alterações do repositório remoto e integrá-las ao seu branch local atual. É como dizer: "Ei, GitHub, veja se houve alguma mudança desde a última vez que olhei e traga essas mudanças para o meu computador."

    **Uso:**

    ```bash
    git pull origin main
    ```

    * `origin`: Geralmente é o nome padrão dado ao seu repositório remoto no GitHub.
    * `main`: É o nome do branch remoto do qual você quer puxar as atualizações (pode ser `master` ou outro nome).

* **`git push`**: Já vimos este comando antes, mas vale reforçar. Depois de fazer seus commits localmente, `git push` é o comando que envia esses commits para o repositório remoto no GitHub, tornando suas alterações visíveis para outros colaboradores e armazenando-as na nuvem.

    **Uso:**

    ```bash
    git push origin main
    ```

    * `origin`: Novamente, o nome padrão do seu repositório remoto.
    * `main`: O nome do branch local que você quer enviar para o branch remoto correspondente.

**Fluxo de Trabalho Típico:**

Em resumo, um fluxo de trabalho comum ao usar Git e GitHub envolve os seguintes passos:

1.  **`git pull origin main`**: Para garantir que você esteja trabalhando com a versão mais recente do projeto.
2.  Faça suas alterações nos arquivos locais.
3.  **`git add <arquivos_modificados>`**: Adicione as alterações à área de staging.
4.  **`git commit -m "Sua mensagem descritiva"`**: Salve suas alterações localmente com uma mensagem clara.
5.  **`git push origin main`**: Envie seus commits para o repositório remoto no GitHub.


---------Em anotações você encontrará os comandos básicos para utilizar o Git.-------------------------

## Links Úteis
[Como Instalar o Git](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git)

[Sintaxe Básica Markdown.](https://www.markdownguide.org/getting-started/)

[Como colocar seu repositório local no GitHub](https://docs.github.com/pt/desktop/adding-and-cloning-repositories/adding-a-repository-from-your-local-computer-to-github-desktop)
