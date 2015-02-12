Openshift LAMP Quickstart
=========================

Este quickstart ajuda a criar uma aplicação LAMP com phpMyAdmin em apenas um passo, adicionando o cartucho PHP e MySQL.

Criando a aplicação
-------------------

Primeiro, cadastre-se gratuitamente em https://getupcloud.com e [instale a ferramenta rhc](https://getup.zendesk.com/entries/38781627).

Criando a aplicação php e usando o quickstart como código inicial:

    rhc app-create mylamp php-5.5 mysql-5.5 --from-code https://github.com/getupcloud/openshift-lamp

Depois de concluído a aplicação poderá ser acessada em [https://mylamp-$namespace.getup.io](#).
