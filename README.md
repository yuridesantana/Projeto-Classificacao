# Projeto-Classificacao
 Projeto de Classificação na área da Saúde
 
O objetivo principal deste projeto é prever a presença ou ausência de doença cardiovascular com base em diversas variáveis do paciente.

Dicionário dos dados:

ID: identificador de cada paciente.

age: Idade do paciente em dias.

age_years: Idade do paciente em anos

gender: sexo do paciente. Variável categórica (1: Feminino, 2: Masculino).

height: Altura do paciente em centímetros.

weight: Peso do paciente em quilogramas.

ap_hi: Pressão arterial sistólica.

ap_lo: Pressão arterial diastólica.

cholesterol: Níveis de colesterol. Variável categórica (1: Normal, 2: Acima da Média, 3: Bem Acima da Média).

gluc: Níveis de glicose. Variável categórica (1: Normal, 2: Acima da Média, 3: Bem Acima da Média).

smoke: Perfil dos participantes quanto ao fumo. Variável binária (0: Não fumante, 1: Fumante).

alco: Perfil dos participantes quanto ao álcool. Variável binária (0: Não consome álcool, 1: Consome álcool).

active: Perfil dos participantes quanto à atividade física. Variável binária (0: Não fisicamente ativo, 1: Fisicamente ativo).

cardio: Presença ou ausência de doença cardiovascular. Variável de destino. Binário (0: Ausência, 1: Presença).

bmi: Índice de Massa Corporal (IMC), derivado do peso e altura.

bp_category: Categoria de pressão arterial baseada em ap_hi e ap_lo. As categorias incluem "Normal", "Elevado", "Estágio de Hipertensão 1", "Estágio de Hipertensão 2" e "Crise Hipertensiva".

bp_category_encoded: forma codificada de bp_category para fins de aprendizado de máquina.

Referência: O banco de dados foi coletado a partir de: https://www.kaggle.com/datasets/colewelkins/cardiovascular-disease
