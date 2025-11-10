# e-Commerce_Analysis
Análise Gerencial sobre os dados da da pesquisa.
Relatório de E-commerce 
Samuel Felipe dos Santos Mendes  


<h1> Contextualização </h1> 

<p> Este relatório tem como objetivo realizar uma análise estatística e gráfica de uma pesquisa de e-commerce. Dentro dessa análise, há algumas análises gráficas entre algumas variáveis independes e algumas entre a dependente e independente. Uma análise de correlação em duas formas diferentes, e duas análises de regressão, uma simples e uma múltipla.  

A amostra contém 86 observações e diversas variáveis demográficas e comportamentais. 
</p>
 

<h2> Gráficos - Interações entre Variáveis </h2>
<h3> Matriz de Correlação	</h3>	 
<img width="674" height="499" alt="{6160AECD-5D1F-44D2-B97D-F88F1D0435B6}" src="https://github.com/user-attachments/assets/5871a826-01e2-43bb-8767-0a0b97f8577c" />
<p>Heatmap de uma matriz de correlação de todas as variaveis e sua influencia entre si</p>

<h3> Dispositivos mais utilizados </h3>
Gráfico de barras
<img width="543" height="373" alt="{6C0CA3BC-F6BB-44A4-8B9F-5FC06C54AC30}" src="https://github.com/user-attachments/assets/15038bf0-8c14-406c-8d04-191a644429d3" />
<p>Computador; 2) Celular; 3) Tablet; 4) Outros<p> 

<h3> Distribuição de Renda </h3> 
Distribuição de Renda Mensal 
<img width="574" height="368" alt="{2A5EC8D9-3910-412A-9CD0-5EEA1E0C7C00}" src="https://github.com/user-attachments/assets/f4c447bd-0cb7-4263-8569-0d48a5ac2ad5" />

 

 

 

Distribuição de Uso de Dispositivo para compra 

 

Tabela – Estatística descritiva e análise de correlação  

Análise de correlação  

  

idade 

sexo 

renda 

gasto_medio 

frequencia 

device 

influencia 

satisfacao 

compara_precos 

seguranca 

sustentabilidade 

criterio 

idade 

1.00 

0.33 

0.49 

0.02 

-0.13 

-0.24 

0.22 

-0.09 

-0.10 

0.05 

0.15 

0.21 

sexo 

0.33 

1.00 

0.29 

-0.10 

0.03 

-0.27 

0.02 

-0.05 

0.06 

0.13 

-0.02 

-0.04 

renda 

0.49 

0.29 

1.00 

0.15 

-0.02 

-0.29 

-0.06 

-0.09 

-0.10 

0.09 

-0.07 

0.06 

gasto_medio 

0.02 

-0.10 

0.15 

1.00 

-0.07 

0.03 

-0.01 

-0.02 

0.15 

0.02 

-0.14 

-0.05 

frequencia 

-0.13 

0.03 

-0.02 

-0.07 

1.00 

0.16 

0.05 

0.10 

0.15 

-0.17 

0.03 

0.02 

device 

-0.24 

-0.27 

-0.29 

0.03 

0.16 

1.00 

-0.16 

0.15 

0.24 

-0.09 

0.09 

-0.03 

influencia 

0.22 

0.02 

-0.06 

-0.01 

0.05 

-0.16 

1.00 

-0.02 

-0.19 

-0.12 

0.18 

0.22 

satisfacao 

-0.09 

-0.05 

-0.09 

-0.02 

0.10 

0.15 

-0.02 

1.00 

0.09 

0.36 

-0.02 

0.08 

facilidade_navegacao 

-0.22 

-0.16 

-0.13 

0.01 

-0.25 

0.21 

-0.10 

0.08 

0.12 

0.10 

-0.13 

-0.04 

compara_precos 

-0.10 

0.06 

-0.10 

0.15 

0.15 

0.24 

-0.19 

0.09 

1.00 

0.09 

0.07 

0.05 

seguranca 

0.05 

0.13 

0.09 

0.02 

-0.17 

-0.09 

-0.12 

0.36 

0.09 

1.00 

0.04 

0.05 

sustentabilidade 

0.15 

-0.02 

-0.07 

-0.14 

0.03 

0.09 

0.18 

-0.02 

0.07 

0.04 

1.00 

0.45 

criterio 

0.21 

-0.04 

0.06 

-0.05 

0.02 

-0.03 

0.22 

0.08 

0.05 

0.05 

0.45 

1.00 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

Estatística descritiva 

Variável 

count 

mean 

std 

min 

25% 

50% 

75% 

max 

idade 

86 

47.07 

14.61 

18.00 

39.50 

54.50 

57.00 

67.00 

sexo 

86 

1.50 

0.50 

1.00 

1.00 

1.50 

2.00 

2.00 

renda 

86 

3.29 

1.00 

1.00 

3.00 

4.00 

4.00 

4.00 

gasto_medio 

86 

683.02 

1707.75 

20.00 

100.00 

250.00 

500.00 

15000.00 

frequencia 

86 

3.72 

1.47 

1.00 

3.00 

3.00 

5.00 

6.00 

dispostivo 

86 

2.66 

0.82 

1.00 

2.00 

2.00 

3.00 

4.00 

influencia 

86 

1.43 

0.50 

1.00 

1.00 

1.00 

2.00 

2.00 

satisfacao 

86 

3.99 

0.74 

2.00 

4.00 

4.00 

4.00 

5.00 

compara_precos 

86 

4.34 

0.94 

1.00 

4.00 

5.00 

5.00 

5.00 

seguranca 

86 

2.87 

1.20 

1.00 

2.00 

3.00 

4.00 

5.00 

sustentabilidade 

86 

3.28 

1.13 

1.00 

3.00 

3.00 

4.00 

5.00 

criterio 

86 

2.74 

1.84 

1.00 

2.00 

2.00 

3.75 

9.00 

 

 

 

 

Análise de Regressão 

Regressão Simples 

Entre o target (Gasto Médio) e a renda. 

Tabela

O conteúdo gerado por IA pode estar incorreto., 

 

Regressão Multipla 

Entre o target (Gasto Médio) e as outras variáveis que foram escolhidas. 

Tabela

O conteúdo gerado por IA pode estar incorreto.  

 

Conclusão e Insights 

Com base nas análises realizadas, observa-se que itens como facilidade de navegação, percepção de segurança e hábitos de comparação de preços apresentam associação com a satisfação do consumidor em compras online. Recomenda-se ao e-commerce investir em melhorias na usabilidade do site, garantias claras de segurança e estratégias de preço competitivas. Análises adicionais com modelos categóricos e amostras maiores podem fortalecer as conclusões. 
