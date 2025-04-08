#task
-memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


#table name `cars`

#table columns (pseudo)

-id - primary key - auto_increment - NOT NULL  ✔
-?general state (0-10 rating?) ✔
-numero proprietari ✔
-km traveled ✔
-brand ✔
-model ✔
-production year v
-cilindrata ✔
-potenza (kw+cv) ✔
-tipo di cambio ✔
-numero marce ✔
-trazione ✔
-peso ✔
-classe euro
-tipologia alimentazione
-consumi (km/l)



#table columns

-id - primary key - auto_increment - NOT NULL
-general_condition - TINYINT - NOT NULL
-owners_amount - TINYINT - NOT NULL
-km - INT - NOT NULL
-brand - VARCHAR(30)
-model - VARCHAR(30)
-production year - YEAR
-displacement - SMALLINT
-power_hp - SMALLINT
-transmission - VARCHAR(15)
-gears - TINYINT
-traction - VARCHAR(4)
-weight - SMALLINT
-EURO - VARCHAR (10)