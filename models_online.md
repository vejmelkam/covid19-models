# Models online

## English language

| Penn Medicine hospital model  | |
|----|----|
| Language | English |
| Links  | [web](https://penn-chime.phl.io/), [code](https://github.com/pennsignals/chime) |
| Presentation | interactive streamlit web app |
| Model focus | pressure analysis for hospital |
| Geographical scope | USA regions/hospital catchment areas |
| Data         |  |
| Uncertainty Quantification | None, deterministic simulation |
| Notes | |


| Epidemic calculator  | Gabriel Goh (OpenAI) |
|----|----|
| Language | English |
| Links  | [web](https://gabgoh.github.io/COVID/index.html), [code](https://github.com/gabgoh/epcalc) |
| Presentation | fully interactive model, running in browser |
| Model focus | deterministic SEIR, hospitalized+fatal compartment |
| Geographical scope | USA |
| Data         | parameters in papers on website |
| Uncertainty Quantification | None |
| Notes | |


| Neher lab | University of Basel |
| ------ | ----- |
| Language | English |
| Links | [web](https://neherlab.org/covid19), [code](https://github.com/neherlab/covid19_scenarios), [model info](https://neherlab.org/covid19/about)|
| Presentation | Fully interactive model, running in browser |
| Model focus  | SIR, age group segmentation, hospital + ICU stress, single spatial compartment |
| Geographical scope | Country/City |
| Data | age distributions, healthcare capacity [github](https://github.com/neherlab/covid19_scenarios_data) |
| Uncertainty quantification | support for Poisson sampling during state computation |


| Dr Richard Hsu | National Taiwan University |
|----|----|
| Language | English |
| Links  | [web](https://geneonline.news/en/2020/03/14/prediction-of-the-covid-19-outbreak-in-south-korea-and-italy/) |
| Presentation | article, static web page|
| Model focus | simplified SIR model |
| Geographical scope | Italy, South Korea |
| Data         | cases in Italy, SK|
| Uncertainty Quantification | None found |
| Notes | |


| COVID act now | |
|----|----|
| Language | English |
| Links  | [web](https://covidactnow.org/), [code](https://docs.google.com/spreadsheets/d/1YEj4Vr6lG1jQ1R3LG6frijJYNynKcgTjzo2n0FsBwZA/edit#gid=1579455912) |
| Presentation | static web page, code in google sheet |
| Model focus | healthcare overload modelling, decision making |
| Geographical scope | USA |
| Data         |  population, case data, [link](https://docs.google.com/spreadsheets/d/1YEj4Vr6lG1jQ1R3LG6frijJYNynKcgTjzo2n0FsBwZA/edit#gid=1583111774) |
| Uncertainty Quantification | ?? |
| Notes | |


| Delphi group | Carnegie Mellon University |
|----|----|
| Language | English |
| Links  | [web](https://delphi.cmu.edu/) |
| Presentation | ?? |
| Model focus | ?? |
| Geographical scope | ?? |
| Data         | ?? |
| Uncertainty Quantification | ?? |
| Notes | Announced but not yet online, related [paper](https://delphi.cmu.edu/files/brooks2015.pdf)|

| CovidSIM  | ExploSYS GmbH |
|----|----|
| Language | English |
| Links  | [web](http://covidsim.eu/), [code](https://gitlab.com/exploratory-systems/covidsim/) |
| Presentation | interactive web page, no code links |
| Model focus | Pandemic Preparedness Planning |
| Geographical scope | Not specified, single compartment model |
| Data         | Epidemiological findings, user input |
| Uncertainty Quantification | None found |
| Notes | Developed in cooperation with Landgesundheitsamt (State health authority) Stuttgart |


| Alphamoon.ai  | |
|----|----|
| Language | English |
| Links  | [web](https://alphamoon.ai/blog/2020/03/24/how-to-predict-the-future-of-sars-cov-2-pandemic/), [code]() |
| Presentation | web scenarios, not interactive |
| Model focus | extended SEIR with asymptomatic class, mitigation analysis |
| Geographical scope | Poland |
| Data         | Poland case data |
| Uncertainty Quantification | Approximate Bayesian Computation  |
| Notes | |


| EpidemicForecasting.org | |
|----|----|
| Language | English |
| Links  | [web](http://epidemicforecasting.org/) |
| Presentation | web scenarios, interactive |
| Model focus | mitigation analysis focusing on specific containment measures |
| Geographical scope | per country |
| Data         | aggreggated data |
| Uncertainty Quantification | multiple GLEAMviz simulations with predefined parameters |
| Notes | working with epidemiologists across many countries |


| covid19dashboards  | |
|----|----|
| Language | English |
| Links  | [web](https://covid19dashboards.com/) |
| Presentation | web |
| Model focus | exploratory data analysis, forecasting |
| Geographical scope | varies |
| Data         | varies |
| Uncertainty Quantification |  varies, Bayesian treatment typically |
| Notes | This site aggregates many Jupyter notebooks with various models focusing on different phenomena.|


## Czech/Slovak language


|   | Inštitút zdravotnej politiky |
|----|----|
| Language | Slovak |
| Links  | [web](https://izp.sk/covid-19/), [code](https://github.com/institute-of-health-policies-sk/SIRmodel_COVID-19) |
| Presentation | code, [pdf](https://izp.sk/wp-content/uploads/2020/03/predikcia_koronavirus_17.3.2020_2.pdf) |
| Model focus | spatial modeling, mitigation analysis |
| Geographical scope | Slovak Republic |
| Data         | traffic between regions in Slovakia, case data, healthcare system stress |
| Uncertainty Quantification | ??  |
| Notes | Expecting update 23.3 |


| eSIR on Czech data ||
|----|----|
| Language | Czech |
| Links  | [web](https://htmlpreview.github.io/?https://github.com/smyckaj/Covid19/blob/master/eSIR.html), [code](https://github.com/smyckaj/Covid19) |
| Presentation | static webpage, aims for interactive web app |
| Geographical scope | Czech Republic |
| Data         | [wikipedia](https://cs.wikipedia.org/wiki/Pandemie_COVID-19_v_%C4%8Cesku) |
| Model focus | SIR with observation layer, single spatial compartment  |
| Uncertainty Quantification | stochastic SIR model, stochastic observation layer, Bayesian modeling, MCMC |


| KoronaInfo | MFF UK |
|----|----|
| Language | Czech |
| Links  | [web](https://koronainfo.cz/Predictions) |
| Presentation | static web page |
| Data         | [Ministry of Health CR](https://onemocneni-aktualne.mzcr.cz/covid-19), [worldometers](https://www.worldometers.info/coronavirus/) |
| Geographical scope | Czech Republic, uses data from other countries to fit parameters |
| Model focus | SIR single compartment, observation bias |
| Uncertainty Quantification | confidence interval on top of deterministic model, estimated parameters based on fit to data of other countries |
