# WSWA
Western Sahara War Archives (WSWA) Military Dataset. This dataset is the result of 4 years of data collection by the Centre of African Studies of Porto University (CEAUP), Project: Western Sahara War Archives- A Digital Archive for the 3rd phase of the Western Sahara War /https://www.africanos.eu/index.php/en/ceaup-r-d/future-research-projects/1292-digital-archives-relationalof-databases)

---

## Context and Objectives
This dataset is the result of four years of data mining on the Sahara Press Service (SPS-https://www.spsrasd.info/es). All raw data was gathered, analysed and made publicly available on the project website (https://westernsaharawararchive.com/). The research question of the project is: What is the evolution of the 3rd Phase of the Western Sahara Conflict? The data was collected and analysed by the WSWA Statistics Team, coordinated by Jorge Teixeira (https://orcid.org/0000-0003-3139-6506). The project aims to inform and organise data about the latest stage of the last colonial war in Africa, which started on 13th November 2020 in Western Sahara

---

## Methodology

1. It was intended to use data from both sides of the conflict, but so far, the Kingdom of Morocco does not recognise that there is such a conflict. Therefore, we do not have data on the Moroccan side.
2. Sahara Press Service is the official news source of the Saharawi Arab Democratic Republic
2.1. Henceforth, we will use the acronym SADR when referring to the Saharawi Arab Democratic Republic.
2.2. Henceforth, we will use the acronym SPS when referring to Sahara Press Service.
2.3. SPS reports are our information base on the conflict, on the Frente POLISARIO side.
2.4. SPS Communiqués refer to the attacks by the Frente POLISARIO “…intensos bombardeos a […] .” (SPS, 2021). In the absence of a specific number, we count all attacks described as “intense” as 1 attack.
3. In order to make the statistical data easier to analyse, and after several meetings with official Saharawi entities and the analysis of the War Communiqués, it was possible to divide the territory of Western Sahara into analyzable portions:
3.1. This division consists of two levels:
3.1.1. Military Region - large geographic regions, that is, the macro unit;
3.1.1.1. So far, 3 (three) Military Regions have been counted;
3.1.1.2. The Military Regions to consider are:
• Military Region 1-Oued Daraa;
• Military Region 2-Saguia El Hamara;
• Military Region 3-Rio de Oro.
3.1.1.3. Saguia El Hamara and Rio de Oro are the two former Spanish administrative regions, with Oued Daraa being added.
3.1.1.4. From now on, we will use the term RM when referring to Military Regions.
3.1.1.5. We will use the acronym RM+Nº as an abbreviation when referring to a particular region, i.e., R1, when referring to Region 1 – Oued Daraa. Therefore, we will designate the Military Regions as follows:
• RM 1
• RM 2
• RM 3
3.1.2. Sector- smaller regions within large regions, that is, the micro unit;
3.1.2.1. Up to the present moment, 13 sectors have been accounted for;
3.1.2.2. The Sectors to consider are:
• Sector 1 – Aaga;
• sector 2 – Touizgui;
• Sector 3 – El Mahabas;
• Sector 4 – Farsia;
• Sector 5 – Haouza;
• Sector 6 – Smara;
• Sector 7 – Amgala;
• Sector 8 – Guelta Zemmour;
• Sector 9 – Oum Dreiga;
• Sector 10 – El Bagari;
• Sector 11 – Auserd;
• Sector 12 – Techla;
• Sector 13 – Bir Guendouz;
3.1.3. We will use the acronym S+Nº as an abbreviation when referring to a particular Sector, i.e., S1, when referring to Sector 1-Aaga. Therefore, we will designate the Sectors as follows:
• S1;
• S2;
• S3;
• S4;
• S5;
• S6;
• S7;
• S8;
• S9;
• S10;
• S11;
• S12;
• S13;
4. In practice, for this Report, the territorial division is as follows:
• RM 1 is comprised:
▪ S1
▪ S2
▪ S3
▪ S4
• RM 2 comprises:
▪ S5
▪ S6
▪ S7
▪ S8
• RM 3 comprises:
▪ S9
▪ S10
▪ S11
▪ S12
▪ S13
5. The statistical Data were obtained from the information in the War Communiqués edited in the SPS, which were compiled in the War Reports of the website: https://westernsaharawararchive.com/
• Tables, Graphs and Maps will be coloured;
• The coloured schematics will be explained at the beginning of each analysis.

- Source of the data: SADR Military Conmmuniqués published on Sahara Press Service (SPS-https://www.spsrasd.info/es), published in Spanish
- Time of Analysis: 13th November 2020 to 12th November 2024
- Data Selection Criteria:
          -    
- instrumentos usados (questionários, scraping, entrevistas, etc.),
- limitações conhecidas.



---

## Data Structure
## Summary of the data analysed
| Variavel | Type | Description |
|---------|------|-----------|
| Starting date      | date | 13th of November 2020 |
| Ending date      | date | 12th of November 2024 |
| Time Frame of Analysis      | string | 4 years (2020-2024) |
| Total of Months analysed      | int | 48 |
| Total of Weeks analysed      | int | 210 |
| Total of Days analysed      | int | 1457 |
| Total of Semesters analysed      | int | 8 |
| Total number of countries analysed      | int | 2 |
| Total of Military Regions analysed      | int | 3 |
| Total of Sectors analysed      | int | 13 |
| War communiques      | int | 744 |
| Month N      | string | 13th of X to 12th of Y |

---

## Matrix of the composition of the Theatre of Operations in Western Sahara

## Military Region 1
| Name        | Acronym | Type/Region/Sector        | Hex Colour |
|-------------|---------|----------------------------|------------|
| Oued Daraa  | MR1     | Northern Region            | `#E2EFD9`  |
| Aaga        | S1      | Northern Sector            | `#BED5B4`  |
| Touizigui   | S2      | Centre-Northern Sector     | `#90BB7A`  |
| El Mahabes  | S3      | Centre-Southern Sector     | `#68A242`  |
| Farsia      | S4      | South Sector               | `#568736`  |


## Military Region 2
| Name            | Acronym | Type/Region/Sector        | Hex Colour |
|-----------------|---------|----------------------------|------------|
| Saguia El Hamara| MR2     | Central Region             | `#FEF2CB`  |
| Haouza          | S5      | Northern Sector            | `#FFDDAD`  |
| Smara           | S6      | Centre-Northern Sector     | `#FFCA69`  |
| Amgala          | S7      | Centre-Southern Sector     | `#EFB300`  |
| Guelta Zemmour  | S8      | South Sector               | `#C89600`  |


## Military Region 3
| Name         | Acronym | Type/Region/Sector        | Hex Colour |
|--------------|---------|----------------------------|------------|
| Rio de Oro   | MR3     | Southern Region            | `#FBE4D5`  |
| Oum Dreiga   | S9      | Northern Sector            | `#FF6161`  |
| El Bagari    | S10     | Centre-Northern Sector     | `#FF3737`  |
| Auserd       | S11     | Centre-Southern Sector     | `#FF1D1D`  |
| Techla       | S12     | South Sector               | `#D20000`  |
| Bir Guendouz | S13     | Centre-Southern Sector     | `#A80000`  |



- formato (CSV, JSON, etc.),
- número de linhas / casos,
- número de variáveis,
- separador, encoding (UTF-8, por amor da ciência).

### **Dicionário de Variáveis**
| Variavel | Type | Description |
|---------|------|-----------|
| ID      | string | Alphanumeric code unique identifier composed by the Micro_Level_ID+Meso_Level_ID+Macro_Level_ID+Mega_Level_ID |
| Conflict_Year   | int    | Indicates the year of the conflict |
| Conflict_Month   | int    | Indicates the month of the conflict |
| Conflict_Week    | int    | Indicates the week of the conflict |
| Conflict_Day    | int    | Indicates the day of the conflict |
| Event_Date    | dat    | Indicates the date of the registered event |
| Micro_Level_Name    | string    | Indicates the name of the Micro level of the event |
| N_of_Event    | int    | Indicates the number of registered events |
| Micro_Level_ID    | string    | Alphanumeric code unique identifier of the Micro level of the event; it is composed of Z (stands for Zone) and a number starting from 00 increasing when a new Zone is registered within the Meso Level |
| Meso_Level_ID    | string    | Alphanumeric code unique identifier of the Meso level of the event; it varies between S1, S2, S3, S4, S5, S6, S7, S8, S9, S10, S11, S12 and S13 |
| Macro_Level_ID    | string    | Alphanumeric code unique identifier of the Macro level of the event; it varies between MR1, MR2 and MR3  |
| Mega_Level_ID    | string     | Alphanumeric code unique identifier of the Mega level of the event; it varies between C1 and C2  |
| Calender_Year    | int    | Indicates the civil year of the registered event |
| Calender_Month    | int    | Indicates the civil month of the registered event |
| Calender_Week    | int    | Indicates the number of the civil week of the registered event |
| Calender_Week_Day    | string    | Indicates the day of the week of the registered event  |
| Calender_Season    | string    | Indicates the season of the year of the registered event |
| Mega_Level_Name    | string    |  Indicates the name of the Mega level of the registered event; it varies between Morocco (C1) and Occupied Western Sahara (C2) |
| Macro_Level_Name    | string    | Indicates the name of the Macro level of the registered event; it varies between Oued Daraa (MR1), Saguia El Hamara (MR2) and Rio de Oro (MR3)  |
| Macro_Level_Geographical_Location    | string    | Indicates the geographical location of the Macro level of the registered event; it varies between North, Centre and South |
| Macro_Level_Latitude    | string    | Indicates the latitude of the Macro level |
| Macro_Level_Longitude    | string    | Indicates the longitude of the Macro level |
| Meso_Level_Name    | string    | Indicates the name of the Meso level of the registered event; it varies between Aaga (S1), Touizgui (S2), El Mahbes (S3), Farsia (S4), Haouza (S5), Smara (S6), Amgala (S7), Guelta Zemmour (S8), Oum Dreiga (S9), El Bagari (S10), Auserd (S11), Techla (S12) and Bir Guendouz (S13) |
| Meso_Level_Important_Location    | string    | Indicates the name of the Meso level of the registered event; it varies between Aaga, Touizgui, El Mahbes, Farsia, Haouza, Smara, Amgala, Guelta Zemmour, Oum Dreiga, El Bagari, Auserd, Techla and Bir Guendouz |
| Meso_Level_Geographical_Location    | string    | Indicates the geographical location of the Meso level of the registered event; it varies between North, Centre-North, Centre, Centre-South and South |
| Meso_Level_Longitude    | string    | Indicates the latitude of the Meso level |
| Meso_Level_Latitude    | string    | Indicates the longitude of the Meso level |
| Meso_Level_MINURSO_control   | string    | Varies between Yes and No |

---

## 📦 Organização do Repositório
Explica o que existe em cada pasta:
