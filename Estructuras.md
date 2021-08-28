```python
text = "Cien años de solead"
print("si" if "años" in text else "no")
print([(letra) for letra in text])

#Longitud de una cadena
print("La palabra tiene {} caracteres".format(len(text)))
#Seleccionar ciertos caracteres [inicio:final]
print(text[0:4])
#Seleccionar desde una posicion hasta el final
print(text[4:])
#Voltear una cadena
print(text[::-1])

#Verificar si una palabra es palindroma o no
word = text.replace(" ","") #Quitar espacios
print("Es palindroma" if text[::-1] == text else "No es Palindroma")

#Numero de aparaciones de un caracter
print(text.count("e"))
#Convertir a minusculas
print(text.lower())
#Convertir a mayusculas
print(text.upper())
#Formatear cadena en tipo oración
print(text.capitalize())
#Verificar si todo el texto esta en mayusculas
print(text.isupper())
#Convertir en titulo
print(text.title())
#Inverir mayusculas y minusculas
print(text.swapcase())
#Remplazar un caracter
print(text.replace("Cien","Setenta"))

#Crear una lista vacia
lista = []
#Lista de nombres
nombres = ["Juan","Maria","Lusisa","Andres","Fernanda"]
print(nombres)
#Lista con diferentes tipos de dato
lista = [True, [1,2], "Roma", (5,6), 1.4]
print(lista)
#Obtener elementos por indice
print(lista[1][0])
print(lista[0])
#Unir dos listas
listaUnida = nombres+lista
print(listaUnida)
#Convertir cadena a lista
print(list(text))
#Imprimir lista al reves
print(nombres[::-2])

#Llenar una lista
numbers = [x for x in range(0,10)]
print(numbers)

```` 
