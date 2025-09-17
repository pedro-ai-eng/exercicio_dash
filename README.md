<div id="header" align="center">
  <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExMG9vOWxnam9jNmdmeXVxemowZWhucjNsbGNjdGx0NHZqdTdhMjVqcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/4FQMuOKR6zQRO/giphy.gif" width="200"/>
  <br/>
  <h1>
    📊 Dashboard de Análise de Agências dos Correios
    <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
  </h1>
  <h3>Análise de Variação Percentual (2005-2012)</h3>
</div>

<div id="badges" align="center">
  <a href="mailto:vieirapedroai@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge"/>
  </a>
  <a href="https://www.linkedin.com/in/masterai/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://github.com/pedro-ai-eng">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"/>
  </a>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/Data_Analysis-FF6B6B?style=for-the-badge&logo=databricks&logoColor=white" alt="Data Analysis"/>
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=pedro-ai-eng&style=flat-square&color=blueviolet" alt=""/>
</div>

---

<div align="center">
  <h2>🎯 Sobre o Projeto</h2>
  <p>Análise completa de dados das agências dos correios no estado de Goiás, comparando os números entre 2005 e 2012 e calculando a variação percentual para cada localidade.</p>
  
  <h3>📈 Principais Resultados</h3>
  <ul align="left" style="display: inline-block;">
    <li><strong>246 localidades</strong> analisadas</li>
    <li><strong>3.96%</strong> de variação média</li>
    <li><strong>75%</strong> de variação máxima</li>
    <li><strong>Goiânia</strong> com maior crescimento (56.67%)</li>
  </ul>
</div>

---

<div align="center">
  <h2>🚀 Tecnologias Utilizadas</h2>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=flat-square&logo=matplotlib&logoColor=white" alt="Matplotlib"/>
</div>

---

<div align="center">
  <h2>📊 Fórmula de Cálculo</h2>
  <code>Variação Percentual = ((2012 - 2005) / 2012) × 100</code>
</div>

---

<div align="center">
  <h2>🔗 Links Úteis</h2>
  <a href="#-como-executar">📖 Documentação</a> •
  <a href="#-estrutura-do-projeto">📁 Estrutura</a> •
  <a href="#-resultados-da-análise">📈 Resultados</a> •
  <a href="#-contribuições">🤝 Contribuir</a>
</div>

---

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
