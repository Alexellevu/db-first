# Database Libreria

## (table) Cars

- id                    BIGINT NOTNULL
- descrizione           TEXT
- marca                 VARCHAR(40) NOTNULL
- modello               VARCHAR(100) NOTNULL
- versione              VARCHAR(100) NULL
- anno immatric.        YEAR NOTNULL
- prezzo                FLOAT() NOTNULL
- chilometraggio        INT NOTNULL
- cilindrata            SMALL NOTNULL
- cilindri              TINYINT NULL 
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
- nazionalità           VARCHAR(50) NOTNULL
           
