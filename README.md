<h3> <center> "GARBAGE IN, GARBAGE OUT" - PRÉ-PROCESSAMENTO</center> </h3>
<hr size="1" width="100%" align="center" noshade> 



<h3> SOBRE </h3>


<p align = 'JUSTIFY'> O pré-processamento envolve conhecer detalhadamente a base de dados, detectando a qualidade destes, a padronização, tipos de variáveis, transformações, tamanho da base e formas que possam colaborar para a eficiência da mineração e que se adequam à tarefa que será utilizada (SCHMITT et al., 2005). </p>

<p align = 'JUSTIFY'>Dada a importância dessa etapa, esse estudo de caso aborda pontos importantes que, caso ignorados, podem impactar negativamente na análise e interpretação - os dados de entrada precisam ser confiáveis -  pois, "Garbage in, garbage out" (lixo entra, lixo sai) - expressão atribuída ao técnico da IBM George Fuechsel. </p>


<p align = 'JUSTIFY'>Para alcançar esse objetivo, nesse estudo, foram utilizadas duas base de dados. Uma é a "Base Crédito", composta por dados sobre o pagamento de empréstimos; já outra, informa dados sobre um censo dos Estados Unidos e indicação de renda entre os participantes. Abaixo, é possível visualizar dois dos gráficos que constam nesse estudo sobre pré-processamento a fim de levantar insigths e hipóteses a respeito dos dados </p>


<img src="https://github.com/WMFrts/pre-processamento-com-pandas-e-sklearn/blob/main/gr%C3%A1ficos.jpg?raw=true">

<h3>BIBLIOTECAS/IMPORTAÇÕES</h3>


* pandas

* numpy 

* seaborn


* matplotlib.pyplot


* plotly.express

* pickle



<h3>ÍNDICE</h3>

<dl>
<dt>1 Importação das bibliotecas</dt>
<dt>2 Base de dados de crédito</dt>
<dt>3 Visualização dos dados</dt>
<dt>4 Tratamento de valores inconsistentes</dt>
<dt>5 Tratamento de valores faltantes</dt>
<dt>6 Divisão entre previsores e classe</dt>
<dt>7 Base de dados census</dt>
<dt>8 Visualização dos dados</dt>
<dt>9 Divisão entre previsores e classe</dt>
<dt>10 Atributos categóricos – LabelEncoder</dt>
<dt>11 Atributos categóricos – OneHotEncoder</dt>
<dt>12 Escalonamento de atributos</dt>
<dt>13 Bases de treinamento e teste</dt>
<dt>14 Salvar as bases de dados</dt>
</dl>


<h3>REFERÊNCIAS</h3>

<p align = 'JUSTIFY'>SCHMITT, J. et al. Pré-processamento para a mineração de dados: uso da análise de componentes principais com escalonamento ótimo. Florianópolis, SC, 2005.


<p align = 'JUSTIFY'>GARBAGE IN, GARBAGE OUT. In: WIKIPÉDIA, a enciclopédia livre. Flórida: Wikimedia Foundation, 2015. Disponível em: <a href= "https://pt.wikipedia.org/w/index.php?title=Garbage_in,_garbage_out&oldid=41413801">Garbage in, garbage out</a>. Acesso em: 19 fev. 2022.


