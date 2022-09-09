|Variable Name Provided |Source Variable Name |Derived |Type       |Description                                     |Comments                                         |
|:----------------------|:--------------------|:-------|:----------|:-----------------------------------------------|:------------------------------------------------|
|~~record_id~~              |                     |Y       |character  |Unique ID for this Record                       |                                                 |
|~~eupi~~                   |                     |Y       |character  |Encrypted UPI Number                            |                                                 |
|sequence_name          |sequence_name        |        |character  |                                                |Where a patient has multiple sequences a numeric suffix will be appended, e.g. `.1` and `.2`   |
|~~shortid~~                |shortid              |Y       |character  |The middle portion of the 3-part sequence_name  |                                                 |
|country                |country              |        |character  |                                                |                                                 |
|adm1                   |adm1                 |        |character  |                                                |                                                 |
|is_pillar_2            |is_pillar_2          |        |logical    |                                                |                                                 |
|sample_date            |sample_date          |        |date       |                                                |yyyymmdd                                         |
|epi_week               |epi_week             |        |integer    |                                                |                                                 |
|lineage                |lineage              |        |character  |                                                |                                                 |
|lineages_version       |lineages_version     |        |character  |                                                |Column is blank, set to "character" by default.  |
|~~lineage_support~~        |lineage_support      |        |character  |                                                |Column is blank, set to "character" by default.  |
|lineage_conflict       |                     |        |           |                                                |                                                 
|lineage_ambiguity_score|                     |        |           |                                                |                                                 
|scorpio_call           |                     |        |           |                                                |                                                 
|scorpio_support        |                     |        |           |                                                |                                                 
|scorpio_conflict       |                     |        |           |                                                |                                                 
|t1001i                 |t1001i               |        |character  |                                                |                                                 |
|n501y                  |n501y                |        |character  |                                                |                                                 |
|del_21765_6            |del_21765_6          |        |character  |                                                |                                                 |
|p681h                  |p681h                |        |character  |                                                |                                                 |
|e484k                  |e484k                |        |character  |                                                |                                                 |
|y453f                  |y453f                |        |character  |                                                |                                                 |
|q27stop                |q27stop              |        |character  |                                                |                                                 |
|d614g                  |d614g                |        |character  |                                                |                                                 |
|del_1605_3             |del_1605_3           |        |character  |                                                |                                                 |
|n439k                  |n439k                |        |character  |                                                |                                                 |
|mutations              |                     |        |           |                                                |                                                 
|~~variants~~               |variants             |        |character  |                                                |                                                 |
|p323l                  |p323l                |        |character  |                                                |                                                 |
|a222v                  |a222v                |        |character  |                                                |                                                 |
