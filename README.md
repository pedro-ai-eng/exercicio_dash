# Dashboard de Análise de Agências dos Correios (2005-2012)

Este projeto analisa dados sobre agências dos correios no estado de Goiás, comparando os números entre 2005 e 2012, e calcula a variação percentual entre esses períodos.

## 📊 Descrição do Projeto

O dashboard processa dados de agências dos correios próprias, calculando a variação percentual entre 2005 e 2012 para cada localidade, utilizando a fórmula:

```
Variação Percentual = ((2012 - 2005) / 2012) × 100
```

## 🚀 Funcionalidades

- **Carregamento de Dados**: Leitura do arquivo CSV com dados das agências
- **Limpeza de Dados**: Conversão de tipos e tratamento de valores ausentes
- **Cálculo de Variação**: Implementação da fórmula de variação percentual
- **Análise Estatística**: Estatísticas descritivas da variação
- **Visualização de Resultados**: Exibição de dados e exemplos significativos

## 📁 Estrutura do Projeto

```
DASH/
├── dashboard_app.py              # Script principal
├── agencias_correios_2005_2012.csv  # Dados das agências
└── README.md                     # Este arquivo
```

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas**: Manipulação e análise de dados
- **Streamlit**: Framework para criação de dashboards (importado mas não utilizado no script atual)
- **Matplotlib**: Biblioteca para criação de gráficos (importada mas não utilizada no script atual)

## 📋 Pré-requisitos

Certifique-se de ter as seguintes bibliotecas instaladas:

```bash
pip install pandas streamlit matplotlib
```

## 🎯 Como Executar

1. Clone ou baixe o projeto
2. Certifique-se de que o arquivo `agencias_correios_2005_2012.csv` está no mesmo diretório
3. Execute o script:

```bash
python dashboard_app.py
```

## 📈 Resultados da Análise

### Estatísticas Gerais
- **Total de registros**: 246 localidades
- **Variação média**: 3.96%
- **Variação máxima**: 75.00%
- **Variação mínima**: 0.00%

### Exemplos de Variações Significativas
- **Goiânia**: 56.67% de aumento (13 → 30 agências)
- **Catalão**: 66.67% de aumento (1 → 3 agências)
- **Anápolis**: 60.00% de aumento (2 → 5 agências)

## 🔍 Estrutura dos Dados

O arquivo CSV contém as seguintes colunas:
- **Localidade**: Nome da cidade/município
- **Variável**: Tipo de agência (Agência de Correios Próprias)
- **2005**: Número de agências em 2005
- **2012**: Número de agências em 2012
- **Variação_Percentual_%**: Nova coluna calculada com a variação percentual

## ⚙️ Processamento de Dados

1. **Carregamento**: Leitura do CSV com encoding UTF-8
2. **Limpeza**: Substituição de valores " -   " por "0"
3. **Conversão**: Transformação de strings para valores numéricos
4. **Cálculo**: Aplicação da fórmula de variação percentual
5. **Tratamento**: Correção de valores infinitos e NaN

## 📊 Interpretação dos Resultados

- **0%**: Número de agências manteve-se igual entre 2005 e 2012
- **Valores positivos**: Aumento no número de agências
- **Valores negativos**: Diminuição no número de agências (não observado nos dados)

## 🔧 Personalização

Para modificar a análise, você pode:
- Alterar a fórmula de cálculo na linha 36
- Ajustar o número de casas decimais no arredondamento
- Modificar os filtros para variações significativas
- Adicionar novas métricas estatísticas

## 📝 Notas Importantes

- O script trata automaticamente valores ausentes (NaN) e infinitos
- A maioria das localidades manteve o mesmo número de agências
- As maiores variações ocorreram em cidades de maior porte
- Os dados são específicos do estado de Goiás

## 🤝 Contribuições

Sinta-se à vontade para contribuir com melhorias, correções ou novas funcionalidades ao projeto.

## 📄 Licença

Este projeto é destinado a fins educacionais e de análise de dados.
