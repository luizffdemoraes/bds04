# ds-city-event
# Desafio para entregar
TAREFA: Validação e Segurança

Implemente as funcionalidades necessárias para que os testes do projeto abaixo passem:
https://github.com/devsuperior/bds04

Collection do Postman:
https://www.getpostman.com/collections/e1f59c905aeca84c1ebc

Este é um sistema de eventos e cidades com uma relação N-1 entre eles:
Neste sistema, somente as rotas de leitura (GET) de eventos e cidades são públicas (não
precisa de login). Usuários CLIENT podem também inserir (POST) novos eventos. Os demais
acessos são permitidos apenas a usuários ADMIN.

Caso tenha dúvidas nas regras de autorização do ResourceServerConfig, colocamos uma sugestão em
linguagem natural na próxima página.

## UML Project
![UML 1](/images/uml-user-role-to-city-event.png)

Validações de City:
=================
<!--ts-->
* Nome não pode ser vazio
<!--te-->

Validações de Event:
=================
<!--ts-->
* Nome não pode ser vazio
* Data não pode ser passada
* Cidade não pode ser nula
<!--te-->

Mínimo para aprovação: 9/12


