# Database Auto_usate

## (table) Cars

- id                    BIGINT NOTNULL AUTO_INCREMENT PRIMARY KEY
- descrizione           TEXT
- marca                 VARCHAR(40) NOTNULL
- modello               VARCHAR(100) NOTNULL
- versione              VARCHAR(100) NULL
- anno immatric.        YEAR NOTNULL
- prezzo                FLOAT(6,2) NOTNULL
- chilometraggio        INT NOTNULL
- cilindrata            SMALL NOTNULL
- n. cilindri           TINYINT NULL 
- peso a vuoto          SMALL NULL
- potenza               SMALL <!-- cv/kw --> NOTNULL
- alimentazione         VARCHAR(100) NOTNULL
- consumo               VARCHAR(100) NOTNULL
- classe emissioni      VARCHAR(20) NOTNULL           
- cambio                VARCHAR(20) NULL 
- trazione              VARCHAR(20) NOTNULL
- numero porte          TINYINT NULL 
- numero posti          TINYINT NULL 
- colore                VARCHAR(20) NOTNULL
- numero proprietari    TINYINT NULL 
- nazionalit√†           VARCHAR(50) NOTNULL
- climatizzatore        BOOLEAN 
- ABS                   BOOLEAN 
- antifurto             BOOLEAN               
- airbag frontali       BOOLEAN 
