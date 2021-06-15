# projeto-locadora

# Projeto para a disciplina de Programação WEB

## 2.1 Tela de login

Esta será a primeira tela do sistema. Ao clicar no botão entrar o sistema deverá ser
direcionado à Tela Principal.
(Não haverá validação de campos.)

## 2.2 Tela Principal

CABEÇALHO
MENU

### 2.2.1 Cabeçalho
O cabeçalho irá conter o nome do sistema e um link que levará o usuário, de onde
estiver, de volta para a tela principal. (O link poderá estar no próprio nome do sistema ou em
uma imagem, fica a critério da equipe. Porém deverá ser padronizado em todas as telas)
Importante: O cabeçalho será o mesmo em todas as telas do sistema (exceto a tela de login).

### 2.2.2 Menu
O menu da tela principal deverá conter links para as seguintes telas:
- Cadastros
- Locação
- Devolução
- Acervo
- Sobre

## 2.3 Tela cadastros

CABEÇALHO
MENU

### 2.3.1 Menu de cadastro
O menu da tela cadastros deverá conter links para as seguintes telas:
- Filme
- Usuário

## 2.4 Tela de formulários

Este layout será aplicado às telas:
- Cadastro de Fita
- Cadastro de Usuário
- Locação
- Devolução
- Acervo

CABEÇALHO
NAVEGAÇÃO

FORMULARIO

- Ao clicar na seta voltar ( ) o sistema deverá seguir as seguintes regras:
1- Quando a tela for locação, devolução, acervo ou sobre, ao clicar em voltar ( ), o sistema
deverá ser direcionado à Tela Principal.
2- Quando a tela for cadastro de usuário ou cadastro de filme, deverá ser direcionado à tela de
cadastros.
- A seta próximo ( ) só será usado quando as informação forem divididas me mais de uma
página. Provavelmente não será usada neste sistema.

## 3 Campos presentes nos Formulários

Aqui serão descritos os campos que irão constar em cada formulário.
Importante: Todos os componentes deverão ter ID único.

## 3.1 Tela de Login
Será composto dos seguintes campos:
• Usuário: Text box
• Senha: Password
• Entrar: Button Submit

Obs: Ao clicar no botão entrar, independente do que for digitado nos campos usuário e senha,
o sistema deverá ser direcionado para a Tela Principal. Não haverá validação de campos nesta
fase do projeto.

## 3.2 Cadastro de Filme
Será composto dos seguintes campos:
• Título: Text box
• Gênero: Select list (incluir pelo menos 5 gêneros)
• Prêmios: Check box1 (incluir pelo menos 5 opções de prêmios)
• Descrição: Text área
• Cadastrar: Button

## 3.3 Cadastro de Usuário
Será composto dos seguintes campos:
• Nome: Text box
• Sexo: Radio buttons
• Preferências: Check box (Incluir pelo menos 5 gêneros)
• Observações: Text área
• Cadastrar: Button

## 3.4 Locação
Será composto dos seguintes campos:
• Cliente: Select list (Os clientes disponíveis serão os integrantes do grupo)
• Data locação: Text box

1 https://pt.wikipedia.org/wiki/Lista_de_pr%C3%AAmios_de_cinema

• Data entrega: Text box
• Observações: Text área
• Confirmar: Button

## 3.5 Devolução
Será composto dos seguintes campos:
• Cliente: Select list (Os clientes disponíveis serão os integrantes do grupo)
• Data entrega: Text box
• Status: Radio bottons (Dentro do prazo / Atrasado)
• Observações: Text área
• Confirmar: Button

## 3.6 Acervo
Na tela principal, ao clicar em acervo, será exibida a imagem da capa de cada filme.
Ao clicar na imagem do filme, o usuário será direcionado a uma página de detalhes do filme com
as seguintes informações:
• Diretor
• Lista com os atores principais
• Ano lançamento
• Trailer (Ao clicar, o usuário poderá assistir ao trailer do filme na própria página ou ser
direcionado para outro site (Ex. Youtube)
• Descrição do filme
• No final da página deverá ter um link (Mais detalhes...) que levará o usuário a um site
externo com mais detalhes.
o A escolha do site externo fica a critério do grupo.
o Ao clicar em “Mais detalhes...” o link deverá ser aberto nova aba do navegador).

Obs: Deverá haver ao menos um filme para cada integrante do grupo.

## 3.7 Sobre
A tela sobre deverá exibir uma breve descrição do sistema e uma lista com o nome de todos os
participantes do grupo.
