# IA Aplicada a Processos

## 📌 Objetivo
Este projeto demonstra **como Inteligência Artificial pode otimizar processos empresariais**, criando um modelo de **Machine Learning para previsão de tempos de resposta** e exposição via **API Flask**.

## 🔹 Tecnologias Utilizadas
- **Python (Scikit-Learn, Pandas, NumPy)**: Para construção do modelo.
- **AWS Lambda**: Para execução serverless de previsões.
- **FastAPI/Flask**: Para expor o modelo como API.
- **Estatística e Inferência**: Para validação dos resultados.

## 🚀 Pipeline de Machine Learning
1. **Coleta de Dados**: Uso de dataset realista (ex: tempos de atendimento de tickets).
2. **Análise Exploratória**:
   - Distribuições estatísticas e outliers.
   - **Teste de hipóteses** para validar suposições sobre tempos médios.
3. **Feature Engineering**:
   - Seleção de variáveis mais relevantes.
   - Normalização e transformação de dados.
4. **Treinamento do Modelo**:
   - Algoritmo de **classificação** (Random Forest ou XGBoost).
   - Validação com **Cross-Validation e Matriz de Confusão**.
5. **Implementação da API**:
   - Exposição via **FastAPI/Flask**.
   - Deploy em **AWS Lambda**.

## 🛠️ Como Rodar o Projeto
### 📌 Pré-requisitos
- Python 3.8+
- FastAPI ou Flask instalado (`pip install fastapi uvicorn` ou `pip install flask`)
- AWS CLI configurado

### 📌 Configuração do Ambiente
1. **Clone o repositório:**
```sh
 git clone https://github.com/vivinfor/ai-process-optimization.git
 cd ai-process-optimization
```
2. **Crie um ambiente virtual e instale as dependências:**
```sh
 python -m venv venv
 source venv/bin/activate  # Linux/Mac
 venv\Scripts\activate  # Windows
 pip install -r requirements.txt
```
3. **Treine o modelo:**
```sh
 python train.py
```
4. **Inicie a API:**
```sh
 uvicorn api:app --reload  # Para FastAPI
 python api.py  # Para Flask
```

## 📊 Resultados e Análises
- **Métricas do modelo (acurácia, recall, F1-score).**
- **Intervalo de confiança para previsões.**
- **Teste A/B para validar impacto do modelo.**

## 🔄 Próximos Passos
- Melhorar seleção de features com **estatística inferencial**.
- Comparar diferentes algoritmos de Machine Learning.
- Criar um **front-end simples para consumir a API.**

🚀 **Desenvolvido por [Viviana]**

