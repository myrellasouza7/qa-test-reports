# qa-login-test-report
Testes realizados na funcionalidade de login com foco em validação de autenticação e comportamento do sistema.
## Cenário de Teste
Validação da funcionalidade de login em diferentes condições de entrada

---

## Ambiente
- Navegador: Chrome  
- Sistema operacional: Windows  

---

## Cenários testados 

---

### Observação: Não foi possível criar username e password no sistema testado, pois não tem a opção. 

---

### Senha incorreta
- username correto + password errada  
- Resultado esperado: mensagem de erro  
- Resultado atual: Mensagem de erro
- Erro: Your username is invalid

---

### Usuário incorreto
- username + password qualquer  
- Resultado esperado: mensagem de erro  
- Erro: Your username is invalid

---

### Campos vazios
- Nenhum campo preenchido  
- Resultado esperado: Aviso para preenchimento
- Resultado atual: Mensagem de erro
- Erro: Your username is invalid

---

## Análise
Descrever comportamento do sistema durante os testes

---

## Conclusão
Resumo geral da funcionalidade de login
Durante os testes, foi identificado que o sistema não diferencia corretamente os cenários diferentes de erro na funcionalidade.
Independente da forma de preenchimento (campos vazios, username + password incorretos, username sem password, username vazio + password), o sistema sempre retorna a mesma mensagem:
"Your username is invalid"
Podendo impactar negativamente na experiência do usuário, dificultando a identificação do real problema para sua devida correção.

---

## 📸 Evidências

### Login inválido
Mensagem de Erro:![Login válido](https://raw.githubusercontent.com/myrellasouza7/qa-test-reports/refs/heads/main/Captura%20de%20tela%202026-04-28%20114618.png)
