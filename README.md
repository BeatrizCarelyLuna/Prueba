# Prueba
```diff
+a
+green
+text in orange
+ text in gray
@@ text in purple (and bold)@@
```

```json
 adn.count('g')
```
```html
   https://stackoverflow.com/questions/11509830/how-to-add-color-to-githubs-readme-md-file
```
```js
    adn.count('g')
```
```css
adn.count('g')
```
// etc.

ggghhh
jjjj
```python
adn.count('g')
```

$${\color{red}Red}$$



# Notas-redes
Estas notas sirven para construir redes desde archivos, están organizadas de la siguiente forma:
Estas notas sirven para construir redes desde archivos, están organizadas de la siguiente forma:
- $${\color{lightblue}\textrm{Instalación de Phyton 3.13.0 para Windows y para Mac}}$$
- $${\color{lightblue}Instalación de pip o pip3}$$
- $${\color{lightblue}Nociones básicas de Python}$$
- $${\color{lightblue}Construcción de gráficas con NetworkX}$$
- $${\color{lightblue}Medidas usuales de redes}$$
  
$${\color{lightblue}Instalación de Phyton 3.13.0 para Windows y para Mac}$$

Ir a la siguiente liga y descargar la última versión de python

https://www.python.org/downloads/

  Instalación de pip o pip3

  Nociones básicas de Python


  Construcción de gráficas con NetworkX


  Medidas usuales de redes.


> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.


####Desde aquí

$${\color{lightblue}\textrm{Variables}}$$

No se necesitan declarar las variables

```python
x=13
y=x+3.0
```

Asignación múltiple

```python
a,b=4,5
```

Tipos de variable
```python
type(y) 
float(x)
int(y)
```

En python una cadena se declara con comilla simple 
```python
adn='agtcaggagttaaccata'
adn_corto='cgta'
```
o se declara con comillas
```python
frase="I can’t Believe It, It’s amazing"
texto='UPN 201, Educar para transformar'
```

```python
adn+adn_corto
texto*3
frase.lower()
len(adn)
adn.count('g')
adn.replace('g','TAZA')
'a' in adn
texto.split()
texto.split(',')
cadena='3*una,*español-ingles,*algo'
cadena.split('*')
```

> [!IMPORTANT]
> Ejercicio
> 
> Escribir una cadena con las letras a,g,t,c y calcular el porcentaje de ocurrencia de a y c.
>
> Intercambiar la a por la c y la c por la a.

> [!NOTE]
> El uso de los índices es similar tanto para listas, cadenas, etc. 


```python
# toma en la cadena desde el índice inicio hasta el indice fin-1 
pos='Escuela de Otoño de Biología Matemática'
# saltos dice de cuanto en cuanto se van tomando. Si no se pone, se va de uno en uno
pos[inicio:final:saltos]
```

```python 
pos[0]
pos[1:4]
pos[5:2]
pos[5:2:-1]
pos[1:]
pos[1:100]
pos=[::-1]
pos[:-3]
pos[-3:]
```

$${\color{lightblue}\textrm{Listas}}$$

```python
#colección de objetos
L1=[2,7,11,-3]
#distintos tipos de elementos
L2=[5,'gato',1,0]
#puede estar vacia
c=[]
#puede ser una lista de listas 
Listas=[12,[‘a’,1,2,3],[b,[c,14]]]
#genera una lista desde inicio hasta final menos uno.
#paso si se da debe ser entero,indica el tamaño de paso.
range(inicio,final,paso)
```

tutorial 
https://recursospython.com/guias-y-manuales/listas-y-tuplas/

```python
L1+L2
L2*3
x=L2[-1]
z=L1[2:4]
L1[0]=250
len(Listas)
Listas[1][2]
L1.index(11)
L2.append(-12)
```

$${\color{lightblue}\textrm{Tuplas}}$$






 










| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |



