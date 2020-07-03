# Seleção Full Stack Java
Como temos muitas oportunidades para você colocar a mão na massa, queremos ver como você se sai com o cenário abaixo, por meio do qual conseguiremos avaliar várias de suas competências.

## A demanda
Deverá ser criada uma aplicação de cadastro de pessoas:

###  1) Back-end
A aplicação, a ser desenvolvida em Java, deverá expor uma API de cadastro, alteração, remoção e consulta de pessoas com as seguintes informações:
 - Nome - obrigatório
 - Sexo
 - Email - não obrigatório, deve ser validado caso preenchido
 - Data de Nascimento - obrigatório, deve ser validada
 - Naturalidade
 - Nacionalidade
 - CPF - obrigatório, deve ser validado (formato e não pode haver dois cadastros com mesmo cpf)

### 2) Front-end
A aplicação deverá ser acessível via navegador e possuir uma tela com formulário. 
Deverá ser utilizado o Angular, a partir da versão 2, para o desenvolvimento do frontend.

### 3) Instalação
Um manual com as instruções de instalação do projeto deve ser produzido. O mesmo ainda deve conter os endpoints disponiveis para consumo.

### 5) Código fonte
A aplicação deverá estar disponível no GitHub com o código fonte do projeto desenvolvido.

## Extras
1) Teste de integração da API em linguagem de sua preferência;
2) A API deverá conter documentação (Javadoc);
3) Versão 2 da API que deve incluir endereço da pessoa como dado obrigatório. Versão 1 deve continuar funcionando.

## EndPoints
1)Listar todos os cadastrados: GET /api/customers/

2)Listar apenas um cadastro: GET /api/customers/{id}

3)Cadastrar usuario: POST /api/customers/create

  3.1 enviar o json nesse formato
  {
    "nome": "dede",
    "email": "dede@gmail.com",
    "telefone": "55816666999"
   }
   
4)Editar usuario: api/customers/{1}

 4.1 enviar json nesse formato
 {
    "nome": "teste",
    "email": "teste2@gmail.com",
    "telefone": "558712341234"
 }
 
 5)Deletar usuario: /api/customers/{id}


