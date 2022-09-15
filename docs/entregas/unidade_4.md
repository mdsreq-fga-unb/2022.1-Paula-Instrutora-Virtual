# Time de Requisitos 
<br>

##Framework SAFe

![SAFe 4](./../img/safe_unidade_4.png)

##PBB/BDD

####PBB
![PBB](./../img/PBB_unidade_4.png)

####BDD
![BDD](./../img/BDD_unidade_4.png)

##User Story Mapping
![USM](./../img/USM.png)

##Casos de Uso

###Especificação de caso de uso "Cadastrar Aluno"
![CASO1](./../img/caso_uso_1.jpg)
<br><br>
O aluno, com o auxílio de um Tutor (qual seja letrado). Cadastrará o Aluno no Sistema Paula.<br>

**Fluxo Básico**:<br><br>
1- O tutor acessa a opção cadastrar Aluno
2- O sistema apresenta os campos para serem preenchidos (RN2)
3- O tutor preenche os campos
4- O sistema válida os campos (FE1, FE2, FE3)
5- O sistema autêntica aluno
6- Encerra Caso de Uso<br><br>

**Regra de Negócios**:<br><br>
RN2. Campos de Cadastro são Nome, Apelido, Senha, Data de Aniversário e Gênero<br><br>

**Fluxo Erros**:<br><br>
FE1- Apelido Existente No passo . do fluxo básico, se o sistema determinar que o apelido do aluno já está sendo usado, o sistema mostra a mensagem "Aluno já Cadastrado"

FE2- Apelido Pequeno No passo . do fluxo básico, se o sistema determinar que o apelido deve possuir mais do que 3 caracteres, o sistema mostra a mensagem "O apelido deve possuir no mínimo 3 caracteres"

FE3- Senha No passo . do fluxo básico, se o sistema determinar que a senha não atingiu o tamanho mínimo de 4 caracteres, o sistema mostra a mensagem "A senha deve possuir mais do que 4 caracteres"

FE4- Data de Aniversário No passo . do fluxo básico, se o sistema determinar que o aluno cadastrado, tem menos de 5 anos de idade, o sistema mostra a mensagem "O aluno deve possuir mais do que 5 anos"

FE5- Campo não preenchido No passo . do fluxo básico, se o sistema determinar que algum campo não foi preenchido, o sistema mostra a mensagem "Informe <Campo Faltante>" 

<br><br>
###Especificação de caso de uso Concluir Módulo
![CASO2](./../img/caso_uso_2.jpg)<br>

Para cada Lição do Módulo, o Usuário irá realizar atividades. Quando todas atividades tiverem prontas o Usuário conclui o Módulo<br>

**Fluxo Básico**:<br><br>
1- O aluno Efetua Login<br>
2- O sistema válida o apelido e senha (A1, A2)<br>
3- O aluno acessa um dos Módulo Disponíveis<br>
4- O sistema apresenta Lições Dentro do Módulo<br>
5- O aluno seleciona uma lição disponível<br>
6- O sistema exibe a lição<br>
7- O aluno realiza uma das 4 atividades da lição<br>
8- O sistema válida a resposta do Aluno (A3)<br>
9- O sistema atualiza o status da Atividade<br>
10- Se houver mais atividade de lição aluno retorna para 7.<br>
11- O sistema atualiza o status de progresso (A4)<br>
12- Se houver mais lições o aluno retorna para 5<br>
13- O sistema atualiza o status do Módulo como concluído. (RN1)<br>
14- Encerra o Caso de Uso<br><br>


**Regras de Negócio**:<br><br>
RN1. O Aluno recebe uma recompensa Virtual ao finalizar um Módulo.
<br><br>

**Fluxo Alternativos**:<br><br>
FA1. Aluno não cadastrado No passo 1 do fluxo básico, se o sistema determinar que o apelido do aluno não é válido, o sistema mostra a mensagem "Apelido Incorreto".

FA2. Senha Inválida No passo 1 do fluxo básico, se o sistema determinar que a senha do aluno não é válida, o sistema mostra a mensagem "Senha Incorreta".

FA3. Resposta Incorreta No passo 8 do fluxo básico, se o sistema determinar que o aluno não respondeu corretamente, o sistema deverá mostrar a mensagem "Reposta Errada", e prosseguir para próxima lição.

FA4. Lição Não Concluída No passo 11 do fluxo básico, se o sistema determinar que o aluno não respondeu corretamente mais de uma atividade, o sistema deverá definir o status da lição como não concluída e o aluno deverá realizar a lição novamente.

<br>
##[Link do Feedback do cliente sobre o produto](https://drive.google.com/drive/folders/10KJ_SKPHqVpJPsNYFnxn8oxrpm6G3PSC?usp=sharing)

<br>

# Time de Métodos de Desenvolvimento de Software 
<br>
