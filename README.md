# Desafio de otimização de afinidades



Numa escola, antes da definição das turmas, cada aluno preenche um formulário informando com quais colegas tem afinidade, resultando na tabela abaixo (onde 1 indica afinidade).

(Vide Excel)

Matriz de afinidades (é simétrica, se um aluno tem afinidade com outro, o inverso também é verdadeiro):



Aluno 1	Aluno 2	Aluno 3	Aluno 4	Aluno 5	Aluno 6	Aluno 7	Aluno 8	Aluno 9	Aluno 10	Aluno 11	Aluno 12	Aluno 13	Aluno 14	Aluno 15
Aluno 1		1	0	1	1	1	1	0	0	1	0	1	1	0	1
Aluno 2	1		0	0	1	0	0	0	1	0	1	0	0	0	0
Aluno 3	0	0		0	0	0	1	0	1	0	0	1	0	0	1
Aluno 4	1	0	0		1	0	0	0	0	0	1	0	0	1	1
Aluno 5	1	1	0	1		0	0	1	0	0	1	1	1	0	1
Aluno 6	1	0	0	0	0		1	0	0	0	0	1	0	0	0
Aluno 7	1	0	1	0	0	1		1	1	0	1	0	1	0	0
Aluno 8	0	0	0	0	1	0	1		1	1	0	0	1	1	1
Aluno 9	0	1	1	0	0	0	1	1		0	1	0	0	0	1
Aluno 10	1	0	0	0	0	0	0	1	0		1	1	1	0	1
Aluno 11	0	1	0	1	1	0	1	0	1	1		1	1	0	0
Aluno 12	1	0	1	0	1	1	0	0	0	1	1		0	0	0
Aluno 13	1	0	0	0	1	0	1	1	0	1	1	0		1	1
Aluno 14	0	0	0	1	0	0	0	1	0	0	0	0	1		0
Aluno 15	1	0	1	1	1	0	0	1	1	1	0	0	1	0	



A escola deve dividir os 15 alunos em 3 turmas de 5 alunos cada.



Dois alunos com afinidade gostam de estar na mesma turma, e dois alunos sem afinidade são indiferentes.


Exercício 1: Dada a alocação abaixo, qual o score de afinidade total?

Alocação	Turma 1	Turma 2	Turma 3
Aluno 1	0 0 1 
Aluno 2	0 0 1
Aluno 3	0 0 1
Aluno 4	0 0 1
Aluno 5	0 0 1
Aluno 6	0	1	0
Aluno 7	0	1	0
Aluno 8	1	0 0	
Aluno 9	0	1	0
Aluno 10	0	1	0
Aluno 11	0	1	0
Aluno 12	1	0	0
Aluno 13	1	0	0
Aluno 14	1	0	0
Aluno 15	1	0	0


Exercício 2 (mais difícil): Qual a melhor forma de alocar os alunos, de modo a maximizar a afinidade total?


Turma 1	Turma 2	Turma 3
Aluno 1			
Aluno 2			
Aluno 3			
Aluno 4			
Aluno 5			
Aluno 6			
Aluno 7			
Aluno 8			
Aluno 9			
Aluno 10			
Aluno 11			
Aluno 12			
Aluno 13			
Aluno 14			
Aluno 15			

