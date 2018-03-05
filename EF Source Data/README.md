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

#### unitbook.xml ####

```
unitList/unit (English name can be translated using UNIT_NAME_[kindNum])
    kindNum         - Unit Unique ID
    tribe           - 1=Human, 2=Elf, 3=Undead, 4=Orc
    className       - ?? (Some sort of Descriptor)
    name            - Name in Korean
    cost            - Cost in Medals to buy (Time Shop/Unit Shop)
    shopGem         - Cost in Gems to buy (Unit Shop, -1 for not available)
    evolveGem       - Cost in Gems to evolve (-1 for not available)
    coin            - Cost in Honor Coins (Honor Shop, 0 for not availabe)
    rare            - ?? (Possibly affects how frequently appears in unit shop)
    size            - Unit Size
    evolKindNum     - kindNum of Senior Version (-1 if senior unit)
    attackType      - Attack Type (melee, range, rangeGround)
    isAirUnit       - Is Unit an Air Unit (Y/N)
    damageType      - Damage Type (Magical / Physical)
    hasSkill        - Does unit have special skills (Y/N)
    skillAttackType - Skill Attack Type (melee, range, rangeGround)
    skillDamageType - Skill Damage Type (Magical / Physical)
    initHp          - Level 1 HP
    incHp           - HP Gained Per Level
    initDamage      - Level 1 Damage
    incDamage       - Damage Gained Per Level
    initPhyDef      - Level 1 Physical Defence
    incPhyDef       - Physical Defence Gained Per Level
    initMagDef      - Level 1 Magic Defence
    incMagDef       - Magical Defence Gained Per Level
    numUnitBlock    - ??
    moveSpeed       - Movement Speed
    attackSpeed     - Attack Speed
    skillSpeed      - Skill Attack Speed
    attackRange     - Attack Range
    skillRange      - Skill Attack Range
    evadePercent    - Evade Chance
    blockPercent    - Block Change
    criticalPercent - Critical Hit Chance
    criticalDamage  - Critical Hit Damage
    splashRange     - Splash Range
    splashDamage    - Splash Damage
    specialSkill    -
    passiveSkill    -
    reviveTime      -
    bloody          -
    explodeDie      -
    des             -
    message         -
    skillList       -
    powerList       -
    rank            -
    sex             -
    orthoGrade      -
    shop            -
    showBook        -
    ratingPosition  -
    trans           -
    material1       -
    material2       -
    material3       -
    starBuff        -
    jewelBuff       -
    groundAir       -
    offlineSpeed    -
    offlineTime     -
    hasHeart        -
    canDetect       -
    cloaking        -
    starBuffFromPet - 
    isHonor         -
    honorNumber     -
```
