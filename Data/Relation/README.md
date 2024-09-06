## Download iDISK 2.0 Relationships
To access the relationships in the iDISK 2.0, you can directly download the iDISK 2.0 relation using the following link.
```
https://drive.google.com/drive/folders/1XTtb4KKxUXfqG8tZTbvxtwv7IDUHe424?usp=sharing
```
When you unzip the file, you will get the following .csv files.
```
dsp_dsi.csv  ## The relationships between the Dietary Supplement Product (DSP) and Dietary Supplement Ingredient (DSI).
dsi_dis.csv  ## The relationships between the Dietary Supplement Ingredient (DSI) and the Disease.
dsi_d.csv    ## The relationships between the Dietary Supplement Ingredient (DSI) and the Drug.
dsi_ss.csv  ## The relationships between the Dietary Supplement Ingredient (DSI) and the Sign or Symptom (SS).
dsi_SOC.csv  ## The relationships between the Dietary Supplement Ingredient (DSI) and the System Organ Class (SOC).
dsi_TC.csv   ## The relationships between the Dietary Supplement Ingredient (DSI) and the Therapeutic Class (TC).
```
## The statistics of iDISK 2.0 entities
| Relationship                   | # of entity |
| ------------------------------ | ----------- |
| is_effective_for (DSI-Disease) | 5,245       |
| has_therapeutic_class (DSI-TC) | 4,435       |
| has_adverse_effect_on (DSI-SOC)| 2,598       |
| has_adverse_reaction (DSI-SS)  | 1,342       |
| has_ingredient (DSP-DSI)       | 317,062     |
| interacts_with (DSI-Drug)      | 3,583       |
| Total                          | 334,265     |

## iDISK 2.0 relationships
Each row in the iDISK 2.0 relationship describes the relationship between a pair of entities, and each column in this row records the relationship's attributes (such as Interaction Rating of DSI interaction with Drugs, etc.). For example,
| DSI       | Relation       | D       | Source    | Interaction Rating | Source Description                           |
| --------- | -------------- | --------| --------- | ------------------ | -------------------------------------------- |
| DSI001441 | interacts_with | D000001 | MSKCC     |                    | Monamine oxdiase inhibitors ...              |
| DSI001441 | interacts_with | D000002 | MSKCC     |                    | Linezolid (Zyvox, an antibiotic MAOI) ...    |
| DSI001441 | interacts_with | D000003 | MSKCC, NM | Moderate           | Carbidopa (Lodosyn, a dopamine promoter) ... |

The above example comes from the "dsi_d.csv" (the relationship table between the Dietary Supplement Ingredient (DSI) and the Drug). In the table, the columns "DSI" and "D" indicate the DSI entities and the Drug entities' unique identifier in the iDISK 2.0, respectively; the "Relation" column indicates the type of relationship; "Souce" column indicates the source information about this entity pair; and the remaining columns describe the various attribute information of the relationship （e.g. Interaction Rating).

## The attributes of the relationships in iDISK 2.0
In iDISK 2.0, there are two relationship attributes. They are:
* Dietary Supplement Ingredient (DSI) - Disease: Effectiveness Rating
* Dietary Supplement Ingredient (DSI) - Drug: Interaction Rating

