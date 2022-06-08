# Análise de Sistema: Visualização de horário das aulas.

## Regras de confeccção de horário - Dados obtidos por entrevista

1. Professor informa sua disponibilidade de horário para o coordenador de cada disciplina a ser lecionada;
2. O coordenador é quem tem a função de separar a grade de aulas;
3. O coordenador deve seguir a disponibilidade informado pelo professor;
4. Assim que o coordenador finalizar o horário, deverá enviar para os funcionários responsáveis da secretaria da faculdade;
5. Secretaria tem a função de upar os horários no siga por conta de não haver sincronização direta;

# Regras de negócio

## Requisitos Não Funcionais

| Código  | Descrição  | Essencial  | Importante   | Opcional| 
| ------  | ---------  | ---------  | ----------   | -------- |
| RNF01   | O sistema deve funcionar no início do semestre letivo |X|||
| RNF02   | O sistema deve estar acessível via navegador de internet Chrome. |X|||
| RNF03   | A interface deve ser agradável e de fácil utilização.  ||X||
| RNF04   | O banco de dados deve ser desenvolvido no SQL Server.  ||x||
| RNF05   | O sistema deve utilizar DotNet para o Back-End. ||x||
| RNF06   | O sistema deve utilizar entity framework ||x|||   |   |
| RNF07   | O sistema deve frameowrk Angular para o Front-end |||x||


## Requisitos  Funcionais

| Código  | Descrição  | Essencial  | Importante   | Opcional| 
| ------- | --------  | ------- | -------- |  ------- |
| RF01   | Os funcionários deve ser cadastrados pelo administrador Os funcionários deve ser cadastrados pelo administrador  |X|||
| RF02   | Os professor precisam logar para realizar o cadastro. |X|||
| RF03   | Deve haver uma autenticação de login.  ||X||
| RF04   | O sistema deve armazenar log de qualquer ação com data e hora e a determinada ação realizada   |X|||
| RF05   | O coordenador tem que realizar a aprovação ou reprovação de horas |X|||
| RF06   | Os professores devem seguir as regras de negócio em disponibilidade |X||||   |   |
| RF07   | Deve haver uma sincronização com o siga |X||||   |   |
| RF08   | Deve haver uma possibilidade da secretarua baixar o arquivo como Excel|X||||   |   |
| RF09   | Os professores devem lançar sua disponibilidade em uma tabela |X||||   |   |
| RF11   | O sistema deve ter um menu lateral   |X||||   |   |
| RF12   | Em caso de reprovação de horário, o professor deve ser notificado pela plataforma e por e-mail   |X||||   |   |

## Regras para confeccionar o lançamento de disponibilidade
1. Marque as caixas vazias em que você TEM disponibilidade para ministrar aulas.
2. Sua disponibilidade precisa ser pelo menos 50% superior ao total de horas-aulas a ministrar no turno (M, T, N).
3. Se o seu total de aulas para o  2º Semestre 2022 for diferente do proposto aqui, dê a disponibilidade apropriada.
4. Deverá ser respeitado o interstício de 11 horas entre a jornada da noite e da manhã.
5. Deverá ser respeitado o interstício de 11 horas entre a jornada da noite e da manhã.
6. Deverá ser respeitado o interstício de 11 horas entre a jornada da noite e da manhã.
7. Será considerada a disponibilidade total caso o docente não entregue sua disponibilidade até a data informada.
8. Para enviar a planilha até o coordenador, será necessário apenas apertar o botão enviar na aba “Definir Disponibilidade”.

# Prototipação

Link protótipo Figma: https://www.figma.com/proto/d1rCw8RfYYlMJKqGoP2Jja/Untitled?page-id=0%3A1&node-id=2%3A2&viewport=-1014%2C421%2C0.58&scaling=min-zoom&starting-point-node-id=2%3A2


# Cronograma

- O projeto deve seguir a metodologia ágil Scrum. Conferir a aba projeto no Github
