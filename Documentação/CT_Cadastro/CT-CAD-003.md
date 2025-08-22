## CT-CAD-003: Tentativa de Cadastro informando código váldo mas expirado   

**Módulo/Funcionalidade:** Cadastro  
**Cenário de Teste:** Verificar comportamento do sistema ao tentar seguir cadastro com código expirado.  
**Pré-condições:** Ter conexão com a internet.  

### Passos de Execução:
1.  Acessar a URL: `https://www.medium.com`  
2.  Clicar em 'Get started'.  
3.  Clicar em 'Sign up with email'.  
4.  Fornecer email válido no campo 'Your email'.  
5.  Clicar em 'Create account'. 
6.  Preencher o campo com código expirado.  
7.  Clicar em 'Validate'.  

### Dados de Teste:
* **E-mail:** `bowoxi3670@evoxury.com`  
* **Código de Validação:** `793959`  

### Resultado Esperado:
* O sistema não deve permitir a continuação do cadastro.  
* O sistema deve informar o usuário que o código está expirado.  

### Status de Execução:
* **Data da Execução:** 22/08/2025  
* **Testador:** Pablo Costa  
* **Resultado:** PASSED  
* **Observações:** O sistema impediu o avanço de cadastro. O sistema informou a mensagem 'Expired code. Please generate a new code..'.  
