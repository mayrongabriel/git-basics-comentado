# 09. Revise o histórico

> Navegue e inspecione a evolução dos arquivos do projeto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)

---

## Comandos desta seção (4)

### 1. `git log`

```bash
git log
```

**O que faz:**

<!-- Mostra o histórico de commit daquele branch. -->

**Quando usar / observação:**

<!-- Para verificar os commits feitos. -->

---

### 2. `git log --follow [arquivo]`

```bash
git log --follow [arquivo]
```

**O que faz:**

<!-- Mostra o histórico de commit de um arquivo isolado da branch. -->

**Quando usar / observação:**

<!-- Para verificar os commits feitos em um arquivo apenas. -->

---

### 3. `git diff [primeiro-branch]...[segundo-branch]`

```bash
git diff [primeiro-branch]...[segundo-branch]
```

**O que faz:**

<!-- Mostra as diferenças que aconteceram na segunda branch, a partir da primeira. -->

**Quando usar / observação:**

<!-- Quando for preciso comparar uma branch com outra.
Obs.: O resultado será as diferenças na segunda branch do comando, apenas. -->

---

### 4. `git show [commit]`

```bash
git show [commit]
```

**O que faz:**

<!-- Mostra as modificações feitas em um commit específico. -->

**Quando usar / observação:**

<!-- Quando for preciso analisar mudanças em apenas um commit. -->

---

## Checklist deste arquivo

- [x] 1. `git log`
- [x] 2. `git log --follow [arquivo]`
- [x] 3. `git diff [primeiro-branch]...[segundo-branch]`
- [x] 4. `git show [commit]`

---

[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)
