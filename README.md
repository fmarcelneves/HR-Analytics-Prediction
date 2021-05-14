# HR-Analytics-Prediction - PT
### Análise exploratória e preditiva de um dataset da IBM sobre rotatividade de funcionários.

Um artigo completo sobre este projeto está disponível no [Medium](https://fmarcelneves.medium.com/rh-analytics-e-machine-learning-e584635d7d87?source=friends_link&sk=7720272d4edf972c1131d51c18a457cf)

Neste projeto utilizei um dataset disponível da IBM para analisar quais empregados teriam a maior probabilidade de sair da empresa (este problema é mais comumente conhecido como churn ratio/employee turnover). O fenômeno de employee attrition, é uma gradual, mas deliberada redução no número de empregados em uma companhia ou negócio, sem processo de demissão. Isto gera um processo custoso para substituição de funcionários, novos custos com treinamento e possibilidade de perca de funcionários talentosos e treinados.

**Metodologia**
<br /> 
Primeiramente foquei em uma extensa análise exploratória de dados. Por fim, um modelo de machine learning foi selecionado (rede neural) dentre vários para prever employee attrition (utilizando o Scikit-learn e o Keras), o qual poderá auxiliar na criação de categorias de risco com base na probabilidade de um funcionário sair ou não da empresa. Como se trata de um dataset desbalanceado, uma série de métodos para lidar com esse tipo de problema foi usado, incluindo o uso de modelos que suportam técnicas para lidar com desbalanceamento de dados, tuning de hiper-parâmetros, e uso de oversampling.

<img src="https://miro.medium.com/max/766/1*-v4fo2Kq8ntIkOWaNzgpzA.png" width="540" height="480">
<br /> 
Figura de exemplo: Probabilidade de atrittion para o subconjunto de teste. entre pessoas que saíram (Attrition=1) e permaneceram na empresa (Attrition=0)

# HR-Analytics-Prediction - EN
### Exploratory and predictive analysis of an IBM dataset on employee turnover. 

A full article about this project is available in [Medium](https://fmarcelneves.medium.com/rh-analytics-e-machine-learning-e584635d7d87?source=friends_link&sk=7720272d4edf972c1131d51c18a457cf) (only in portuguese for now)

This portfolio project uses a dataset available from IBM to analyze which employees have a higher probability to get out of the company (this problem is more commonly known as churn ratio / employee turnover). The phenomenon of employee attrition is a gradual, but deliberate reduction in the number of employees in a company or business, without a proper demise process. This create a costly process for the replacement of employees, new costs with professional training and the possibility of losing talented and trained employees.

**Methodology**
<br /> 
Firstly, I made an extensive exploratory analysis of data. After that, a machine learning model was selected (neural network) among several others to forecast employee attrition (using Scikit-learn and Keras), which could assist in the creation of risk categories based on the probability of an employee to leave or not the company . Since it is an unbalanced dataset, a series of methods to deal with this type of problem was used, including the use of models which support techniques to deal with data imbalance, hyper-parameter tuning, and the use of oversampling.

<img src="https://miro.medium.com/max/766/1*-v4fo2Kq8ntIkOWaNzgpzA.png" width="540" height="480">
<br /> 
Example figure: Probabilidade de atrittion para o subconjunto de teste. entre pessoas que saíram (Attrition=1) e permaneceram na empresa (Attrition=0)
