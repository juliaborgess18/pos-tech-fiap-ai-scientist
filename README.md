# Projetos Pós-Tech FIAP 

Este repositório centraliza os desafios e projetos desenvolvidos durante a pós-graduação em **AI Science** na FIAP. Cada projeto está organizado para demonstrar a aplicação de técnicas de Ciência de Dados e Inteligência Artificial em problemas reais de negócio.

---

## Estrutura do Repositório

O projeto segue uma estrutura padronizada para garantir a reprodutibilidade e organização dos artefatos de Data Science:

``` text
├── data/              <- Armazenamento de dados (raw, interim, processed, external).
├── docs/              <- Documentação técnica do projeto.
├── models/            <- Modelos treinados ou sumários de performance.
├── notebooks/         <- Jupyter notebooks organizados:
│   └── 1.0-jbs-eda.ipynb  <- Análise Exploratória e Diagnóstico do Case NPS Preditivo.
│       ├── Objetivo: Entender o impacto logístico/atendimento no NPS e identificar o ponto de ruptura.
│       └── Descobertas: Correlação de -0.60 com atraso; queda de 39.4% no 5º dia de delay.
├── projetos_pos_tech_fiap/ <- Código-fonte (Módulo Python do projeto).
├── references/        <- Dicionários de dados e materiais explicativos.
├── reports/           <- Análises geradas (HTML, PDF) e pastas de figuras.
│   └── 1.0-jbs-eda_files/ <- Pasta com arquivos para gerar o html dos reports utilizando Quarto.
│   └── figures/ <- Pasta auxiliar para imagens dos reports.
│   └── 1.0-jbs-eda.html  <- Report gerado pelo Quarto do notebook 1.0-jbs-eda.ipynb em HTML.
│   └── 1.0-jbs-eda.pdf   <- Report gerado pelo Quarto do notebook 1.0-jbs-eda.ipynb em PDF.
├── .env               <- Variáveis de ambiente (credenciais, caminhos locais).
├── .gitignore         <- Arquivos e pastas ignorados pelo Git (ex: data/ e .env).
├── Makefile           <- Comandos de conveniência (ex: `make data` ou `make train`).
├── pyproject.toml     <- Configurações de metadados e ferramentas de build.
├── README.md          <- Documentação principal do repositório.
└── requirements.txt   <- Bibliotecas necessárias para reproduzir o ambiente.
```
---

## Como Reproduzir as Análises

### Pré-requisitos
* Python 3.8+
* Pandas, Seaborn e Matplotlib

### Passo a Passo

1.  **Clonar o repositório:**
    ``` bash
    git clone https://github.com/seu-usuario/projetos_pos_tech_fiap.git
    cd projetos_pos_tech_fiap
    ```

2.  **Instalar as dependências:**
    ```bash
    pip install -r 'requirements.txt'
    ```

3.  **Executar o Notebook:**
    Navegue até a pasta `/notebooks` e abra o notebook de interesse em seu ambiente Jupyter ou VS Code para visualizar os gráficos construídos.

---

**Autor:** Júlia Borges Santos (JBS)

**Curso:** Pós-Graduação em AI Science - FIAP