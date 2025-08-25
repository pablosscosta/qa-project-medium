## BUG-GER-003: Inconsistência de feedback na exclusão de posts publicados e rascunhos.  

**Módulo/Funcionalidade:** Gerenciamento de Conteúdo

**Prioridade:** Média (A funcionalidade de exclusão de rascunhos exibe mensagem de feedback de confirmação mas a funcionalidade de exclusão de post publicado não apresenta feedback)  

**Ambiente:** Google Chrome Versão 139.0.7258.127 (Versão oficial) 64 bits / Linux Mint 22 Cinnamon Versão 6.2.9

### Passos de Execução: (exclusão de post)  
1.  Na dashboard inicial clicar no ícone de 3 barras no canto superior esquerdo.
2.  No menu lateral clicar na opção 'Stories'.
3.  Na tela de stories selecionar a aba 'Published'.
4.  Selecionar o card do post que deseja excluir.
5.  Com o card aberto, clicar no botão '... More'.
6.  Clicar na opção 'Delete story'.
7.  Confirmar a exclusão.  

### Passos de Execução: (exclusão de rascunho)  
1.  Na dashboard inicial clicar no ícone de 3 barras no canto superior esquerdo.
2.  No menu lateral clicar na opção 'Stories'.
3.  Na tela de stories selecionar a aba 'Drafts'.
4.  Clicar no ícone de seta para baixo que está no card.
5.  Clicar na opção 'Delete story'.  
6.  Confirmar a exclusão.

### Resultado Esperado:  
* O sistema deve ter um comportamento consistente para todas as exclusões.  
* Ele deveria sempre exibir uma mensagem de confirmação para o usuário, independentemente do tipo de post.  

### Resultado Real:  
* O sistema não exibe uma mensagem de confirmação ao excluir um post publicado.  
* O sistema exibe a mensagem 'Successfully deleted post' ao excluir um post como rascunho.  
