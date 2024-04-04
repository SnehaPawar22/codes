# codes

IF(NOT(ISBLANK(Birthdate)), 
   FLOOR((TODAY() - Birthdate) / 365.25), 
   NULL)
