# Concessionario

## [Table] Automobili usate

- **id** | BIGINT | PRIMARY_KEY NOTNULL AUTO_INCREMENT UNIQUE
- **foto** | VARCHAR(255) | NULL
- **marca** | VARCHAR(20) | NOTNULL
- **modello** | VARCHAR(20) | NOTNULL
- **anno_di_uscita** | YEAR | NULL
- **anno_immatricolazione** | YEAR | NOTNULL
- **carburante** | VARCHAR(20) _(mild-hybrid|elettrica|benzina)_ | NULL
- **segmento** | VARCHAR(10) _(berlina|suv|utilitaria)_ | NULL
- **n_porte** | TINYINT | NULL
- **optionals** | VARCHAR(255) | NULL
- **tipo_di_cambio** | VARCHAR(10) _(manuale|automatico)_ | NULL
- **cilindrata** | FLOAT(2,1) | NULL
- **cavalli** | SMALLINT | NULL
- **chilometraggio** | SMALLINT | NULL
- **targa** | VARCHAR(10) | NULL
- **n_proprietari** | TINYINT | NULL
- **anni_garanzia** | TINYINT | NULL
- **disponibilità** | TINYINT _(0|1)_ | DEFAULT(1)
- **prezzo** | DECIMAL(7,0) _(999.999)_ | NULL
- **sconto** | TINYINT | NULL
- **controlli_effettuati** | VARCHAR(255) | NULL
- **condizione_usato** | VARCHAR(10) | NULL
- **note** | TEXT | NULL
