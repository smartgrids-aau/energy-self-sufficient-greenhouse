# energy-self-sufficient-greenhouse
 ​Simulation models for PV output and electrical energy consumption for an energy self-sufficient greenhouse

The Python-based simulation evaluates the performance of the Organic Photovoltaic (OPV) system integrated on the roof. The model considers diffrent environmental variables, like temperature, sunshine duration, and cloud cover.
To ensure a comparative analysis, the simulation utilizes two distinct trackers: one monitors the energy yield from the roof installation, while the other measures the output from the two panels on the exterior wall. 

The simulation references a specific weather dataset "Wetter_Daten.xlsx" to ensure environmental accuracy. 
Quellen:
https://www.sunrise-and-sunset.com/de/sun/osterreich/klagenfurt-am-woerthersee/2025/november
Zugriff  = 22.02.2026
https://meteostat.net/de/station/11231?t=2025-01-01/2025-12-31
Zugriff = 22.02.2026
https://dataset.api.hub.geosphere.at/app/frontend/station/historical/klima-v2-1m
Zugriff = 22.02.2026

Additionally, the model incorporates technical specifications from the HeliaKit documentation, which provides the benchmark parameters and efficiency values assumed for the OPV modules. 
Quelle: https://www.heliatek.com/en/ Zugriff: 24.August 2025
