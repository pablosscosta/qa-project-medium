## BUG-GER-002: Ausência de feedback visual e validação para exclusão de post

**Módulo/Funcionalidade:** Gerenciamento de Conteúdo

**Prioridade:** Média (A funcionalidade principal de exclusão funciona, mas a usabilidade e a segurança são afetadas)

**Ambiente:** Google Chrome Versão 139.0.7258.127 (Versão oficial) 64 bits / Linux Mint 22 Cinnamon Versão 6.2.9

### Passos para Reproduzir:
1.  Na dashboard inicial clicar no ícone de 3 barras no canto superior esquerdo.
2.  No menu lateral clicar na opção 'Stories'.
3.  Na tela de stories selecionar a aba 'Published'.
4.  Selecionar o card do post que deseja excluir.
5.  Com o card aberto, clicar no botão '... More'.
6.  Clicar na opção 'Delete story'.
7.  Confirmar a exclusão.

### Resultado Esperado:  
* O sistema deve permitir a exclusão do post.  
* O post não deve mais ser visível na lista de 'Published'.  
* O sistema deve exibir uma mensagem de confirmação de exclusão.  

### Resultado Real:  
* O sistema permitiu a exclusão do post.
* O sistema não informou uma mensagem de feedback visual sobre o status da exclusão.
