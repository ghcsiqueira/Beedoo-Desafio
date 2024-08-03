# Beedoo-Desafio 
> 


## 💡 User storie 001 - A página inicial 
> * Como aluno
> * Gostaria de verificar todos os cursos disponíveis
> * Para conseguir me inscrever no curso que desejo

### ✔️ Critérios de aceitação

| Campo | Descrição |
| ----- | --------- | 
| Ordenação | Os cards dos cursos devem ser apresentados de forma ordenada de acordo com a data de criação do curso| 
| Tamanho | Os cards devem ter tamanhos padronizados (iguais) | 
| Nome | Os cards devem apresentar o nome do curso | 
| Descrição | Os cards devem apresentar a descrição completa do curso | 
| Imagem | Os cards devem apresentar a imagem | 
| Instrutor | Os cards devem informar o nome do instrutor | 



## 💡 User Storie 002 - Cadastro de novo curso
> * Como um administrador
> * Gostaria de conseguir cadastrar um curso
> * Para que nossos alunos possam se inscrever
 
### ✔️ Critérios de aceitação


| Campo | Descrição | Obrigatoriedade | 
| -----|---------| --------------- | 
| Nome do curso | Deverá aceitar somente letras e caracteres especiais. | Sim | 
| Descrição do curso | Deverá aceitar caracteres Alfanumérico | Sim | 
| Instrutor | Deverá aceitar caracteres alfabéticos | Sim |
| Imagem da capa do curso | Deverá ser possível informar o link da imagem | Sim | 
| Data de ínicio | Deverá ser possível informar a data com formato DD/MM/AAAA | Sim | 
| Data de fim | Deverá ser possível informar a data com formato DD/MM/AAAA e a data não pode ser menor que a data de início | Sim |
| Número de vagas | Deverá ser possível cadastrar somente quantidade de vagas positivas | Sim | 
| Tipo de curso presencial | Ao selecionar esta opção deverá ser aparecer um novo campo para informar o endereço onde o curso acontecerá | Sim |
| Tipo de curso online | Ao selecionar esta opção deverá ser aparecer um novo campo para informar o link do curso | Sim | 


## 💡 User Storie 003 - Excluir curso
> * Dado que sou administrador
> * Gostaria de conseguir excluir um curso
> * Para que não seja possível que alunos se inscrevam em cursos que já finalizaram

### ✔️ Critérios de aceitação
| Campo | Descrição |
| -----|---------|
| Excluir | Ao excluir, o curso deve ser removido imediatamente da listagem de cursos | 
| Confirmação | Ao excluir, o sistema deve enviar a confirmação visual da exclusão do curso | 

# Sugestão de melhorias

## 💭 Formulário de cadastro
> Durante a criação de um curso, caso algum campo não seja preenchido
> Deve-se mostrar uma mensagem de erro informando ao usuário que o preenchimento do campo é obrigatório
> Deve-se mostrar a quantidade máxima de caracteres na descrição do curso


| Campo | Mensagem de erro | 
| -----|---------|
| Nome do curso | Este campo é obrigatório | 
| Descrição do curso | Quantidade máxima de caracteres permitida é 1000 | 
| Instrutor | Este campo é obrigatório | 
| Data de início | Este campo é obrigatório | 
| Data de fim | Este campo é obrigatório | 
| Número de vagas | Este campo é obrigatório | 
| Tipo de curso | Este campo é obrigatório | 
| Endereço | Este campo é obrigatório | 
| Link de inscrição | Este campo é obrigatório | 

## 💭 Filtros de pesquisa
| Filtros | Descrição | 
| -----|---------|
| Nome do curso | Buscar pelo nome próximo ou igual ao curso | 
| Data de ínicio | Busca para mostrar quais cursos começaram naquela determinada data | 
| Tipo de curso | Busca para tipos de curso online ou presencial | 
| Instrutor | Busca para determinado instrutor | 
