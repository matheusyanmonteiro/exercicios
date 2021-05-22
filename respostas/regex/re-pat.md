## Q1)
Com a regex (\d{2})/(\d{2})/(\d{4}) é possível encontrar as datas e a regra $2/$1/$3 converte elas para o formato brasileiro.

## Q2)
Com o módulo "re", criei as seguintes variáveis: uma variável com o texto gerado a partir do arquivo, uma variável com a regex e uma variável com as respostas.

Usando a regex <img src=\"(/\w+)+.gif\"> é possível encontrar os arquivos com a terminação ".gif". Com isso, igualei a variável ads respostas com a função re.findall(r"<img src="(/\w+)+.gif">", <variável com o texto>) e encontrei todos os arquivos com a terminação ".gif". E para calcular o tamanho da variável das repostas, foi utilizada a função len().