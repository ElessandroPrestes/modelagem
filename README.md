
## **Cenário** 
Vanessa possui uma escola de idiomas e faz alguns controles manuais. 

Ela gostaria de melhorar seus controles e informações para tomada de decisão e, para tanto, 
deseja contratar uma cooperativa de profissionais em TI para desenvolver um sistema 
informatizado para que ele pudesse resolver os seguintes problemas:

1 - Vanessa não sabe quais os alunos que mais gastam na escola.<br />
2 - Vanessa não sabe quais são os idiomas mais vendidos (inglês, espanhol, italiano, etc).<br />
3 - Vanessa não sabe quantos alunos estão cursando cada idioma.<br />
4 - Vanessa não sabe quanto ela fatura com a venda de cursos de idiomas na sua escola.<br />
5 - Vanessa pretende expandir seus negócios vendendo livros em vários idiomas.<br />

Supondo que você ajudará no desenvolvimento deste sistema, utilizando um banco de dados 
relacional, como você construiria a modelagem do banco de dados do sistema para atender ass
necessidades da Vanessa?

<br />
<br />

<div align="center">
  <img src="" width="700px" />
<div>
  
<br />
<br />
  
  1 - Os alunos precisam estar matriculados, posteriormente estarão vinculados as suas respectivas turmas, podendo escolher entre um ou mais idiomas aprender.<br />
  2 - Os idiomas mais vendidos,  se darão de acordo com as matriculas efetuadas, sendo abertas as turmas, de acordo com os idiomas onde foram matriculados.<br />
  3 - Através da matricula, estes alunos estão vinculados as turmas, sendo assim vinculados a quais idiomas frequentam.<br />
  4 - Através da matricula efetuada, são gerados as turmas, que por sua vez possuem os valores da matricula de cada idioma.
  5 - Efetuado a modelagem de livros para expensão de venda de livros pela escola.