## CT-GER-005: Exclusão de um Post com Sucesso

**Módulo/Funcionalidade:** Gerenciamento de Conteúdo  
**Cenário de Teste:** Verificar o comportamento do sistema ao tentar excluir uma publicação postada.  
**Pré-condições:** Ter conexão com a internet. Estar logado no sistema. Ter post publicado.  

### Passos de Execução:
1.  Na dashboard inicial clicar no ícone de 3 barras no canto superior esquerdo.
2.  No menu lateral clicar na opção 'Stories'.
3.  Na tela de stories selecionar a aba 'Published'.
4.  Selecionar o card do post que deseja excluir.
5.  Com o card aberto, clicar no botão '... More'.
6.  Clicar na opção 'Delete story'.
7.  Confirmar a exclusão.

### Dados de Teste:
* **Post:** Um post publicado para ser excluído.

### Resultado Esperado:
* O sistema deve permitir a exclusão do post.
* O post não deve mais ser visível na lista de 'Published'.
* O sistema deve exibir uma mensagem de confirmação de exclusão.

### Status de Execução:
* **Data da Execução:** 25/08/2025
* **Testador:** Pablo Costa
* **Resultado:** FAILED
* **Observações:** O sistema permitiu a exclusão mas não informou uma mensagem de feedback.
