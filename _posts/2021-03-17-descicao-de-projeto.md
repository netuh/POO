---
layout: post
title: 'Primeiras Funcionalidades'
subtitle: Básico
tags: [projeto]
---

As primeiras funcionalidades da rede social do UNIKUT

# Funcionalidades

Funcionalidade           | Descrição
------------------------ | -----------
Criação de conta         | Permita a um usuário criar uma conta na rede social. Deve ser fornecido um login, uma senha e um nome com o qual o usuário será conhecido.
Edição de perfil         | Permita a um usuário cadastrado editar atributos de seu perfil. Ele deve poder modificar qualquer atributo do perfil.
Adição de amigos         | Permita a um usuário cadastrado do UNIKUT adicionar outro usuário como amigo, o que faz o sistema enviar-lhe um convite. O relacionamento só é efetivado quando o outro usuário o adicionar de volta.
Envio de recados         | Permita a um usuário cadastrado do UNIKUT enviar um recado a qualquer outro usuário cadastrado.

## Criação de conta

O sistema deve permitir que o usuário possa criar uma conta na **UNIKUT**. Algumas restrições são:
- Todo usuário cadastrado DEVE fornecer um **login** e **senha**. O nome é opicional.
- Caso o usuário não forneça um nome. O nome padrão deve ser **convidado**.
- O sistema deve verifica se já não existe um usuário cadastrado previamente com o **login** informado. Caso exista, o sistema deve apresentar uma mensagem de erro e pedir um novo **login**.

## Edição de perfil
O sistema deve permitir que o usuário possa entrar na **UNIKUT** com seu **login** e **senha** cadastrados e alterar seu perfil segundo algumas restrições:
- Não é permito ao usuário alterar o **login**.

## Adição de amigos
O sistema deve permitir que o usuário possa entrar na **UNIKUT** com seu **login** e **senha** cadastrados e adicionar amigos segundo algumas restrições:
- O usuário deve informar o **login** do amigo a ser adicionado. E o sistema deve verificar se o **login** informado está presente no sistema.
- Uma vez que o pedido de amizade é enviado, o status da amizade deve ficar como **PENDENTE**.
- O pedido de amizade só é efetivado quando o outro usuário o adicionar de volta.

## Envio de recados
O sistema deve permitir que o usuário possa entrar na **UNIKUT** com seu **login** e **senha** cadastrados e enviar um recado a qualquer outro usuário cadastrado segundo algumas restrições:
- E o sistema deve verificar se o **login** informado para o destinatário está presente no sistema.
- Cada usuário deve guardar a mensagens enviadas em uma determinada ordem.