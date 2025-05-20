# Sistema de Emissão de Faturas com Flask

Este projeto é uma aplicação web desenvolvida em Flask para gerenciar a emissão e envio de faturas (notas fiscais) para pedidos de clientes.  

## Funcionalidades

- Registrar pedidos com informações de cliente e valor.
- Gerar notas fiscais nos formatos PDF e XML (simulados como arquivos texto).
- Armazenar as informações das faturas vinculadas aos pedidos.
- Consultar o histórico de pedidos realizados.
- Visualizar os arquivos gerados da nota fiscal.
- Enviar as notas fiscais por e-mail (simulado).
- Testes automatizados para validar o funcionamento das rotas principais.

## Tecnologias Utilizadas

- Python 3
- Flask
- Flask-SQLAlchemy (SQLite)
- Unittest (para testes)

## Como Rodar o Projeto

1. Clone o repositório:

```bash
git clone <url-do-repositorio>
cd <nome-da-pasta>
