# task01-grupo04
Repositório para a task01 

# Documentação do Git

### Funcionamento, sintaxe e aplicação do comando git rebase:
 O git rebase é um comando do Git que permite mover ou reaplicar commits de uma ramificação para outra, criando um histórico linear e limpo. Ele funciona aplicando os commits de uma ramificação (a "ramificação de origem") sobre a ramificação de destino, como se os commits tivessem sido feitos diretamente na ramificação de destino. 

---

 ### `git cherry-pick`

- **Funcionamento:** Aplica commits específicos de outro branch no branch atual.
- **Sintaxe:** `git cherry-pick <hash-do-commit>`
- **Aplicação:** Usado para trazer mudanças pontuais sem fazer merge completo.

---

### `git revert`

- **Funcionamento:** Cria um novo commit que desfaz as mudanças de um commit anterior.
- **Sintaxe:** `git revert <hash-do-commit>`
- **Aplicação:** Usado para desfazer commits de forma segura, preservando o histórico.

---

### `git squash`

- **Funcionamento:** Combina vários commits em um só.
- **Sintaxe:** Durante rebase: `git rebase -i <hash-anterior>`
- **Aplicação:** Usado para limpar o histórico antes de mesclar branches.