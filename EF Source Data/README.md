Information datamined from within the game itself.

Folder structure is "region-version". e.g. korea-2.5.9, global 1.6.8. 


## Guide to XML Contents ##

#### petbook.xml ####
```
petList (Name in English can be worked out from translation file PET_NAME_kindNum)
    kindNum      - Unique ID of Pet
    className    - ?? 
    name         - Name in Korean.
    tribe        - 1=Human, 2=Elf, 3=Undead, 4=Orc
    type         - ??
    rank         - ??
    skill1       - ID of Skill in petbook.xml, petSkillList section.
    value1       - Strength of skill1 at levels 1 to 5 (Separator "|")
    skill2       - ID of Skill in petbook.xml, petSkillList section.
    value2       - Strength of skill1 at levels 1 to 5 (Separator "|")
    masterskill  - ID of Skill in petbook.xml, petSkillList section.
    value3       - Strength of skill1 at levels 1 to 5 (Separator "|")
    couple       - ID of Unit Couple (-1 means no unit couple)
    incGoldLevel - Pet Points gained at levels 1 to 5 (Separator "|")
    treasure     - ID of Artifact gained at Level 5 (0 means no artifact gained)
    isPercent    - ?
    isAlpha      - ??
```
```
petSkillList (Name in English can be worked out from translation file PET_SKILL_DESC_kindNum)
    kindNum - Unique ID of Pet Skill
    id      - ??
    name    - ??
    sub     - ??
    Type    - Seems to identify where the pets buff applies.
    desc    - Skill description in Korean
    misc    - ??
```
```
gemForPetScenarioTicket - Cost of extra Spirit Highlands Tickets
```
```
petStoneForEvolve - Amount of Pet FRagments needed to level up Pet
```
```
maxLevelUpForPetGrade - ??
```
