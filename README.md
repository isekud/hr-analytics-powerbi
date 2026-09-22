=============================================================================================================================================================================================
HR Analytics Dashboard: RAPORT ZATRUDNIENIA I ROTACJI KADR W LATACH 2025–2026 | Microsoft Power BI 
Autor: Ilona Sekudewicz (w ramach wyzwania Power BI | SkuteczneRaporty.pl) 
[English below]

OPIS PROJEKTU I CEL BIZNESOWY:
Interaktywny dashboard kadrowy przygotowany w programie Microsoft Power BI dla studia gamedev PixelAI Studio. Raport służy jako narzędzie wsparcia decyzji dla Dyrektora HR oraz kadry zarządzającej, umożliwiając bieżące monitorowanie stanu zatrudnienia (Headcount, FTE), dynamiki rotacji pracowników oraz identyfikację ognisk odejść w podziale na działy, zespoły, formy zatrudnienia (B2B vs. UoP) oraz grupy demograficzne. 

KLUCZOWE WNIOSKI BIZNESOWE (STAN NA CZERWIEC 2026):
•	Spadek zatrudnienia: Ogólny headcount w organizacji spadł z 64 osób w maju do 60 osób w czerwcu (55,5 FTE). 
•	Ogniska rotacji kadr: W maju odpływ pracowników skupił się w dziale marketingu i PR (3 odejścia z 4 w całej firmie). W czerwcu 2026 r. wszystkie 3 odejścia dotyczyły wyłącznie działu Quality Assurance (QA), gdzie wskaźnik rotacji w dziale QA sięgnął 20% (przy ogólnej rotacji w firmie na poziomie 5,0%).
•	Główna przyczyna odejść (Exit Interviews): brak rozliczania nadgodzin (crunch) oraz presja nierealnych terminów w fazie przedpremierowej gier.
•	Rekomendacje dla HR: Pilne wdrożenie programów retencyjnych w dziale QA (szczególnie w zespole Automatyzacji), formalne uregulowanie rozliczeń nadgodzin oraz rewizja obciążenia pracą w kluczowych sprintach. 

MIARY ANALITYCZNE I KALKULACJE DAX:
•	Headcount: Liczba aktywnych pracowników w wybranym okresie. 
•	FTE (Full-Time Equivalent): ekwiwalent pełnego czasu pracy uwzględniający wymiary etatów. 
•	Wskaźnik rotacji (%): Stosunek liczby odejść w danym miesiącu do średniego stanu zatrudnienia. 
•	Zmiana Headcount vs. LM: Śledzenie zmiany zatrudnienia w porównaniu z poprzednim miesiącem (Last Month / MoM).
•	Struktura demograficzna: Rozkład zatrudnienia według przedziałów wiekowych (0-24, 25-34, 35-44, 45-54) oraz płci (K/M). 

MODEL DANYCH I ARCHITEKTURA RAPORTU:
•	ETL w Power Query: czyszczenie danych, standaryzacja typów, obsługa braków danych oraz budowa tabeli kalendarza. 
•	Model relacyjny: schemat gwiazdy łączący tabelę faktów o zatrudnieniu i odejściach z tabelami wymiarów organizacji i czasu. 
•	Warstwa wizualna: Ciemny motyw interfejsu, karty KPI z porównaniami LM (Last Month), wykresy trendów czasowych (liniowe i warstwowe), wykres drzewa (treemap odejść), drążenie wskroś oraz dynamiczne fragmentatory (slicery) według daty, pionu, departamentu i rodzaju umowy.

STRUKTURA PLIKÓW W REPOZYTORIUM:
•	HR_Analytics_PixelAI_Studio.pbix: Główny plik raportu Power BI.
•	hr_dashboard_overview.png: Zrzut ekranu gotowego dashboardu.
•	Certyfikat_Power_BI.pdf: Certyfikat ukończenia szkolenia i wyzwania projektowego. 
•	README.md: Dokumentacja projektu.
=============================================================================================================================================================================================

ENGLISH VERSION
HR Analytics Dashboard: Workforce Headcount & Turnover Report (2025–2026) | Microsoft Power BI 
Author: Ilona Sekudewicz (completed as part of the Power BI Challenge by SkuteczneRaporty.pl) 

PROJECT OVERVIEW & BUSINESS OBJECTIVE: An interactive People Analytics dashboard developed in Microsoft Power BI for the game development studio PixelAI Studio. The report serves as a Decision Support System (DSS) for the HR Director and executive leadership, enabling continuous tracking of workforce capacity (Headcount, FTE), attrition dynamics, and the identification of turnover hotspots across departments, teams, contract types (B2B vs. Permanent Employment / UoP), and demographic segments. 

KEY BUSINESS FINDINGS (AS OF JUNE 2026):
•	Headcount Contraction: Total organizational headcount decreased by 4 employees, dropping from 64 in May to 60 in June (55.5 FTE). 
•	Turnover Hotspots: In May, employee turnover was heavily concentrated in the Marketing & PR department (3 out of 4 total departures across the company). In June 2026, all 3 departures occurred exclusively within the Quality Assurance (QA) department, driving the QA department's turnover rate to 20% (with company-wide turnover at 5.0%).
•	Identified Exit Drivers (Exit Interviews): Uncompensated overtime (crunch) and intense milestone pressure during pre-release production stages.
•	Strategic HR Recommendations: Implement immediate retention initiatives in the QA division (specifically within the QA Automation team), establish formalized overtime compensation guidelines, and rebalance sprint workloads during critical release phases. 

ANALYTICAL METRICS & DAX CALCULATIONS
• Headcount: Number of active employees during the selected reporting period.
• FTE (Full-Time Equivalent): Standardized workload capacity accounting for both full-time and fractional employment contracts.
• Turnover Rate (%): Ratio of monthly departures to average active headcount.
• Headcount Change vs. LM: Month-over-month (MoM) variance tracking workforce fluctuations against the previous month (Last Month).
• Demographic Breakdown: Workforce distribution segmented by age brackets (0–24, 25–34, 35–44, 45–54) and gender demographics (Female/Male).

DATA MODELING & REPORT ARCHITECTURE:
• ETL in Power Query: Ingestion, schema normalization, data type casting, missing value handling, and custom calendar table creation.
• Relational Data Model: Star schema connecting fact tables for workforce snapshots and departures with dedicated organizational and time dimensions.
• Visual Layer: Executive dark-themed interface, high-contrast KPI metric cards with LM (Last Month) variance indicators, longitudinal time-series trends (line and area charts), exit distribution treemap, drill-through functionality, and dynamic multi-level slicers filtering by date, division, department, and contract type.

REPOSITORY STRUCTURE:
•	HR_Analytics_PixelAI_Studio.pbix: Core Power BI report file.
•	hr_dashboard_overview.png: High-resolution screenshot of the dashboard.
•	Certyfikat_Power_BI.pdf: Official certificate of challenge completion. 
•	README.md: Project documentation.
=============================================================================================================================================================================================
