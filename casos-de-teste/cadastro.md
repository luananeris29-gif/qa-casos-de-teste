# Caso de Teste – Cadastro

## Cenário – Cadastro com e-mail inválido

**Dado** que o usuário está na tela de cadastro  
**Quando** inserir um e-mail inválido (sem "@")  
**E** clicar em “Cadastrar”  
**Então** o sistema deve exibir uma mensagem de erro informando que o e-mail é inválido
