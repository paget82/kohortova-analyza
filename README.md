# Projekt: Kohortová analýza
Kohortová analýza je metoda používaná v oblasti analytiky a business intelligence, která slouží k rozdělení zákazníků nebo uživatelů do kohort na základě společných charakteristik nebo zkušeností v určitém časovém období. Tyto kohorty jsou pak sledovány v čase, aby bylo možné pozorovat změny v chování, používání nebo jiných klíčových metrikách.

###  Soubory ke stažení
-  [CSV](cohorts.csv) – Dataset
-  [Jupyter Notebook](kohortova-analyza.ipynb) – Kohortová analýza


## Dataset
Poskytnutý dataset obsahuje údaje o interakci uživatelů, včetně metrik jako je počet nových a vracejících se uživatelů a délka jejich zapojení v 1. a 7. den.


### Klíčové sloupce v datasetu:
- **Datum**: Konkrétní dny interakcí uživatelů.
- **Noví uživatelé**: Počet nových uživatelů pro každý den.
- **Vracející se uživatelé**: Počet uživatelů, kteří se v daný den vrátili.
- **Délka trvání – den 1**: Průměrná doba interakce uživatele v jejich první den.
- **Délka trvání – den 7**: Průměrná doba interakce uživatele v jejich sedmý den.

## Cíl projektu
1. Identifikovat trendy v získávání nových uživatelů a udržení vracejících se uživatelů na týdenní bázi.

2. Porozumět vývoji zapojení uživatelů – jak se mění průměrná délka interakce od prvního dne do sedmého.

3. Odhalit výrazné týdenní vzorce nebo odchylky v chování a zapojení uživatelů a prozkoumat možné příčiny těchto trendů.

4. Prozkoumat vztah mezi retencí a zapojením, abyste mohli posoudit účinnost "user engagement" strategií.

6. Poskytnout akční doporučení pro marketing, tvorbu obsahu a zlepšení uživatelské zkušenosti.

## Výsledek
![kohortova-analyza](https://github.com/paget82/kohortova-analyza/blob/main/Trend%20of%20New%20and%20Returning%20Users%20Over%20Time.png)

![kohortova-analyza](https://github.com/paget82/kohortova-analyza/blob/main/Trend%20of%20Duration%20(Day%201%20and%20Day%207)%20Over%20Time.png)

![image](https://github.com/user-attachments/assets/a5ec873b-154f-4971-b144-91e5732848d2)

Nejsilnější korelace je mezi počtem nových a vracejících se uživatelů – noví uživatelé se často vracejí.

![kohortova-analyza](https://github.com/paget82/kohortova-analyza/raw/main/Weekly%20Average%20of%20New%20vs.%20Returning%20Users.png)

![kohortova-analyza](https://github.com/paget82/kohortova-analyza/raw/main/Weekly%20Average%20of%20Duration.png)

![image](https://github.com/user-attachments/assets/6e2019ba-0c00-4669-89ad-af2b10413db7)

Z kohortní matice je patrné, že počet uživatelů i délka trvání interakcí se liší týden od týdne. Například ve 47. týdnu došlo k významnému nárůstu obou typů uživatelů. Délka trvání však nevykazuje přímou souvislost s počtem uživatelů – mohou ji ovlivňovat jiné faktory jako kvalita obsahu, technické problémy nebo externí události.


