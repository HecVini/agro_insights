# agro_insights

## CAIT CO2e Emissions

## Global Carbon Project CO2 Emissions

## MI Social Bolsa Familia Programm (BFP) Cash Transfers 
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

		Original Data available in: https://dados.gov.br/dataset/bolsa-familia-misocial#
		IPCA data available in: http://www.ipeadata.gov.br/Default.aspx (search for "IPCA" and select "Índice nacional de preços ao consumidor amplo (IPCA) geral: índice (dez. 1993 = 100)")

## Cattle Effective (1974 - 2020)
	dt_cattle1: Bonive cattle herd effective size at city level.
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
 
