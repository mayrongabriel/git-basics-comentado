# 06. Refatore nomes de arquivos

> Mude e remova os arquivos versionados.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)

---

## Comandos desta seção (3)

### 1. `git rm [arquivo]`

```bash
git rm [arquivo]
```

**O que faz:**

<!-- Remove um arquivo do Git e o exclui do computador. -->

**Quando usar / observação:**

<!-- Obs.: Revome definitivamente o arquivo do computador. -->

---

### 2. `git rm --cached [arquivo]`

```bash
git rm --cached [arquivo]
```

**O que faz:**

<!-- Remove um arquivo apenas do Git. -->

**Quando usar / observação:**

<!-- Obs.: O arquivo ainda fica salvo no computador. -->

---

### 3. `git mv [arquivo-original] [arquivo-renomeado]`

```bash
git mv [arquivo-original] [arquivo-renomeado]
```

**O que faz:**

<!-- Renomeia um arquivo no repositório, mantendo seu reconhecimento. -->

**Quando usar / observação:**

<!-- Obs.: O Git utiliza o comando do próprio windows para renomear e depois adiciona esse novo arquivo ao Git. Comandos:
mv [arquivo-original] [arquivo-renomeado] // comando do Windows.
git add [arquivo-renomeado] // comando do Git.
git rm [arquivo-original]  // comando do Git -->

---

## Checklist deste arquivo

- [x] 1. `git rm [arquivo]`
- [x] 2. `git rm --cached [arquivo]`
- [x] 3. `git mv [arquivo-original] [arquivo-renomeado]`

---

[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)
