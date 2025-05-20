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
DengueMonitoring/
├── README.md
├── .gitignore
├── LICENSE
├── docs/
│   └── Relatorio_PI_III_Entrega_final_PDF.pdf
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── denguemonitoring/
│   │   │           └── App.java
│   │   └── resources/
│   │       └── config.properties
│   └── test/
│       └── java/
│           └── com/
│               └── denguemonitoring/
│                   └── AppTest.java
├── data/
│   └── sample_dataset.csv
├── assets/
│   ├── images/
│   └── animations/
├── scripts/
│   └── deploy.sh
├── requirements.txt (se for Python)
└── app-release.apk (se for Android)
# Clonar o repositório existente
git clone https://github.com/Fabiojr-gif/DengueMonitoring.git
cd DengueMonitoring

# Criar arquivos e estrutura
mkdir -p docs src/main/java/com/denguemonitoring src/main/resources src/test/java/com/denguemonitoring data assets/images assets/animations scripts
touch README.md .gitignore LICENSE

# Adicionar arquivos do projeto
cp /caminho/do/arquivo/Relatorio_PI_III_Entrega_final_PDF.pdf docs/

# Inicializar projeto Java (exemplo)
echo "public class App { public static void main(String[] args) { System.out.println(\"Dengue Monitoring iniciado!\"); } }" > src/main/java/com/denguemonitoring/App.java
echo "public class AppTest { }" > src/test/java/com/denguemonitoring/AppTest.java

# Git comandos
git add .
git commit -m "Estrutura inicial do projeto DengueMonitoring"
git push origin main
# DengueMonitoring

Aplicativo desenvolvido no âmbito do Projeto Integrador III (UNIVESP) para monitoramento de casos suspeitos de dengue.

## Estrutura
- `src/`: Código-fonte principal
- `docs/`: Documentação e relatórios
- `assets/`: Imagens e animações do app
- `data/`: Conjuntos de dados de testes
- `scripts/`: Scripts úteis

## Desenvolvedor
Fábio Fernandes Junior – Polo Dourado-SP – UNIVESP
