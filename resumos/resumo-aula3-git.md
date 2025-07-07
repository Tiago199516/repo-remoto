# 🗒️ Resumo aula 3 Git - Branch

Branch é um "ramo" do projeto. É um galho criado para inseriri uma nova funcionalidade sem alterar o projeto original até que os testes sejam concluídos.
Conflitos de Merge ocorrem quando duas pessoas alteram a mesma linha de código em branchs diferentes e quando isso ocorre o Git retorna um erro mostrando as duas linhas de códigos para que o usuário decida qual linha deve ser mantida.

- Comandos para trabalhar com Branches.

| Comandos | Descrição |
|----------|-----------|
| git checkout -b "nome da branch"  | Cria uma nova branch do projeto |
| git checkout "nome da branch" | Retorna para a branch selecionada |
| echo "#nome do commit" > nome_do_arquivo.txt | Cria um novo commit |
| git branch -v | Lista o último commit de cada branch |
| git merge "nome da branch" | Unifica a branch ao main, alterando o main |
| git branch | Lista todas as branchs do sistema |
| git branch -d "nome da branch" | Exclui a branch |
| git fetch origin main | Baixa a um novo commit sem alterar o repositório local |
| git diff main origin/main | Mostra as diferenças entre duas branchs |
| git clone "link-do-repositório" --branch "nome da branch" --single-branch | Clona apenas uma branch específica do projeto |
| git stash | Arquiva a última modificação feita, impedindo-a de subir para o repositório original |
! git stash list | Lista todas as alterações arquivadas |
| git stash pop | Retira a alteração dos arquivos |
| git stash apply | Aplica a alteração que está arquivada |