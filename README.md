<<<<<<< HEAD
=======
## Como acessar e colaborar neste repositório usando Git no terminal do VS Code

Siga os passos abaixo para clonar o repositório, criar uma nova branch, fazer alterações e colaborar enviando um Pull Request:

### 1. Clonar o repositório

Abra o terminal do VS Code e execute:

```bash
git clone https://github.com/sourcevincent/receita-secreta.git
cd receita-secreta
```

### 2. Crie uma nova branch para sua contribuição

Escolha um nome descritivo para sua branch, por exemplo: `feature/nova-receita` ou `fix/bug-login`:

```bash
git checkout -b nome-da-sua-branch
```

### 3. Faça suas alterações

Edite, adicione ou remova arquivos conforme necessário.

### 4. Adicione e faça commit das suas alterações

```bash
git add .
git commit -m "Descrição clara e objetiva da alteração"
```

### 5. Envie sua branch para o GitHub

```bash
git push origin nome-da-sua-branch
```

### 6. Abra um Pull Request

1. Acesse o repositório no GitHub ([https://github.com/sourcevincent/receita-secreta](https://github.com/sourcevincent/receita-secreta)).
2. Clique em **Compare & pull request** próximo à sua branch.
3. Preencha o título e a descrição, depois clique em **Create pull request**.

---

**Dicas:**
- Sempre sincronize sua branch principal antes de criar uma nova branch:

  ```bash
  git checkout main
  git pull origin main
  ```

- Para atualizar sua branch com as últimas alterações da `main`:

  ```bash
  git checkout nome-da-sua-branch
  git merge main
  ```

Se precisar de ajuda, consulte a [documentação oficial do Git](https://git-scm.com/doc) ou abra uma issue neste repositório!
>>>>>>> 1ff087e52667dc67bbb349c47f559b07e574fac4
