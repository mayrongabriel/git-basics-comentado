# 11. Sincronize mudanças

> Registre um repositório remoto e troque o histórico de versão.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)

---

## Comandos desta seção (4)

### 1. `git fetch [nome-remoto]`

```bash
git fetch [nome-remoto]
```

**O que faz:**

<!-- Baixa todos os objetos remotos do git. -->

**Quando usar / observação:**

<!-- Obs.: Não faz o merge automaticamente. -->

---

### 2. `git merge [nome-remoto]/[branch]`

```bash
git merge [nome-remoto]/[branch]
```

**O que faz:**

<!-- Traz as modificações de outra branch para a branch local atual. -->

**Quando usar / observação:**

<!-- Obs.: As modificações só são aplicadas na branch local selecionada. -->

---

### 3. `git push [alias] [branch]`

```bash
git push [alias] [branch]
```

**O que faz:**

<!-- Envia para um diretório remoto todos os commits no diretório local que ainda não foram enviados. -->

**Quando usar / observação:**

<!-- Obs.: Modificações que não foram commitadas não serão enviadas. -->

---

### 4. `git pull`

```bash
git pull
```

**O que faz:**

<!-- Traz todas as modificações feitas no diretório remoto para o diretório local. -->

**Quando usar / observação:**

<!-- É uma boa prática atualizar o diretório local antes de começar a fazer modificações no projeto. -->

---

## Checklist deste arquivo

- [x] 1. `git fetch [nome-remoto]`
- [x] 2. `git merge [nome-remoto]/[branch]`
- [x] 3. `git push [alias] [branch]`
- [x] 4. `git pull`

---

[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)
