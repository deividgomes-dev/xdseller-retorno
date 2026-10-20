# xdseller-retorno

Página estática (GitHub Pages) usada como endereço de retorno (redirect) da autorização do Mercado Livre e da Shopee para o xDSeller Pro.
Ela apenas exibe o endereço com o código de autorização para ser copiado; não envia dados a nenhum servidor.
O código só pode ser trocado por um token junto com o `code_verifier` (PKCE), que nunca sai do computador do usuário.
