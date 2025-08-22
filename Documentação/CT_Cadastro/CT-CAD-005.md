## CT-CAD-005: Tentativa de Cadastro sem selecionar três ou mais interesses.   

**Módulo/Funcionalidade:** Cadastro  
**Cenário de Teste:** Verificar comportamento do sistema ao tentar seguir cadastro sem selecionar três ou mais interesses.  
**Pré-condições:** Ter conexão com a internet.  

### Passos de Execução:
1.  Acessar a URL: `https://www.medium.com`  
2.  Clicar em 'Get started'.  
3.  Clicar em 'Sign up with email'.  
4.  Fornecer email válido no campo 'Your email'.  
5.  Clicar em 'Create account'. 
6.  Preencher o campo com código válido.  
7.  Clicar em 'Validate'.  
8.  Preencher campo 'Your full name'.  
9.  Clicar em 'Create account'.  
10. Clicar em 'Continue'.  

### Dados de Teste:
* **E-mail:** `bowoxi3670@evoxury.com`  
* **Full name:** `BowoxiTest` 

### Resultado Esperado:
* O sistema não deve permitir a continuação do cadastro.  
* O sistema deve permanecer com o botão 'Continue' desabilitado até o usuário selecionar ao menos três opções de interesse.  

### Status de Execução:  
* **Data da Execução:** 22/08/2025  
* **Testador:** Pablo Costa  
* **Resultado:** PASSED  
* **Observações:** O sistema não permitiu o avanço de cadastro e o botão 'Continue' permaneceu desabilitado.  
