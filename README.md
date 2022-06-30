# Permanente-2.c-
Convertir un Número Entero a un Numeral Romano
Primero definimos una función que será llamada conversion_entero_romano(entero):
Luego elaboramos dos listas
	numeros = [1000, 900, 500, 400, 100, 90, 50, 40, 10, 9, 5, 4, 1]
La siguiente lista tendrá una equivalencia con la primera
    	numerales = ['M','CM', 'D', 'CD', 'C', 'XC','L', 'XL', 'X', 'IX', 'V', 'IV', 'I']
Definimos una variable que va a contener el resultado
	numeral = ''
otra variable auxiliar que será i
 	i = 0
el entero que introduce el usuario será mayor a 0, si se cumple la funcion se realizan las siguientes operaciones 
	while entero > 0:
        for _ in range(entero// numeros[i]):
            numeral += numerales[i]
            entero -= numeros[i]
se usa para ir reduciendo el valor que el usuario pasa como numero entero, entonces en este ciclo for se va a lograr encontrar todas las cadenas que cumplan esa condición
        i += 1
al final retornamos el numeral
	return numeral
imprimos el resultado: 
print(convertion_entero_romano(x))
agregandole un valor numerico a x 
