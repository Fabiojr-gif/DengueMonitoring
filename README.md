# DengueMonitoring
Aplicativo para acompanhamento de suspeitos de dengue- Projeto Integrador UNIVESP
denguemonitoring/
├── README.md
├── frontend/
│   └── index.html
├── database/
│   └── estrutura.sql
└── relatorio/
    └── Relatorio_PI_UNIVESP.pdf
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>DengueMonitoring - UNIVESP</title>
</head>
<body>
  <h1>Projeto Integrador UNIVESP</h1>
  <p>Aplicativo para monitoramento de pacientes com suspeita de dengue.</p>
</body>
</html>
CREATE TABLE pacientes (
  id INTEGER PRIMARY KEY,
  nome TEXT NOT NULL,
  idade INTEGER,
  sintomas TEXT
);
# DengueMonitoring - UNIVESP

Este repositório contém o Projeto Integrador do curso de Bacharelado em Tecnologia da Informação da UNIVESP (Polo Dourado-SP).

## Objetivo

Desenvolver um aplicativo web para monitoramento de pacientes com suspeita de dengue, permitindo o cadastro, análise de sintomas e geração de relatórios para equipes de saúde.

## Estrutura

- `/frontend`: interface HTML simples
- `/database`: estrutura do banco de dados
- `/relatorio`: PDF do relatório final enviado à UNIVESP
