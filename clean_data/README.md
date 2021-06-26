# Summary of Files

## __Main Dataframe (sample)__
---
> df_injury_clean.csv

|FIELD1|Treatment_Date|Age                             |Sex   |Alcohol|Drug|Narrative                                                                                                                                                                                                                                                                                                                                                                                                       |Incident Locale              |Body_Part        |Diagnosis                                  |Disposition                                            |
|------|--------------|--------------------------------|------|-------|----|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------|-----------------|-------------------------------------------|-------------------------------------------------------|
|0     |1/1/16        |39                              |Male  |       |    |39YOM WAS LIGHTING BOTTLE...                                                                                                                                                                                                                                                                                                                                |Home                         |Eyeball          |Contusions, Abrasions                      |Treated/Untreated and Released...|

<br>

## __Helper Dataframes (samples)__
---
<br>

>df_body_part.csv

|FIELD1|Code|Body_Part|
|------|----|--------------------------------|
|0     |0   |Internal|
|1     |30  |Shoulder                        |
|2     |31  |Upper Trunk    ....                 |

<br>

>df_diagnosis.csv

|FIELD1|Diagnosis1|Code                            |
|------|----------|--------------------------------|
|0     |Ingested foreign object|41                              |
|1     |Aspirated foreign object|42                              |
|2     |Burns, electrical 46 Burns, not specified|47...|

<br>

>df_disposition.csv

|FIELD1|Code|Disposition                     |
|------|----|--------------------------------|
|0     |1   |Treated/Untreated and Released  |
|1     |2   |Treated and transferred to another hospital|
|2     |3   |Treated and admitted for hospitalization...|

<br>

>df_incident_local.csv

|FIELD1|Code|Incident Locale                 |
|------|----|--------------------------------|
|0     |1   |Home                            |
|1     |2   |Farm/Ranch                      |
|2     |4   |Street or highway...|

<br>

>df_race.csv

|FIELD1|Code|Race                            |
|------|----|--------------------------------|
|0     |0   |Not stated in ED record         |
|1     |1   |White                           |
|2     |2   |Black/African American...|

<br>

