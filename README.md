# ADAL-IA

# ADAL-IA - Auxiliar de Análise de Logs com Inteligência Artificial

O ADAL-IA é uma aplicação Python que utiliza Inteligência Artificial (IA) para auxiliar na análise de logs, facilitando a identificação de erros, a determinação da causa raiz e a geração de insights acionáveis para a resolução de problemas em diferentes tipos de aplicações.

## Funcionalidades (Planejadas)

* **Processamento de Logs Genérico:** Suporte a diversos formatos de log com detecção automática e configuração personalizada.
* **Análise Inteligente de Erros:** Identificação, classificação e análise da causa raiz de erros usando algoritmos de IA.
* **Base de Conhecimento Inteligente:** Base de conhecimento dinâmica, alimentada pelos modelos de IA, para aprimorar a análise.
* **Geração de Relatórios e Micro Tasks:** Relatórios detalhados com informações sobre os erros, incluindo impacto, causa raiz e micro tarefas para verificação.
* **Interface Gráfica Intuitiva:** Interface para configuração, visualização de resultados e interação com os modelos.
* **Pré-processamento de Dados:** Limpeza, normalização e transformação dos dados dos logs para uso nos modelos.
* **Modelos de IA Treinados:**  Salvar e carregar modelos treinados para diferentes tipos de logs e cenários.

## Tecnologias

* Python 3.x
* Tkinter (interface gráfica)
* Bibliotecas de IA: TensorFlow/PyTorch/Scikit-learn (a definir)
* Bibliotecas de Processamento de Dados: Pandas, NumPy
* Bibliotecas de PNL: spaCy/NLTK (se necessário)

## Instalação

1. Clone o repositório: `git clone https://github.com/ss01074/ADAL.git`
2. Navegue até a pasta: `cd ADAL-IA`
3. Crie um ambiente virtual: `python3 -m venv .venv`
4. Ative o ambiente:
    * Linux/macOS: `source .venv/bin/activate`
    * Windows: `.venv\Scripts\activate`
5. Instale as dependências: `pip install -r requirements.txt`

## Uso

(Instruções de uso, considerando as novas funcionalidades de IA.  **Complete esta seção com os comandos e passos necessários para usar o ADAL-IA.**)

## Executando os Testes

```bash
pytest

Contribuição
Contribuições são bem-vindas! Siga as instruções no arquivo CONTRIBUTING.md

Licença
Este projeto é licenciado sob a licença Gratuito para Uso Não Comercial. Para uso comercial, entre em contato com o autor. 

Contato
Samuel Pedroso dos Santos - sps04028701074@outlook.com

Estrutura-do-Projeto

adal-ia/
├── adal_ia.py             # Arquivo principal
├── utils/                # Funções utilitárias
│   ├── log_parser.py     # Parsing de logs
│   ├── ai_utils.py       # Funções auxiliares para IA
│   └── data_preprocessing.py # Pré-processamento de dados
├── data/                 # Dados e base de conhecimento
│   ├── logs_exemplo/    # Arquivos de log de exemplo
│   ├── datasets/        # Datasets para treinamento
│   └── knowledge_base.json# Base de conhecimento
├── models/               # Modelos de IA treinados
├── gui/                  # Interface gráfica
│   └── main_window.py   # Janela principal
├── tests/                # Testes unitários
│   ├── test_log_parser.py  # Testes para log_parser
│   ├── test_ai_utils.py    # Testes para ai_utils
│   └── test_data_preprocessing.py # Testes para pré-processamento
├── config.py             # Arquivo de configuração
├── pyproject.toml        # Configurações do projeto
├── requirements.txt      # Dependências do projeto
├── ROADMAP.md            # Roadmap do projeto
├── LICENSE               # Arquivo de licença
└── CONTRIBUTING.md       # Guia de contribuição (opcional)
