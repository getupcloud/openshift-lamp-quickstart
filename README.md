Openshift LAMP Quickstart
=========================

Este repositório git ajuda a criar uma aplicação LAMP com phpMyAdmin em apenas um passo.

Criando a aplicação
-------------------

Primeiro, cadastre-se gratuitamente em https://getupcloud.com e [instale a ferramenta rhc](https://getup.zendesk.com/entries/38781627).

Crie uma aplicação php e use este repositório como código inicial:

    rhc app-create mylamp php-5.5 mysql-5.5 --from-code https://github.com/getupcloud/openshift-lamp

Acesse a aplicação exemplo em [https://mylamp-$namespace.getup.io](#) para mais instruções.
