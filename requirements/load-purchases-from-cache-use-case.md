# Carregar Compras do Cache

> ## Caso de sucesso
1. Sistema executa o comando "Carregar Compras"
2. Sistema carrega os dados do Cache
3. Sistema valida se o Cache tem menos de 3 dias
4. Sistema cria uma lista de compras a partir dos dados do Cache
5. Sistema retorna a lista de compras

> ## Exceção - Cache expirado
1. Sistema limpa o Cache
2. Sistema retorna o erro

> ## Exceção - Cache expirado
1. Sistema retorna o erro