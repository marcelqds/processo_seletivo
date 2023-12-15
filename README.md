<h1 align="center">Fluig - Processo seletivo</h1>
<!-- <p align="center">
  <a href="#sobre">Sobre</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#projetos">Técnologias utilizadas</a>&nbsp;&nbsp;|&nbsp;&nbsp;  
</p> -->


## Sobre
- Projeto construido como proposta do curso de fluig através da Escola de Implementadores - Totvs Fluig. O mesmo tem por finalidade, a construção de um simples processo seletivo, e a partir de que um candidato seja aprovado, um usuário deverá ser criado automaticamente para ele via rest no protheus.


## Técnologias
- [x] Eclipse Lunar
- [x] Fluig 1.8.1
- [X] BPMN 1.0 / BPMN 2.0
- [X] JQuery 
- [X] Aws Lambda
- [X] Aws ApiGateway
- [X] NodeJs 20.x


## Formulários
- preCadastroVaga
  - Descrição
  - Nível
  - Status
- cadastroCandidato
  - Vaga
  - Nível
  - Salário desejado
  - Nome
  - email
  - linkedIn
  - tempo de experiência 

## Dataset
- dsVaga
- dsCandidato

## Serviço
- Serviço na plataforma - REST
  - protheus_homolog (name)
  - https://mglaiwonq8.execute-api.sa-east-1.amazonaws.com (domain)
  - GET /default/protheus (rota para teste)
  - POST /default/protheus (para para criação de usuário)


