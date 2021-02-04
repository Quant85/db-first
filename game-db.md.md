

# database name: GameStop
# nome tabelle: Games
- id BIGINT PRIMARYKEY NOTNULL AUTO_INCREMENT UNIQUE
- SKU string VARCHAR(10) NOTNULL UNIQUE
- title string VARCHAR (30) NOTNULL
- description TEXT NULL
- platform string VARCHAR(20) NOTNULL
  publication_date YEAR NOTNULL
- genre string VARCHAR(15) NOTNULL
- price number FLOAT(5,2) NULL
- software_house string VARCHAR(50) NULL
- availability number TINYIT NULL DEFAULT(0)
- cover_image string VARCHAR(250) NULL
- pegi number TINYIT NOTNULL
- language string VARCHAR(20) NOTNULL
- game_engine string VARCHAR(20) NULL
- stock_availability number SMALLINT NULL DEFAULT(0)
- type string VARCHAR(25) NULL
- Release_Date data DATETIME NOTNULL
- edited data DATETIME NULL