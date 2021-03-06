# [Globo.com] - Oficina de como criar sua primeira ontologia
===========

Web Semântica na Prática: **Criando seu Primeiro Modelo Semântico**.

**Facilitadores:**

[Rômulo Jales](http://github.com/romulojales): Engenheiro da computação e aluno de mestrado pela PUC-RIO, atualmente trabalhando na globo.com como engenheiro de software para o globoesporte.com .

[Victor Pantoja](http://github.com/victorpantoja): Engenheiro eletrônico e de computação pela UFRJ e mestre em informática pela PUC-Rio, atua desde 2005 como engenheiro de software na globo.com tendo desenvolvido grandes portais como o globoesporte.com e também o fanstasy game Cartola FC.

## Descrição

Se você assistiu o debate sobre web semântica e ficou querendo mais, essa é a oportunidade! Se você ainda não assistiu, confira [aqui](http://academiatech.com.br/agenda/web-semantica-os-desafios-por-tras-da-nova-web).

Baixe os slides do workshop feito no dia 09/10/2014 [aqui](./slides/Slides-Workshop-Semantica.pdf).

Veja o vídeo do workshop [aqui](https://www.youtube.com/watch?v=Q1uB66oSMv8).

Quer trabalhar na globo.com? Acesse [aqui](https://github.com/globocom/IWantToWorkAtGloboCom).

## Resumo do conteúdo

O objetivo final desta oficina é apresentar de forma prática os conceitos de web semântica através da criação de uma ontologia que descreve Fórmula 1.

Faremos uma rápida apresentação sobre web semântica, sobre o banco de grafos Virtuoso, SPARQL e demais tecnologias relacionadas

Os desenvolvedores criarão a ontologia baseada no nosso input (domínio e dicionário de dados). A idéia e criarmos os TTLs para cada entidade e carregarmos esses TTLs no Virtuoso utilizando o simple-db-migrate.

Os TTLs serão criados aos poucos, com nosso auxílio. Os desenvolvedores irão criar as queries para inserir dados iniciais na ontologia.

A seguir, faremos consultas SPARQL no grafo que criamos no Virtuoso e explicaremos, na prática, os paradigmas dessa abordagem de programação.

Esperamos com essa oficina que os desenvolvedores saiam com vontade de utilizar semântica em suas apliações

## Pré-requisitos originais para esse workshop

1. Assistir o debate sobre web semântica [aqui](http://academiatech.com.br/agenda/web-semantica-os-desafios-por-tras-da-nova-web)
2. Levar seu notebook (nós forneceremos uma instalação do virtuoso)
3. Instalar o [Virtuoso](https://github.com/romulojales/Sua-primeira-ontologia/wiki/Virtuoso)
4. Instalar o python 2.7, ou superior, com o [pip](https://pypi.python.org/pypi/pip) instalado
5. Configurar o virtualenv. Executar no terminal:

```bash
mkdir -p ~/academiatech && cd ~/academiatech

git clone https://github.com/romulojales/Sua-primeira-ontologia
cd oficina-002

pip install virtualenvwrapper
mkvirtualenv semantica
pip install simple-virtuoso-migrate

```

