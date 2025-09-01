# Projeto de Análise de Dados de Consumidores de Energia

## Integrantes 

* **Nathan Magno Gustavo Cônsolo  558987**
* **Júlio Cesar Nunes  557774**
* **Nathalia Gomes da Silva  554945**
* **Luiz Paulo Freitas Fernandes  555497**

##  Requisitos

1. Carregue o dataset e exiba as 10 primeiras linhas.

2. Explique a diferença entre as variáveis Global_active_power e Global_reactive_power.

3. Verifique se existem valores ausentes no dataset. Quantifique-os.

4. Converta a coluna Date para o tipo datetime e crie uma nova coluna com o dia da semana 
correspondente.

5. Filtre os registros apenas do ano de 2007 e calcule a média de consumo diário de 
Global_active_power.

6. Gere um gráfico de linha mostrando a variação de Global_active_power em um único dia à 
sua escolha.

7. Crie um histograma da variável Voltage. O que pode ser observado sobre sua distribuição?

8. Calcule o consumo médio por mês em todo o período disponível no dataset.

9. Identifique o dia com maior consumo de energia ativa global (Global_active_power).

10. Compare o consumo médio de energia ativa global em dias de semana versus finais de 
semana.

11. Calcule a correlação entre as variáveis Global_active_power, Global_reactive_power, 
Voltage e Global_intensity.

12. Crie uma nova variável chamada Total_Sub_metering que some Sub_metering_1, 
Sub_metering_2 e Sub_metering_3.

13. Verifique se há algum mês em que Total_Sub_metering ultrapassa a média de 
Global_active_power.

14. Faça um gráfico de série temporal do Voltage para o ano de 2008.

15. Compare o consumo entre os meses de verão e inverno (no hemisfério norte).

16. Aplique uma amostragem aleatória de 1% dos dados e verifique se a distribuição de 
Global_active_power é semelhante à da base completa.

17. Utilize uma técnica de normalização (Min-Max Scaling) para padronizar as variáveis 
numéricas principais.

18. Aplique K-means para segmentar os dias em 3 grupos distintos de consumo elétrico. 
Interprete os resultados.

19. Realize uma decomposição de série temporal (tendência, sazonalidade e resíduo) para 
Global_active_power em um período de 6 meses.

20. Treine um modelo de regressão linear simples para prever Global_active_power a partir de 
Global_intensity. Avalie o erro do modelo.

## DataSets utilizados


**Appliances Energy Prediction:** https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction

**Informações:** O conjunto de dados está com intervalos de 10 minutos por cerca de 4,5 meses. A temperatura e as condições de umidade da casa foram monitoradas com uma rede de sensores sem fio ZigBee. Cada nó sem fio transmitia as condições de temperatura e umidade a cada 3,3 minutos. Em seguida, os dados sem fio foram calculados em média para períodos de 10 minutos. Os dados de energia foram registrados a cada 10 minutos com medidores de energia m-bus. As condições climáticas da estação meteorológica do aeroporto mais próximo (Aeroporto de Chievres, Bélgica) foram baixadas de um conjunto de dados público da Reliable Prognosis (rp5.ru) e combinadas juntamente com os conjuntos de dados experimentais usando a coluna de data e hora. Duas variáveis aleatórias foram incluídas no conjunto de dados para testar os modelos de regressão e filtrar atributos (parâmetros) não preditivos.

**Individual Household Electric Power Consumption:** https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption

**Informações:** Este arquivo contém 2.075.259 medições coletadas em uma casa localizada em Sceaux (7 km de Paris, França) entre dezembro de 2006 e novembro de 2010 (47 meses). Notas: 1. (global_active_power*1000/60 - sub_metering_1 - sub_metering_2 - sub_metering_3) representa a energia ativa consumida a cada minuto (em watt-hora) na residência por equipamentos elétricos não medidos nas sub-medições 1, 2 e 3. 2. O conjunto de dados contém alguns valores ausentes nas medições (quase 1,25% das linhas). Todos os timestamps de calendário estão presentes no conjunto de dados, mas para alguns timestamps, os valores de medição estão ausentes: um valor ausente é representado pela ausência de valor entre dois separadores de atributos de ponto e vírgula consecutivos. Por exemplo, o conjunto de dados mostra valores ausentes em 28 de abril de 2007.
