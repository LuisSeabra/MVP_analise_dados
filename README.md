MVP de Luis Antonio Moreira Seabra

Este trabalho se propõe a analisar um conjunto de dados médicos, chamado "Heart Disease Dataset" o qual é um conjunto de dados disponível no Kaggle que contendo informações relacionadas a fatores de risco e diagnóstico de doenças cardíacas. Esse conjunto de dados é amplamente utilizado em estudos e análises na área de saúde e ciência de dados. Abaixo estão algumas das variáveis comuns analisadas nesses conjuntos de dados:

Idade: A idade do paciente em anos. A idade é um fator importante na avaliação do risco de doença cardíaca, pois o risco aumenta com a idade.

Sexo: O sexo do paciente, geralmente codificado como masculino (1) ou feminino (0). O sexo pode ser um fator de risco para doenças cardíacas, com os homens tendo um risco geralmente mais elevado do que as mulheres.

Pressão arterial: A pressão arterial do paciente, muitas vezes dividida em duas medidas: pressão arterial sistólica (pressão máxima durante uma batida cardíaca) e pressão arterial diastólica (pressão mínima entre as batidas cardíacas). A pressão arterial elevada é um fator de risco para doenças cardíacas.

Colesterol: Os níveis de colesterol no sangue do paciente, geralmente divididos em colesterol total, colesterol HDL (lipoproteína de alta densidade, conhecida como "colesterol bom") e colesterol LDL (lipoproteína de baixa densidade, conhecida como "colesterol ruim"). Níveis elevados de colesterol LDL e baixos níveis de colesterol HDL estão associados a um maior risco de doença cardíaca.

Açúcar no sangue em jejum (Fasting Blood Sugar - FBS): O nível de glicose no sangue do paciente após um período de jejum. Níveis elevados de açúcar no sangue estão associados a um maior risco de diabetes, que por sua vez é um fator de risco para doenças cardíacas.

Eletrocardiograma (ECG): Resultados de testes de ECG, que podem indicar anormalidades na atividade elétrica do coração. Anormalidades no ECG podem ser indicativas de problemas cardíacos.

Angina induzida por exercício: Um tipo específico de dor no peito que ocorre durante atividade física ou estresse. A angina é um sintoma comum de doença cardíaca.

Capacidade de exercício: A capacidade do paciente para realizar atividade física, muitas vezes Para a execução do trabalho, iremos importar as "ferramentas" necessárias para trabalhar os dados e fazer análises gráficas e por meio de algorítmos, utilizando-se de validação cruzada para obatrobter as métricas necessárias para comparação dos mesmos.

O "Heart Disease Dataset" do Kaggle contém as seguintes variáveis:

Age: Idade do paciente;

Sex: Gênero do paciente (1 = masculino, 0 = feminino);

CP (Chest Pain Type): Tipo de dor no peito (com quatro valores categóricos);

Trestbps: Pressão arterial em repouso (em mm Hg);

Chol: Colesterol sérico (em mg/dl);

Fbs: Glicose em jejum (1 se fbs > 120 mg/dl, 0 caso contrário);

Restecg: Resultados do eletrocardiograma em repouso (com três valores categóricos);

Thalach: Frequência cardíaca máxima alcançada;

Exang: Angina induzida por exercício (1 = sim, 0 = não);

Oldpeak: Depressão do ST induzida por exercício em relação ao repouso;

Slope: Inclinação do segmento ST durante o pico de exercício;

Ca: Número de vasos principais (0-3) coloridos por fluoroscopia;

Thal: Defeito fixo ou reversível;

Target: Variável alvo, indicando a presença de doença cardíaca (1 = doença, 0 = sem doença).
