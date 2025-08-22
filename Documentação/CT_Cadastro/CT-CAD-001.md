## CT-CAD-001: Tentativa de Cadastro sem preencher o campo 'Your email'

**Módulo/Funcionalidade:**  Cadastro  
**Cenário de Teste:** Verificar o comportamento do sistema ao tentar realizar cadastro sem fornecer um email.  
**Pré-condições:** Ter conexão com a internet.  

### Passos de Execução:
1.  Acessar a URL: `https://www.medium.com`  
2.  Clicar em 'Get started'.  
3.  Clicar em 'Sign up with email'.  
4.  Não preencher o campo 'Your email'.  
5.  Clicar em 'Create account'.  

### Dados de Teste:
* **E-mail:** Em branco  

### Resultado Esperado:
* O sistema não deve permitir o usuário avançar no cadastro.  
* O sistema deve mostrar uma mensagem informando que o usuário deve informar um endereço de email.  

### Status de Execução:
* **Data da Execução:** 22/08/2025  
* **Testador:** Pablo Costa  
* **Resultado:** PASSED  
* **Observações:** O sistema não seguiu com o cadastro. O sistema mostrou a mensagem 'Please enter a valid email address.'  
