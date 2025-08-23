## CT-GER-003: CT-GER-003: Criação de um Post preenchendo todas informações.  

**Módulo/Funcionalidade:** Gerenciamento de Conteúdo  
**Cenário de Teste:** Verificar o comportamento do sistema ao tentar publicar post completo.  
**Pré-condições:** Ter conexão com a internet. Estar logado no sistema.  

### Passos de Execução:
1.  Na dashboard inicial clicar em 'Write'.  
2.  Preencher campo 'Title'.  
3.  Preencher campo 'Tell your story...'.  
4.  Clicar no botão 'Publish'. 
5.  Adicionar imagem.  
6.  Adicionar tópicos.  
7.  Clicar no botão 'Publish now'.  


### Dados de Teste:
* **Título:** `Post de teste completo`  
* **Texto:** `Esse post é apenas um teste de QA para verificar o fluxo de publicação.`   
* **Imagem:** Gerada por IA (ChatGPT)  
* **Tópicos:** `Tópico 1`, `Teste 2`, `Terceiro`, `Number 4`, `Five`

### Resultado Esperado:
* O sistema deve permitir a publicação.  

### Status de Execução:
* **Data da Execução:** 23/08/2025  
* **Testador:** Pablo Costa  
* **Resultado:** PASSED  
* **Observações:** O sistema permitiu a publicação.
O upload da imagem é um ponto a melhorar.
A plataforma não informa qual formato de imagem aceita e após o upload não dá retorno se a imagem foi carregada.
Dessa forma é fácil publicar imagens duplicadas, por exemplo.
