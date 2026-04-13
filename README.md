# Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


# Iniziamo trovando il nome per la nostra tabella, in questo caso caso parliamo di automobili

# TABLE NAME
- cars_table

# Possiamo ora iniziare a definire che tipologia di informazioni sono necessarie nel nostro DB

# DB INFOS

- car_Id 
- car_Brand
- car_Model
- car_Image
- car_Price
- car_Km
- car_Fuel_Type
- is_Automatic
- car_Optional
- is_New

# Trovati gli elementi fondamentali, procediamo a dargli una tipologia di dato 

- car_Id (numero: INT - attributi: PRIMARY_KEY, AUTO_INCREMENT )
- car_Brand ( testo: VARCHAR(50), attributi: NOTNULL )
- car_Model ( testo: VARCHAR(50), attributi: NOTNULL )
- car_Image ( testo: VARCHAR(50), attributi: DEFAULT (http://Placeholder.boolean) )
- car_Price (numero: DECIMAL(5,3), attributi: NOTNULL )
- car_Km (numero: DECIMAL (10,2), attributi: NOTNULL ) 
- car_Fuel_Type (testo: VARCHAR(15), attributi: NOTNULL)
- is_Automatic (numero: TINYINT (0), attributi: NOTNULL)
- car_Optional (testo: VARCHAR(255), attributi: NULL)
- is_New (numero: TINYINT(0), attributi: NOTNULL)