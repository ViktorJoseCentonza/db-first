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
-classe euro ✔
-tipologia alimentazione ✔
-consumi (km/l) ✔



#table columns

-id - primary key - auto_increment - NOT NULL
-general_condition - TINYINT - NOT NULL
-owners_amount - TINYINT - NOT NULL
-km - INT - NOT NULL
-brand - VARCHAR(30) - NULL
-model - VARCHAR(30) - NULL
-production year - YEAR
-displacement - SMALLINT - NULL
-power_hp - SMALLINT - NULL
-transmission - VARCHAR(15) - NOT NULL
-gears - TINYINT - NULL
-traction - VARCHAR(4) - NULL
-weight - SMALLINT - NULL
-EURO - VARCHAR (10) - NOT NULL
-fuel_type - VARCHAR(15) - NOT NULL
-fuel_consumption - DECIMAL(3,1) - NULL