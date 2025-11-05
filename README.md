Este script realiza a leitura de um arquivo CSV contendo movimentações financeiras, unifica colunas duplicadas e gera um resumo financeiro consolidado com o total de créditos, débitos e saldo final. Ele foi projetado para auxiliar na validação de conciliações bancárias ou divergências entre sistemas de pagamento.

# 📊 Calcular Resumo Financeiro

Este script lê um arquivo CSV contendo dados de transações financeiras e calcula um **resumo detalhado** com o total de créditos, débitos e o saldo final.

## 🚀 Funcionalidades
- Leitura de arquivos CSV com separador configurável.
- Unificação automática de colunas `_x` e `_y`.
- Conversão de valores para formato numérico.
- Cálculo de totais de **créditos (CRDT/C)** e **débitos (DBIT/D)**.
- Exibição formatada dos resultados no console.

## ⚙️ Configuração
Edite as variáveis no início do script:
```python
arquivo_para_calcular = 'divergencias.csv'
separador_csv = ';'

▶️ Como usar
python calcular_resumo_financeiro.py

🧩 Dependências

Python 3.x

pandas

numpy

Instalação:

pip install pandas numpy

🧠 Autor

Desenvolvido por Vinicius Costa de Paula
