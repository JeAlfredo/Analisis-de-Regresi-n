# Analisis-de-Regresi-n
Trabajos 
############### DIA 1 ##################
####### 1.- INTRODUCCIÓN A R
#podemos ocupar R como calculadora
#R sabe cuanto es pi
pi#R me genera el número 
##Variables en R 
##Operaciuones aritmeticas
a <- 4
b <- 3
a + b 
suma <- a + b
suma 

##Operaciones de comparación
a > b #  ¿a es mayor que b?
a >= a # a es mayor o igual que a   
a <= b
a == b # ¿a es igual que b?
a == 4 
a != b # ¿a es diferente a b?

##Concepto de función
x <- abs  (-2.5) # abs es la funvión del valor absoluto 
x
help (abs) #pedir ayuda en R

##Para asignar valores a variable en R se usa una <-
x <- "hola"
z <- 6
ciudad <- "Toluca" #Una entrada 
nombres <- c("Karla","Rodrigo", "Miguel", "Samuel") #Caracter de 4 entradas 
edad <- c(28,17,49,31) #Numerico y 4 entradas
# Se utiliza la función class para para preguntarle a R que tipo de variable es 
class (nombres)
class (edad)
base1 <- data.frame (nombres,edad)
View(base1)#Ver la base de datos 
ls(base1) ### ver lista de variables de base 1

base1$edad #Para conocer los datos de la variable
      #Edad de la base1
sexo <- c(2, 1, 1, 1)
base2 <- data.frame (nombres,edad,sexo)
View(base2)
table (base2$sexo)
table (base2$edad)
palumnos <- c(40, 120, 60, 80)
etiq <- c("act", "eco", "rei", "neg")
pie(palumnos)
pie(palumnos,etiq)
pie(palumnos, etiq, main=
      "Gráfica de pie de 
    la facultad de economía", 
    sub = "Fuente: Facultad de economía", 
    col = c("blue", "red", "pink", "yellow"),
    radius = 1.2, clockwise = FALSE)
