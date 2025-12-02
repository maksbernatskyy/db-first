# DB Schema

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Table name: cars (entity name: car)

Columns:

- id BIG PK AI NOT NULL
- brand VARCHAR(100) NOT NULL
- model VARCHAR(100) NOT NULL
- registration_year YEAR NOT NULL
- license_plate CHAR(7) UNIQUE, NOT NULL
- km INT NOT NULL DEFAULT(0)
- fuel_type VARCHAR(20) NOT NULL
- price DECIMAL(10, 2) NOT NULL
