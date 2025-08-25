## CT-GER-006: Exclusão de um Post como rascunho com sucesso

**Módulo/Funcionalidade:** Gerenciamento de Conteúdo  
**Cenário de Teste:** Verificar o comportamento do sistema ao tentar excluir um rascunho.  
**Pré-condições:** Ter conexão com a internet. Estar logado no sistema. Ter um ou mais rascunhos no  perfil.  

### Passos de Execução:
1.  Na dashboard inicial clicar no ícone de 3 barras no canto superior esquerdo.
2.  No menu lateral clicar na opção 'Stories'.
3.  Na tela de stories selecionar a aba 'Drafts'.
4.  Clicar no ícone de seta para baixo que está no card.
5.  Clicar na opção 'Delete story'.  
6.  Confirmar a exclusão.

### Dados de Teste:
* **Post:** Um rascunho para ser excluído.

### Resultado Esperado:
* O sistema deve permitir a exclusão do rascunho.
* O post não deve mais ser visível na lista de 'Drafts'.
* O sistema deve exibir uma mensagem de confirmação de exclusão.

### Status de Execução:
* **Data da Execução:** 25/08/2025
* **Testador:** Pablo Costa
* **Resultado:** PASSED
* **Observações:** O sistema permitiu a exclusão e informou a mensagem 'Successfully deleted post'.  
