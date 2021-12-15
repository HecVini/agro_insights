# agro_insights

## CAIT CO2e Emissions
	dt_cait1: CAIT CO2e emissions database
		year = years beatween 1990 and 2018
		iso = countries  ISO-3 standart code. Available for 193 UN recognized countries.
		sector = Agriculture, Energy, Industrial Processes, LUCF, Waste
		emiss = MtCO2e emissions, according to SAR GWP
		
	dt_cait2: CAIT CO2e emissions database
		year = years beatween 1990 and 2018
		iso = countries  ISO-3 standart code. Available for 166 UN recognized countries + UE27.
		sector = Agriculture, Energy, Industrial Processes, LUCF, Waste
		emiss = MtCO2e emissions, according to SAR GWP
		
	dt_cait3: CAIT CO2e emissions database
		year = years beatween 1990 and 2018
		iso = countries  ISO-3 standart code. Available for 193 UN recognized countries.
		sector = Agriculture, Energy, Industrial Processes, LUCF, Waste + Energy subsectors (see methodology)
		emiss = MtCO2e emissions, according to SAR GWP
		
	CAIT methodology available in: http://cait2.wri.org/docs/CAIT2.0_CountryGHG_Methods.pdf
	Original data available in: https://www.climatewatchdata.org/data-explorer/historical-emissions?historical-emissions-data-sources=cait&historical-emissions-gases=all-ghg&historical-emissions-regions=All%20Selected&historical-emissions-sectors=total-including-lucf&page=1
	
## Global Carbon Project CO2 Emissions
	dt_cait1: CAIT CO2e emissions database
		year = years beatween 1990 and 2018
		iso = countries  ISO-3 standart code. Available for 193 UN recognized countries.
		sector = Agriculture, Energy, Industrial Processes, LUCF, Waste
		emiss = MtCO2e emissions, according to , in
		
	CAIT

## Bolsa Familia Program (BFP) Cash Transfers 
	dt_bfp1: BFP monthly cash tranfers, per munnicipality in BRL. (Jan/2004 - Dec/2020)
		date = yyyy-mm-dd
		mun_ibge7 = IBGE's state 7-number code, for every 5570 Brazilian cities.  
		mun_name = munnicipality name
		uf_ibge2 = IBGE's state 2-number code, for every 27 Brazilian states.
		fam = numbers of subscribed families in each month. 
		transf = cash tranfers for each city, in each month, in nominal BRL.
		trasf_ipca = cash tranfers for each city, in dec/2020 BRL inflation-adjusted, by IPCA (Brazilian CPI).
    
	dt_bfp2: BFP annual nominal cash tranfers, per munnicipality in BRL. (Jan/2004 - Dec/2020)
		year = year between 2004 and 2020
		mun_ibge7 = IBGE's state 7-number code, for every 5570 Brazilian cities.  
		mun_name = munnicipality name
		uf_ibge2 = IBGE's state 2-number code, for every 27 Brazilian states.
		avrg_fam = average families subscribed in each year.
		transf = cash tranfers for each city, in each month, in nominal BRL.
		trasf_ipca = cash tranfers for each city, in dec/2020 BRL inflation-adjusted, by IPCA (Brazilian CPI).

	Original Data available in: https://dados.gov.br/dataset/bolsa-familia-misocial
	IPCA data available in: http://www.ipeadata.gov.br/Default.aspx (search for "IPCA" and select "Índice nacional de preços ao consumidor amplo (IPCA) geral: índice (dez. 1993 = 100)")

## GDP and Population
	dt_pop: Brazian cities annual population
		year = years between 2001 and 2021
		mun_ibge7 = IBGE's state 7-number code, for every 5570 Brazilian cities.  
		mun_name = munnicipality name
		uf_ibge2 = IBGE's state 2-number code, for every 27 Brazilian states.
		pop = estimated population at jul 31. Population in 2007 from the demographic count and 2010 from the census.
		
	dt_gdp: Brazilian cities gross domestic product
		year = years between 2001 and 2021
		mun_ibge7 = IBGE's state 7-number code, for every 5570 Brazilian cities.  
		mun_name = munnicipality name
		uf_ibge2 = IBGE's state 2-number code, for every 27 Brazilian states.
		gdp = nominal GDP in thousand BRL
		gdp_defimp = real GDP in thousand BRL, inflation-adjusted by GDP implicit deflator
		gdp_pc = nominal GDP divided by population, in BRL
		gdp_defimp_pc = real GDP divided by population, in BRL
		
	Original Data available in: https://sidra.ibge.gov.br/tabela/5938, https://sidra.ibge.gov.br/tabela/6579, https://sidra.ibge.gov.br/tabela/793, https://sidra.ibge.gov.br/tabela/200
	Implicit deflator available in: 

## Cattle Effective
	dt_cattle1: Bovine cattle herd effective size at city level.
		year = years between 1974 and 2020
		mun_ibge7 = IBGE's state 7-number code, for every 5570 Brazilian cities.  
		mun_name = munnicipality name
		uf_ibge2 = IBGE's state 2-number code, for every 27 Brazilian states.
		cattle_size = heads of bovine cattle by dec 31
      
	dt_cattle2: Bonive cattle herd effective size at state level.
		year = years between 1974 and 2020
		uf_ibge2 = IBGE's state 2-number code, for every 27 Brazilian states.
		cattle_size = heads of bovine cattle by dec 31
     
	Original data available in: https://sidra.ibge.gov.br/tabela/3939

## Deforestation
	dt_prodes1: state-level deforestation increment.
		year = years between 1988 and 2021.
		uf_ibge2 = IBGE's state 2-number code, for every 27 Brazilian states.
		sqkm = increase in deforestation area, in sqkm.
		
	dt_prodes2: city-level deforestation increment.
		year = years between 2008 and 2021.
		mun_ibge7 = IBGE's state 7-number code, for every 5570 Brazilian cities.  
		mun_name = munnicipality name
		uf_ibge2 = IBGE's state 2-number code, for every 27 Brazilian states.
		sqkm = increase in deforestation area, in sqkm.
		
		
	dt_mapabiomas: city-level land cover data
		
	PRODES original data available in: http://terrabrasilis.dpi.inpe.br/app/dashboard/deforestation/biomes/amazon/increments
	MapaBiomas original data available in: https://mapbiomas.org/estatisticas

	Original data availabe in: http://terrabrasilis.dpi.inpe.br/app/dashboard/deforestation/biomes/legal_amazon/rates
