# BraSNAM2018-Dataset-Analise-de-sentimentos-em-tweets-em-portugues-brasileiro
O repositório contém os dados usados no trabalho "Análise de Sentimentos em ​Tweets​ em Português Brasileiro" publicado no BraSNAM-2018

<b>Resumo</b>

Este trabalho apresentou uma metodologia para comparar técnicas que classificam sentimentos expressos diretamente ou indiretamente em tweets no idioma português brasileiro. Os resultados apresentados são promissores ao classificar sentimentos distintos, pois o melhor classificador alcança 85% de acerto. Por outro lado, relações entre sentimentos próximos apresentam resultados inferiores a 70% de acerto.

<b>Metodologia</b>

Foi utlizado o SQL Server 2012 para armazenamento dos dados. 

No repositório é disponibilizado o script "DDL_Criacao_Tabela_Com_Todos_Dados", onde contém a instrução de criação da tabela juntamente com a inserção de todos os dados. Assim, para obter os dados, basta executar o script "DDL_Criacao_Tabela_Com_Todos_Dados".

É importante ressaltar que os dados disponibilizados já passaram por alguns processamentos apresentados no trabalho. Assim, os principais emojis contidos nos tweets foram substituídos por palavras-chave, exemplo: O emoji ❤ foi substituído pela palavra ECoracao. 

A coleta dos dados foi feita entre os meses de agosto e outubro de 2017, contando com 12.814 tweets coletados ao todo. Com a remoção de tweets com textos repetidos, restaram 11.513 disponibilizdos no script "DDL_Criacao_Tabela_Com_Todos_Dados".
