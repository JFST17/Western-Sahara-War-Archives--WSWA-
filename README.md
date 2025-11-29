# WSWA
Western Sahara War Archives (WSWA) Military Dataset. This dataset is the result of 4 years of data collection by the Centre of African Studies of Porto University (CEAUP), Project: Western Sahara War Archives- A Digital Archive for the 3rd phase of the Western Sahara War /https://www.africanos.eu/index.php/en/ceaup-r-d/future-research-projects/1292-digital-archives-relationalof-databases)

---

## Context and Objectives
This dataset is the result of four years of data mining on the Sahara Press Service (SPS-https://www.spsrasd.info/es). All raw data was gathered, analysed and made publicly available on the project website (https://westernsaharawararchive.com/). The research question of the project is: What is the evolution of the 3rd Phase of the Western Sahara Conflict? The data was collected and analysed by the WSWA Statistics Team, coordinated by Jorge Teixeira (https://orcid.org/0000-0003-3139-6506). The project aims to inform and organise data about the latest stage of the last colonial war in Africa, which started on 13th November 2020 in Western Sahara.

---

## Methodology

It was intended to use data from both sides of the conflict, but so far, the Kingdom of Morocco does not recognise that there is such a conflict. Due to this fact, we do not have data from the Moroccan side of the conflict. Thus, to date, the only data available are from the Sahrawi and the UN. AS SPS is the official news source of the Saharawi Arab Democratic Republic (SADR) and is responsible for publishing official communications. Therefore, SPS reports were our primary source of information about the conflict. As the official language of SADR is Hassaniya, the team, after careful consideration and several meetings with representatives of the Sahrawi, opted to utilise the SADR Military Conmmuniqués published in Spanish. These reports were published on a daily basis. After the creation of the official SPS Facebook page, those reports began to be published there, in Arabic, and as weekly summaries, rather than on the SPS website. The reports would be published again on the website.

SPS Communiqués refer to the attacks by the Frente POLISARIO “…intensos bombardeos a […] .” (SPS, 2021). In the absence of a specific number, we count all attacks described as “intense” as 1 attack.

In order to make the statistical data easier to analyse, and after several meetings with official Saharawi entities and the analysis of the War Communiqués, it was possible to divide the territory of Western Sahara into analyzable portions:

<ul>
  <li>Theatre of Operations
    <ul>
      <li>It is the mega-level of the conflict</li>
      <li>Two sectors of MR1 are located within Morocco
        <ul>
          <li>Due to this fact, to better understand the data, we have coded:
            <ul>
              <li>Events that happened within Morocco as <strong>C01</strong></li>
              <li>Events that happened within Western Sahara as <strong>C02</strong></li>
            </ul>
          </li>
        </ul>
      </li>
    </ul>
  </li>
  <li>Western Sahara was divided into three military regions
    <ul>
      <li>They have a North–South orientation</li>
      <li>They are named after the geographical area where they are inserted</li>
      <li>They are the macro-level of the conflict</li>
      <li>Each Military Region was attributed the acronym <strong>MRx</strong></li>
      <li>Each Military Region received a unique colour (Hexadecimal colour code)
        <ul>
          <li>The attribution of a Hexadecimal colour code allows for better organisation and better reading of the attack data</li>
        </ul>
      </li>
    </ul>
  </li>
  <li>Each MR is composed of four (4) Sectors, except MR3, which has five (5)
    <ul>
      <li>They have a North–South orientation</li>
      <li>They are named after the most important point within the Sector</li>
      <li>They are the meso-level of the conflict</li>
      <li>The Sectors are located along the Moroccan Military Wall</li>
      <li>Each Sector was attributed the acronym <strong>Sx</strong></li>
      <li>Each Sector received a unique colour (Hexadecimal colour code)
        <ul>
          <li>Attributing a Hexadecimal colour code allows for better organisation and better reading of the attack data</li>
        </ul>
      </li>
    </ul>
  </li>
  <li>Each military Sector is composed of Zones
    <ul>
      <li>They are the micro-level or conflict zones where attacks take place</li>
      <li>They are the micro-level or conflict zones, where the attacks take place</li>
    </ul>
  </li>
</ul>

<ul>
  <li>The Data Selection Criteria are:
    <ul>
      <li>Official Numbered SADR Military Communiqués published in Spanish on the SPS website</li>
      <li>Within those reports:
        <ul>
          <li>Date of events</li>
          <li>Number of events</li>
          <li>General location of events (indicating the name of the zone and/or region of the attacks)</li>
          <li>Additional information such as type of base attack:
            <ul>
              <li>Artillery Platform</li>
              <li>Specific Base or Platoon Base</li>
              <li>Surveillance Point</li>
            </ul>
          </li>
          <li>All War Communiqués will have the word <strong>“ataques”</strong> or <strong>“bombardeos”</strong> in their title</li>
          <li>All War Communiqués will have a photo of military equipment</li>
          <li>Reference to <strong>ELPS</strong></li>
        </ul>
      </li>
      <li>Published between 13th November 2020 and 12th November 2024</li>
    </ul>
  </li>

  <li>Known Limitations:
    <ul>
      <li>No Moroccan Data</li>
      <li>Unreliability of publishing schedule</li>
      <li>Multiple writers</li>
      <li>Hassaniya is primarily a spoken language, causing terminology inconsistencies in reports</li>
      <li>Multiple platforms</li>
    </ul>
  </li>
</ul>

The statistical Data were obtained from the information in the War Communiqués edited in the SPS, which were compiled in the War Reports of the website: https://westernsaharawararchive.com/
• Tables, Graphs and Maps will be coloured;
• The coloured schematics will be explained at the beginning of each analysis.

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
