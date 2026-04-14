# Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


# Iniziamo trovando il nome per la nostra tabella, in questo caso caso parliamo di automobili

# TABLE NAME
- cars

# Possiamo ora iniziare a definire che tipologia di informazioni sono necessarie nel nostro DB

# DB INFOS

- id 
- brand
- model
- image
- price
- km
- fuel_type
- is_automatic
- optional
- is_new

# Trovati gli elementi fondamentali, procediamo a dargli una tipologia di dato 

- id (numero: INT - attributi: PRIMARY_KEY, AUTO_INCREMENT, NOTNULL, UNIQUE )
- brand ( testo: VARCHAR(50), attributi: NOTNULL )
- model ( testo: VARCHAR(50), attributi: NOTNULL )
- image ( testo: VARCHAR(50), attributi: DEFAULT (http://Placeholder.boolean) )
- price (numero: DECIMAL(5,3), attributi: NULL )
- km (numero: DECIMAL (10,2), attributi: NULL ) 
- fuel_type (testo: VARCHAR(15), attributi: NOTNULL)
- is_automatic (numero: TINYINT (0), attributi: NOTNULL)
- optional (testo: VARCHAR(255), attributi: NULL)
- is_new (numero: TINYINT(0), attributi: NOTNULL)