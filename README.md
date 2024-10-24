# Projeto de Banco de Dados para Gerenciamento de Conteúdo de Vídeos

Este projeto é um sistema de gerenciamento de um serviço de streaming de vídeos, desenvolvido utilizando **MySQL**. O banco de dados modela as principais entidades envolvidas em um serviço de vídeo, incluindo clientes, catálogos de filmes e séries, atores, idiomas, faixas etárias, métodos de pagamento e muito mais.

## Funcionalidades

O sistema oferece as seguintes funcionalidades:

- **Gerenciamento de Catálogo**: Tabelas para filmes, séries, temporadas e episódios com informações detalhadas sobre elenco, idioma e restrições de faixa etária.
- **Controle de Clientes**: Armazena dados de clientes, planos, métodos de pagamento e informações de perfil para personalização.
- **Pagamentos**: Histórico de pagamentos, incluindo formas de pagamento, cartões de crédito e valores associados.
- **Informações de Funcionários**: Registra informações de funcionários da empresa, incluindo salários, fotos e datas de demissão.

## Estrutura do Banco de Dados

O banco de dados inclui as seguintes tabelas principais:

- `tb_plano`: Planos disponíveis para os clientes com valores e descrições.
- `tb_funcionario`: Informações dos funcionários da empresa.
- `tb_cartao_credito`: Detalhes dos cartões de crédito dos clientes.
- `tb_cliente`: Informações dos clientes, como CPF e plano.
- `tb_pagamento`: Histórico de pagamentos realizados pelos clientes.
- `tb_perfil`: Perfis associados aos clientes, usados para customização.
- `tb_catalogo`: Detalhes sobre filmes e séries disponíveis no catálogo, incluindo sinopse, duração, país de origem e faixas etárias.
- `tb_ator`: Informações dos atores que participam das produções.
- `tb_idioma`: Idiomas disponíveis para o catálogo de vídeos.
- `tb_categoria`: Categorias dos vídeos no sistema, como gêneros.
- `tb_episodio`: Detalhes dos episódios de séries.
- `tb_serie`: Detalhes das séries e suas temporadas.

## Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/kaiolucas8741/DBnetflix.git
