1º) - Executar 'utils.R' (função de limpeza)

2º) - em 'ANÁLISE DE SENTIMENTO COM BASE EM DADOS DO TWITTER.RMD' preencher 
com suas chaves da API do Tweeter

3º) - Na Etapa 2, digitar o tema que deseja pesquisar em "A" e o número de tweets em B

      "## Etapa 2 - Coleta dos Dados - carregamento dos Tweets
       ```   {r tweets}

       # Limite máximo de 18000 Tweets, por pesquisa

       tweetdata <- search_tweets(
       "A", n = B, include_rts = FALSE,lang = "pt")"

4º) - executar todas as etapas do algoritmo, um por vez, esperando que cada etapa 
seja concluída, finalizado o processo terá todas as informações disponíveis para analisa
