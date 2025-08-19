📊 Previsão de Evasão de Clientes (Churn Prediction)
📌 Descrição do Projeto

Este projeto tem como objetivo prever a evasão de clientes em uma empresa de telecomunicações, identificando os principais fatores que influenciam a saída dos clientes.
Com base nos resultados, foram propostas estratégias de retenção para reduzir o churn e melhorar a fidelização.

O estudo foi desenvolvido como parte de um desafio de análise de dados e machine learning.

⚙️ Tecnologias Utilizadas

Python 3.x

Bibliotecas principais:

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

🧠 Modelos Treinados

Foram utilizados diferentes algoritmos de machine learning para comparar desempenho:

Regressão Logística

Acurácia: 80,38%

Recall para classe "evasão": 0,54

Melhor desempenho geral na detecção de clientes que evadiram.

Random Forest

Acurácia: 78,53%

Recall para classe "evasão": 0,48

Confirmou a relevância das variáveis mais importantes.

📊 Principais Fatores de Evasão

Contrato de curto prazo (Month-to-month): maior risco de cancelamento.

Menor tempo de contrato (tenure baixo): clientes novos têm maior chance de evasão.

Faturamento mensal elevado: clientes com contas altas tendem a cancelar mais rápido.

Ausência de serviços adicionais (Ex: TechSupport, OnlineSecurity): aumenta a evasão.

🎯 Estratégias de Retenção Recomendadas

Criar programas de fidelidade para incentivar contratos de longo prazo.

Oferecer pacotes de serviços adicionais (segurança, suporte técnico, etc.).

Realizar ofertas personalizadas para clientes de alto faturamento.

Monitorar clientes com tenure baixo e agir preventivamente com benefícios iniciais.

📌 Conclusão

A análise mostrou que os modelos conseguem prever a evasão com boa precisão.
A Regressão Logística se destacou pela interpretabilidade e equilíbrio de desempenho, enquanto o Random Forest reforçou a importância de variáveis como contrato, faturamento e tempo de permanência.

Com essas informações, a empresa pode adotar estratégias direcionadas para reduzir a evasão e aumentar a fidelidade dos clientes.
