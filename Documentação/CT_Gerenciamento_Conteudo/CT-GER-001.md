## CT-GER-001: Tentativa de post sem título e texto.  

**Módulo/Funcionalidade:** Gerenciamento de Conteúdo  
**Cenário de Teste:** Verificar o comportamento do sistema ao tentar publicar sem preencher título e texto.  
**Pré-condições:** Ter conexão com a internet. Estar logado no sistema.  

### Passos de Execução:
1.  Na dashboard inicial clicar em 'Write'.  
2.  Não preencher campo 'Title' e 'Tell your story...'.  
3.  Clicar no botão 'Publish'.  


### Dados de Teste:
* **Título:** Em branco  
* **Texto:** Em branco  

### Resultado Esperado:
* O sistema não deve permitir que o botão 'Publish' esteja disponível para clique.  
* O sistema deve informar ao usuário que é necessário escrever algo antes de publicar.  

### Status de Execução:
* **Data da Execução:** 23/08/2025  
* **Testador:** Pablo Costa  
* **Resultado:** PASSED  
* **Observações:** O sistema não permitiu a publicação. O sistema mostrou a mensagem 'Publishing will become available after you start writing'.  
