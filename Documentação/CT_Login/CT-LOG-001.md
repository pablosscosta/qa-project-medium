## CT-LOG-001: Tentativa de Cadastro informando código váldo mas expirado   

**Módulo/Funcionalidade:** Login  
**Cenário de Teste:** Verificar comportamento do sistema ao tentar login sem informar o email.  
**Pré-condições:** Ter conexão com a internet.  

### Passos de Execução:
1.  Acessar a URL: `https://www.medium.com`  
2.  Clicar em 'Sign in'.  
3.  Clicar em 'Sign up with email'.  
4.  Não preencher o campo 'Your email'.  
5.  Clicar em 'Continue'.  

### Dados de Teste:
* **E-mail:** Em branco 

### Resultado Esperado:
* O sistema não deve permitir o login.  
* O sistema deve informar o usuário que o usuário deve informar um endereço de e-mail.  

### Status de Execução:
* **Data da Execução:** 22/08/2025  
* **Testador:** Pablo Costa  
* **Resultado:** PASSED  
* **Observações:** O sistema impediu o avanço do login. O sistema informou a mensagem 'Please enter a valid email address.'.  
