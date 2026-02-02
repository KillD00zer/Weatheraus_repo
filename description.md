| Column Name | Description | Units / Type |
| :--- | :--- | :--- |
| **Date** | The date of observation | Date (YYYY-MM-DD) |
| **Location** | The common name of the weather station location | Categorical (City Name) |
| **MinTemp** | The minimum temperature recorded in the 24 hours to 9am | Celsius (°C) |
| **MaxTemp** | The maximum temperature recorded in the 24 hours to 9am | Celsius (°C) |
| **Rainfall** | The amount of rainfall recorded for the day | Millimeters (mm) |
| **Evaporation** | The Class A pan evaporation (water evaporation) in the 24 hours to 9am | Millimeters (mm) |
| **Sunshine** | The number of hours of bright sunshine in the day | Hours |
| **WindGustDir** | The direction of the strongest wind gust in the 24 hours to midnight | Categorical (16 Compass Points) |
| **WindGustSpeed** | The speed of the strongest wind gust in the 24 hours to midnight | Kilometers per hour (km/h) |
| **WindDir9am** | The direction of the wind at 9am | Categorical (Compass Points) |
| **WindDir3pm** | The direction of the wind at 3pm | Categorical (Compass Points) |
| **WindSpeed9am** | The wind speed averaged over 10 minutes prior to 9am | Kilometers per hour (km/h) |
| **WindSpeed3pm** | The wind speed averaged over 10 minutes prior to 3pm | Kilometers per hour (km/h) |
| **Humidity9am** | The relative humidity at 9am | Percent (%) |
| **Humidity3pm** | The relative humidity at 3pm | Percent (%) |
| **Pressure9am** | Atmospheric pressure reduced to mean sea level at 9am | Hectopascals (hPa) |
| **Pressure3pm** | Atmospheric pressure reduced to mean sea level at 3pm | Hectopascals (hPa) |
| **Cloud9am** | Fraction of the sky obscured by cloud at 9am | Oktas (0–8 scale) |
| **Cloud3pm** | Fraction of the sky obscured by cloud at 3pm | Oktas (0–8 scale) |
| **Temp9am** | Temperature recorded at 9am | Celsius (°C) |
| **Temp3pm** | Temperature recorded at 3pm | Celsius (°C) |
| **RainToday** | Did the current day receive rainfall exceeding 1mm? | Binary (Yes/No) |
| **RainTomorrow** | **(Target)** Did it rain the next day? | Binary (Yes/No) |

Sources
https://www.kaggle.com/code/jribeiro09/