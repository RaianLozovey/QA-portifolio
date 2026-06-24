# Casos de Teste - Login

## CT001 - Login válido

### Passos

1. Acessar o SauceDemo.
2. Informar usuário standard_user.
3. Informar senha secreta.
4. Clicar em Login.

### Resultado Esperado

Sistema deve acessar a página de produtos.

---

## CT002 - Senha inválida

### Passos

1. Informar usuário válido.
2. Informar senha incorreta.
3. Clicar em Login.

### Resultado Esperado

Sistema deve exibir mensagem de erro.

---

## CT003 - Campos vazios

### Passos

1. Não preencher usuário.
2. Não preencher senha.
3. Clicar em Login.

### Resultado Esperado

Sistema deve solicitar preenchimento dos campos.
