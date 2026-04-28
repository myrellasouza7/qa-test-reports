# qa-test-reports
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

### Observação: Não foi possível criar username e password no devido site, pois não tem a opção. 

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
Houveram falhas na descrição da mensagem de erro de acordo com a forma de preenchimento.
Formas diferentes de preenchimento apresentaram a mesmaa mensagem de erro, como se apenas o username estivesse inválido, independente do campo senha estar vazio, independente de ambos os campos estarem vazios. Independente de apenas o campo username estar preenchido. 

---

## 📸 Evidências

### Login válido
Mensagem de Erro:![Login válido](https://raw.githubusercontent.com/myrellasouza7/qa-test-reports/refs/heads/main/Captura%20de%20tela%202026-04-28%20114618.png)
