# Preencher-e-exibir-10-valores


 
Moodle - IFRS

Programador Web - Turma 2022A
Painel Meus cursos  PW2022A  3 Lógica de Programação  3.29 Praticando um pouco...
 
3.29 Praticando um pouco...
Neste curso, você faz seu próprio tempo de estudos. Seu progresso será aferido pelos questionários denominados "Teste seu conhecimento". Entretanto, sabemos da importância em praticar, pois só assim você aperfeiçoar sua aprendizagem. Para isso, elaboramos esse livro, com algumas questões desafiadoras e seu gabarito. Utilize o menu de navegação para acessar os enunciados. Quando finalizar sua resposta, confira com o gabarito localizado logo abaixo.



 

Exercício 4: Preencher e exibir 10 valores
Gabarito do Exercício 4
Exercício 4: Faça um programa que crie um vetor de 10 números inteiros. Em seguida, peça para o usuário informar os 10 valores. Após isso, exiba os 10 valores (um por linha)

programa
{
   funcao inicio() 
   {
      inteiro vetor[10]
      para (inteiro pos = 0; pos < 10; pos++){
         escreva("Informe o número da posição "+(pos+1)+": ")
         leia(vetor[pos])
      }

      para (inteiro pos = 0; pos < 10; pos++){
         escreva(vetor[pos]+"\n")
      }
   }
}
