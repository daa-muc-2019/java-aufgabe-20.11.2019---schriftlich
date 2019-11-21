


> Written with [StackEdit](https://stackedit.io/).
Geschrieben in Markdown

um Markdown Datein zu speichern: .md

>Aufgabe verfügbar auf:
>
>https://github.com/daa-muc-2019/java-aufgabe-20.11.2019---schriftlich
>
>https://www.w3schools.com/java/java_exercises.asp


# Aufgabe: Code auf Papier

## 1. Java Syntax

### 1
Vervollständigen Sie den Code um auf der Konsole 
```Hello World!``` zu erhalten

```java
public class MyClass {
  public static void main(String[] args) {
  
   System.out.print("Hello World");
  }
}
```
### 2
Vervollständigen Sie

```java

   // Ich bin ein einzeiliger Kommentar
       
   /* Ich bin ein
       mehrzeiliger Kommentar */
	   
```
## Variablen

### 1
Erstellen Sie eine Variable(deklarieren): ```carName``` und initialisieren Sie diese mit dem Wert: ```Volvo```

```java

String  carName = "Volvo" ;
 ```

### 2
Erstellen Sie eine Variable ```maxSpeed``` und initialisieren Sie diese mit dem Wert: ```120```

```java

 int  maxSpeed =120;
 ```
 
### 3
Lassen Sie die Summe von  ```5 + 10 ```, mit der Hilfe der 2 Variablen  ```x ``` und  ```y ``` anzeigen.

 ```java
 
int  x  = 5;
int y = 10;
 System.out.println(x + y);
  ``` 

### 4
Erstellen Sie eine Variable ```z```. ```z``` ist dabei die Summe aus ```x``` und ```y```.
Geben Sie das Resultat auf der Konsole aus.

```java
int x = 5;
int y = 10;

int z = x + y;

System.out.println(z);
```

### 5
```java

int x = 5, y = 6, z = 50;
//alternative
int x = 5; int y = 6; int z = 50;

System.out.println(x + y + z);
```

## Datentypen

### 1
Vervollständigen Sie den Code

```java

 int myNum = 9;
 
 float myFloatNum = 8.99f;
 
 char myLetter = 'A';
 
 boolean myBool = false;
 
 String myText = "Hello World";


```

### 2
`byte`, `short`, `int`, `long`, `float`, `double`, `boolean` and `char` heißen:

```

 primitive Datentypen.
```

### 3
Wandeln Sie das Attribut `myDouble` in ein `int` um
```

double myDouble = 9.78;

int myInt = (int)  myDouble;
```
### 3.1
welchen Wert besitzt myInt? Mit kleiner Erklärung

```

Antwort:	
			- 9

			- int entspricht ganzer Zahl
			
			- Alles nach dem `.` wird abgeschnitten
			



```

## Operatoren

### 1

Multiplizieren Sie `10` mit `5`, und geben Sie das Resultat auf der Konsole aus.


```java

//Antwort:	
	
System.out.print(5*10);

//oder:

int result = 5*10;

System.out.println(result);



```
### 2
Dividieren Sie `10` durch `5` und geben Sie das Resultat auf der Konsole aus.

```java
//Antwort:	
	
System.out.print(5/10);

//oder:

int result = 5/10;

//kein backslash: \

System.out.println(result);
```

### 3
Inkrementieren den Wert von x um eins nach oben: (inkrementieren = Schrittweisen Erhöhung oder Verminderung einer Größe oder Variablen)

```
int x = 10;

x++;

//alternativ:

++x;

x = x + 1;

x += 1;

```
### 4
Addieren Sie in der Kurzschreibweise `5` zur Variablen `x`

```java
int x = 10;

x += 5;

```

## String
### 1
Vervollständigen Sie den Code, damit die Variable `greeting` vom Typ`String` mit dem Wert`Hello` initilaisiert wird.

```java

String greeting = "Hello";


```
### 2
Vervollständigen Sie den Code. Ziel ist auf der Konsole die Länge der Variablen `txt`auszugeben

```java
String txt = "Hello";

System.out.println(txt.length());

```
### 3
Ergänzen Sie den Code so, dass auf der Konsole `Hello World!`ausgegeben wird

```java
String hello = "Hello ";
// String world = "World!;


System.out.println(hello + "World!");

```

## Boolische Werte

### 1

Vervollständigen Sie den Code, damit auf der Console

>true 
>
>false

ausgegeben wird.


```java
 boolean isJavaFun = true;
 
 boolean isFishTasty = false;
 
System.out.println(isJavaFun);
System.out.println(isFishTasty);
```

### 2
Vervollständigen Sie den Code, damit auf der Console

>true

ausgegeben wird.

```java
int x = 10;
int y = 9;

System.out.println(x > y  );

```

## if...Else

### 1
Geben Sie

>Hello World
>

auf der Konsole aus, wenn `x`größer ist als `y`

```java
int x = 50;
int y = 10;

if (x > y) {
  System.out.println("Hello World");
}



```

### 2
Print `x und y sind gleich`, falls `x`und `y`gleich sind, andernfalls print `x und y sind ungleich`

```java

int x = 50;
int y = 50;

if (x == y) {
  System.out.println("Yes");
} else  {
  System.out.println("No");
}


```

### 3
print `1` wenn `x` gleich `y` ist, print `2` wenn `x` größer als `y`ist. Ansonsten print `3`

```java


int x = 50;
int y = 50;


if (x == y) {
  System.out.println("1");
  
}  else if (x>y) {
  System.out.println("2");
  
}  else{
  System.out.println("3");
}

```

## Schleifen
### 1
Print `i` solange `i`kleiner als `6`ist und mind. 4x ausgeführt wird (kein endlos Loop erstellen)

```java

int i = 1;

while ( i < 6) {
	System.out.println(i);

i++;
// i = i + 1;
// i += 1;

}
```

### 2

Nutzen sie eine `for`-Schleife um 5 mal `ja`auf der Console auszugeben
```java
String output = "ja";

 for (int i = 0; i < 5; i++ ) {
 
  System.out.println(output);
}
```

### 3
geben ist ein Array mit den Werten `Volvo`, `BMW`, `Ford`
Geben Sie innerhalb einer Schleife folgenden Inhalt auf der Konsole aus:
> Volvo
> BMW
> Ford

```java
String[] cars = {"Volvo", "BMW", "Ford"};

//					Wert: 3
for (int i = 0; i < cars.length; i++ ) {

System.out.println(cars[i]);

}
```

## Arrays
### 1
Erstellen Sie ein array vom Typ `Char` mit dem Namen`vokale`. Befüllen Sie dieses mit allen Vokalen (a, e, i .......)

```java 

char[]  vokale = {'a', 'e', 'i', 'o', 'u'};



```

#### 1.1

Geben sie die Vokale auf der Console im folgenden Format aus:
>a
>e
>i
>.
>.
>.
```java


for (int i = 0; i < vokale.length; i++ ) {

System.out.println(vokale[i]);

}
```

### Übertragen Sie die Code fragmente sinnvoll auf Ihren PC und überprüfen Sie Ihre Antworten





