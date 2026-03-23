# Teste Funcional - Sistema de Login

## Objetivo
Validar o funcionamento da funcionalidade de login do sistema.

## Casos de Teste

### CT01 - Login com dados válidos
- Entrada: usuário e senha corretos
- Resultado esperado: acesso permitido ao sistema

### CT02 - Senha incorreta
- Entrada: usuário válido e senha inválida
- Resultado esperado: mensagem de erro informando senha inválida

### CT03 - Usuário inexistente
- Entrada: usuário inválido
- Resultado esperado: mensagem de usuário não encontrado

### CT04 - Campos vazios
- Entrada: campos sem preenchimento
- Resultado esperado: alerta solicitando preenchimento obrigatório
