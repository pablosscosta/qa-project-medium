## BUG-GER-001: Ausência de feedback visual e validação para upload de imagem

**Módulo/Funcionalidade:** Gerenciamento de Conteúdo

**Prioridade:** Média (A funcionalidade principal de upload funciona, mas a usabilidade e a segurança são afetadas)

**Ambiente:** Google Chrome Versão 139.0.7258.127 (Versão oficial) 64 bits / Linux Mint 22 Cinnamon Versão 6.2.9

### Passos para Reproduzir:
1.  Fazer login e navegar para a dashboard.
2.  Clicar em 'Write'.
3.  Criar um novo post (com título e texto).
4.  Clicar no ícone '+' para adicionar um bloco de conteúdo.
5.  Selecionar a opção de adicionar imagem.
6.  Fazer upload de uma imagem.

### Resultado Esperado:
* O sistema deveria exibir uma mensagem visual (por exemplo, uma barra de progresso ou um ícone de carregamento) durante o upload da imagem.
* O sistema deveria exibir um pop-up ou notificação confirmando que o upload foi concluído com sucesso.
* O sistema deveria informar o usuário sobre os formatos de arquivo aceitos (ex: PNG, JPG, GIF).

### Resultado Real:
* O sistema permite o upload da imagem, mas não exibe nenhum feedback visual.
* Após o upload, não há nenhuma mensagem de confirmação.
* É possível fazer upload da mesma imagem várias vezes, pois não há um retorno visual claro.
