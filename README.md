Resumo do código:
Este código faz um sorteio de números aleatórios não repetidos dentro de um intervalo definido pelo usuário e apresenta o resultado na página.

Explicação das principais partes:
Função sortear():

Entrada de dados: Lê três valores de campos HTML:
quantidade: Quantos números sortear.
de: Limite inferior do intervalo.
ate: Limite superior do intervalo.
Validações:
Verifica se o limite inferior (de) é menor que o superior (ate).
Confere se a quantidade solicitada não ultrapassa a quantidade de números possíveis no intervalo.
Sorteio:
Sorteia números aleatórios únicos até atingir a quantidade desejada.
Evita números repetidos usando o método includes.
Ordenação (opcional): Se uma checkbox estiver marcada, ordena os números.
Exibição: Exibe os números sorteados na página.
Função obterNumeroAleatorio(min, max):
Retorna um número aleatório entre dois valores (min e max).

Função alterarStatusBotao():
Altera o estilo do botão entre habilitado e desabilitado.

Função reiniciar():
Limpa os campos e redefine o texto do resultado para o estado inicial.

Função preencherIntervalo(de, ate):
Preenche os campos de intervalo e executa o sorteio automaticamente.
