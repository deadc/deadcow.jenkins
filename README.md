Jenkins
=========

[![CircleCI](https://circleci.com/gh/deadc/deadcow.jenkins/tree/master.svg?style=shield)](https://circleci.com/gh/deadc/deadcow.jenkins/tree/master)

Jenkins é um servidor de Integração Contínua open-source feito em Java, pode ser rodado de forma standalone ou como uma web aplicação dentro de um servidor web.

Requerimentos
------------
Nenhum

Variaveis
--------------

Nenhum

Dependencias
------------

Nenhum

Playbook exemplo
----------------

    - hosts: all

      roles:
         - { role: jenkins }

Licença
-------

BSD

Author Information
------------------

Esta role foi desenvolvida por Thiago Freitas (deadcow@archlinux.com.br) em 03/2018
