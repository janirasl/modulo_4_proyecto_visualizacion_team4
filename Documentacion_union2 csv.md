Vemos el documento Lifestyle_and_Health_Risk_Prediction_Synthetic_Dataset.csv :
            12 columnas y 5000 filas
            sin duplicadoss
            sin nulos
            homogeneizado

Age, habla de la edad de las personas : 0 nulos  y de tipo int .

Weight, peso de las personas calculado en kilos  es un int no tiene nulos calculado en kilos completos .

Height , alturas de la personas ,  esta en centimetros ,  es de tipo int no tien nullos.

Exercise , ejercicio que hace la persona semanalmente, 
            categorica con 4 categorias.
            valores unicos  son :
                    none,nada de ejercicio
                    low,poco ejercicio 
                    medium,
                    high

Sleep , media de las horas que se duerme por noche , tipo float 

Sugar _intake nivel de consumo de azucar, 
    categorica con 3 categorias 
                    medium,
                    low, 
                    high,
    tipo string
smoking , si fuma o no , categorica la respuesta es si o no
alcohol, si bebe o no , categorica la respuesta es si o  no 
married , casado o no , categorica la respuesta es si o no
profession, profesion de las personas, categorizada de esta manera:
                    student          644
                    farmer           639
                    driver           631
                    doctor           630
                    artist           626
                    engineer         616
                    teacher          612
                    office_worker    602

BMI , indice de masa corporal, se calcula como perso entre altura al cuadrado, tipo float
health _risk , alto o bajo riesgo de mala salud , high alto, low es bajo


Vemos el documento Comida_precios
consta de : 5 columnas
            71 filas
            no tiene nulos

    Alimento, columna de tipo string , con nombre de los alimentos
    
    Tipo columna de tipo string, categorica con 2 categorias
        Real 57.74%
        ultrra 42.25%

   Sueño columna de tipo string, categorica con 3 categorias
        malo 42.25%
        neutro 29.57%
        bueno 28.16%
    
    precio _eur_kg_l columna tipo float
        maxinmo 15.0
        minimo 0.5
        media 2.6
    
    