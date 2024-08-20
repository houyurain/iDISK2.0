## Download iDISK 2.0 Entities
To access the entity vocabulary in the iDISK 2.0, you can directly download the .csv files.
Below is a description of the iDISK 2.0 entity files:
```
DSI.csv  ## The information about the Dietary Supplement Ingredient (DSI).
DSP.csv  ## The information about the Dietary Supplement Product (DSP).
D.csv    ## The information about the Drug.
Dis.csv  ## The information about the Disease.
SS.csv   ## The information about the Sign or Symptom (SS).
SOC.csv  ## The information about the System Organ Class (SOC).
TC.csv   ## The information about the Therapeutic Class (TC).
```
## iDISK 2.0 entities vocabulary
Each row in the iDISK 2.0 entity vocabulary describes an entity, and each column in this row records the entity's attributes (such as DSI's background information, etc.). For example,
| iDISK_ID  | Name           | CUI      | Background                        |
| --------- | -------------- | -------- | --------------------------------- |
| DSI000000 | Serenoa repens | C4082853 | Saw palmetto is a...              |
| DSI000001 | Zea mays       | C0010028 | The long shiny fibers...          |
| DSI000002 | Selenium       | C0521939 | Selenium, an essential dietary... |

The above example comes from the "DSI.csv" (the Dietary Supplement Ingredient vocabulary table). In the table, the column "iDISK_ID" indicates the entities' unique identifier in the iDISK 2.0; the "Name" column indicates the entity name; "CUI" column indicates the entity's corresponding UMLS CUI; and the remaining columns describe the various attribute information of the entity （e.g. Background).
