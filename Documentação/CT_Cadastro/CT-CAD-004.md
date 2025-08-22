## CT-CAD-004: Tentativa de Cadastro deixando em branco o campo 'Your full name'.   

**Módulo/Funcionalidade:** Cadastro  
**Cenário de Teste:** Verificar comportamento do sistema ao tentar seguir cadastro sem preencher o nome completo.  
**Pré-condições:** Ter conexão com a internet.  

### Passos de Execução:
1.  Acessar a URL: `https://www.medium.com`  
2.  Clicar em 'Get started'.  
3.  Clicar em 'Sign up with email'.  
4.  Fornecer email válido no campo 'Your email'.  
5.  Clicar em 'Create account'. 
6.  Preencher o campo com código válido.  
7.  Clicar em 'Validate'.  
8.  Não preencher campo 'Your full name'.  
9.  Clicar em 'Create account'.  

### Dados de Teste:
* **E-mail:** `bowoxi3670@evoxury.com`  
* **Full name:** Em branco 

### Resultado Esperado:
* O sistema não deve permitir a continuação do cadastro.  
* O sistema deve informar ao usuário que é necessário fornecer um nome.  

### Status de Execução:
* **Data da Execução:** 22/08/2025  
* **Testador:** Pablo Costa  
* **Resultado:** PASSED  
* **Observações:** O sistema não permitiu o avanço de cadastro e mostrou a mensagem 'Please enter your name'.  
