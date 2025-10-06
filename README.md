# Machine Learning para Diagnóstico de Motores Elétricos

##  Descrição do Projeto

Este projeto aplica técnicas de Machine Learning para detectar falhas e analisar a eficiência de motores elétricos em veículos elétricos, no contexto da **Indústria 4.0** e automação industrial.

##  Objetivos

1. **Classificação (Detecção de Falhas)**: Identificar quando um motor elétrico apresenta sinais de falha ou degradação
2. **Regressão (Predição de Eficiência)**: Prever a eficiência energética do motor baseada em condições operacionais

## Dataset

- **5.000 registros** sintéticos simulando sensores de motores elétricos
- **18 variáveis** incluindo parâmetros elétricos, mecânicos e térmicos
- **3 classes de falha**: Normal, Falha Incipiente, Falha Crítica
- **Período**: 20 dias de dados simulados

### Principais Variáveis:
- Temperatura do motor (°C)
- Corrente elétrica (A) 
- Tensão de entrada (V)
- Velocidade de rotação (RPM)
- Torque aplicado (Nm)
- Vibração (m/s²)
- Tempo de operação (horas)
- Eficiência (%)

## 🤖 Modelos Implementados

### Classificação:
- Random Forest
- Gradient Boosting ⭐ (Melhor)
- SVM
- Logistic Regression

### Regressão:
- Random Forest
- Gradient Boosting ⭐ (Melhor)
- SVR
- Linear Regression

## Resultados

### Detecção de Falhas (Classificação):
- **Accuracy**: 99.9%
- **F1-Score**: 99.9% 
- **Precision**: 99.9%
- **Recall**: 99.9%

### Predição de Eficiência (Regressão):
- **R²**: 99.98%
- **RMSE**: 0.12%
- **MAE**: 0.05%
- **Erro Percentual Médio**: 0.07%

## Tecnologias Utilizadas

- **Python 3.10+**
- **Pandas** - Manipulação de dados
- **NumPy** - Operações numéricas
- **Scikit-learn** - Machine Learning
- **Matplotlib/Seaborn** - Visualização
- **Jupyter Notebook** - Desenvolvimento

## Estrutura do Projeto

```
ml-electric-motor-diagnostics/
├── motor_eletrico_diagnosticos.ipynb  # Notebook principal
├── README.md                          # Documentação
└── LICENSE                           # Licença
```

## Como Executar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/fabriciodimoraes231-rgb/ml-electric-motor-diagnostics.git
   cd ml-electric-motor-diagnostics
   ```

2. **Instale as dependências**:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter scipy
   ```

3. **Execute o notebook**:
   ```bash
   jupyter notebook motor_eletrico_diagnosticos.ipynb
   ```

## Features Mais Importantes

1. **`razao_potencia`** - Principal indicador (94% da importância)
2. **`condicao_operacional`** - Indicador composto crucial
3. **`vibracao`** - Excelente para detectar falhas mecânicas
4. **`temperatura_motor`** - Fundamental para ambos os problemas

## Aplicações Práticas

- **Manutenção Preditiva**: Detecção precoce de falhas
- **Otimização Energética**: Maximização da eficiência
- **Monitoramento Tempo Real**: Alertas automáticos
- **Redução de Custos**: Evitar paradas não programadas

## Estrutura do Notebook

1. **Contextualização e Formulação do Problema**
2. **Importação de Bibliotecas**
3. **Carregamento e Exploração dos Dados**
4. **Análise Exploratória (EDA)**
5. **Pré-processamento dos Dados**
6. **Divisão dos Dados**
7. **Modelagem de Classificação**
8. **Modelagem de Regressão**
9. **Avaliação Detalhada**
10. **Análise de Importância das Features**
11. **Otimização de Hiperparâmetros**
12. **Considerações Finais**

## Visualizações Incluídas

- Distribuições das variáveis principais
- Boxplots por status de falha
- Matriz de correlação
- Análise temporal
- Matriz de confusão
- Gráficos de predições vs valores reais
- Análise de resíduos
- Importância das features

## 🎓 Contexto Acadêmico

Este projeto foi desenvolvido como **Trabalho Prático** para a disciplina de **Inteligência Artificial para Automação**, focando na aplicação de ML no contexto da **Indústria 4.0**.

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

**Fabrício Moraes**
- GitHub: [@fabriciodimoraes231-rgb](https://github.com/fabriciodimoraes231-rgb)

---

**⚡ "A aplicação de Inteligência Artificial na indústria não é apenas uma tendência, é uma necessidade para competitividade e sustentabilidade no século XXI."**
