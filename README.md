# AA_P3
Identificação das letras mais frequentes num ficheiro de texto usando diferentes metadologias

Abstract:
In this project, carried out within the Advanced Algorithms(40751) curriculum unit, we use 3 methods, Exact Counter, Probabilistic Counter (with fixed probability) and Lossy Counter, to study the most frequent letters in a text file, evaluating each of these methods through various metrics such as accuracy and mean square error. From the results obtained it was possible to conclude that, if we do not encounter memory problems, the Exact Counter method is the best approach, as it always returns the exact values. However, if we are facing a memory problem or at risk of being, both Probabilistic Counter and Lossy Counter methods, are good approaches, as they return sufficiently satisfactory results and with a execution time not much longer than the Exact Counter method. 

Resumo:
Neste projeto, realizado no âmbito da unidade curricular Algoritmos Avançados (40751), procuramos utilizar 3 métodos, Exact Counter, Probabilistic Counter (de probabilidade fixa) e Lossy Counter, para estudar as letras mais frequentes num ficheiro de texto, avaliando cada um destes métodos através de várias métricas como a exatidão e o erro quadrático médio. A partir dos resultados obtidos foi possível concluir que, caso não nos deparemos com problemas de memória, o método de Exact Counter é a melhor abordagem, visto retornar sempre os valores exatos. No entanto, caso estejamos perante um problema de memória ou em risco de o estar, ambos os métodos de Probabilistic Counter e Lossy Counter, são boas abordagens, pois apresentam resultados suficientemente satisfatórios e com um tempo de execução não muito mais elevado que o método Exact Counter.


Conteúdos:

	- Pasta 'codigos' com os ficheiros .py com o código para a resolução deste problema
		-> lossy_counter.py - Método 'Lossy Counter'
		-> prob_counter.py - Método 'Probabilistic Counter'
		-> exact_counter.py - Método 'Exact Counter'
		-> calculate_parameters.py - Código para calcular as métricas, referidas no relatório, para avaliar os modelos
		-> main.py - Código principal, usa o códigos acima para resolver o problema e guardar os resultados nos respetivos ficheiros .txt 
	
	- Ficheiro .pdf com o relatório

	- Pasta 'dirty_files' com os ficheiros tal como se pode descarregar de [1], isto é, não estão formatados para análise

	- Pasta 'clean_files' com os ficheiros 'limpos', isto é, formatados para a análise

	- Pasta 'counter' com 3 pastas no interior, cada uma respetiva a cada método.
		-> Para análise indivual do ranking de letras de um livro, o nome de cada ficheiro encontra-se no formato "NomeDoLivro_Método_Parametro.txt" (parâmetro se for lossy/probabilistic)
		-> Para análise das métricas para avaliar os métodos (contem os 4 livros num ficheiro), o nome de cada ficheiro, encontra-se no formato "metricas_Método_Parametro.txt" (parâmetro se for lossy/probabilistic)
	
	- Pasta 'tops' que permite uma vizualiação mais fácil, do Top 3,5,10 e todas as letras ordenadas de forma de crescente; retornado por cada método para cada livro, isto é, todos os livros num ficheiro
		-> Formatação "NomeDoMétodo_parametro"(parâmetro se for lossy/probabilistic)

	- No projeto, para o método Probabilistic counter, para alem de se usar uma probabilidade de 1/(2^3), para comparação também se usou uma de 1/(2^8),
	  para o livro 'O livro de Cesário Verde', cujos resultados encontram-se na pasta 'Extra -> Probabilistic Counter, k=8'



[1] Project Gutenberg - https://www.gutenberg.org/
