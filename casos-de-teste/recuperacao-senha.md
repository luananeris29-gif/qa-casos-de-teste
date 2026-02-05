# Casos de Teste – Recuperação de Senha (BDD)

## Cenário 1 – Recuperar senha com e-mail válido

**Dado** que o usuário está na tela de login  
**E** possui um e-mail cadastrado  
**Quando** clicar em “Esqueci minha senha”  
**E** informar um e-mail válido  
**Então** o sistema deve enviar um link de recuperação de senha para o e-mail informado

---

## Cenário 2 – E-mail não cadastrado

**Dado** que o usuário está na tela de login  
**Quando** clicar em “Esqueci minha senha”  
**E** informar um e-mail não cadastrado  
**Então** o sistema deve exibir a mensagem “E-mail não encontrado”

---

## Cenário 3 – Campo vazio

**Dado** que o usuário está na tela de recuperação de senha  
**Quando** clicar em “Enviar” sem preencher o e-mail  
**Então** o sistema deve exibir mensagem de campo obrigatório
