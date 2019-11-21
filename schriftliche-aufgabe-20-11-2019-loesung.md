


> Written with [StackEdit](https://stackedit.io/).
Geschrieben in Markdown

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
  
   __________.______.__________("Hello World");
  }
}
```
### 2
Vervollständigen Sie

```java

   _____ Ich bin ein einzeiliger Kommentar
       
   _____ Ich bin ein
       mehrzeiliger Kommentar ____
```
## Variablen

### 1
Erstellen Sie eine Variable(deklarieren): ```carName``` und initialisieren Sie diese mit dem Wert: ```Volvo```

```java

___________  ___________ = ______________ ;
 ```

### 2
Erstellen Sie eine Variable ```maxSpeed``` und initialisieren Sie diese mit dem Wert: ```120```

```java

 _____  ____________ =__________;
 ```
### 3
Lassen Sie die Summe von  ```5 + 10 ```, mit der Hilfe der 2 Variablen  ```x ``` und  ```y ``` anzeigen.

 ```java
 
_____  ___  = ____;
 int y = 10;
 System.out.println(x + y);
  ``` 

### 4
Erstellen Sie eine Variable ```z```. ```z``` ist dabei die Summe aus ```x``` und ```y```.
Geben Sie das Resultat auf der Konsole aus.

```java
int x = 5;
int y = 10;

______  ____ = ______ +  ______;

System.out.println(____);
```

### 5
```java

_____ x = 5___ y = 6 ____ z = 50;
System.out.println(x + y + z);
```

## Datentypen

### 1
Vervollständigen Sie den Code

```java

 __________ myNum = 9;
 
 __________ myFloatNum = 8.99f;
 
 __________ myLetter = 'A';
 
 __________ myBool = false;
 
 __________ myText = "Hello World";


```

### 2
`byte`, `short`, `int`, `long`, `float`, `double`, `boolean` and `char` heißen:

```

 _________________ Datentypen.
```

### 3
Wandeln Sie das Attribut `myDouble` in ein `int` um
```

double myDouble = 9.78;

int myInt = _________ myDouble;
```
### 3.1
welchen Wert besitzt myInt? Mit kleiner Erklärung

```

Antwort:



```

## Operatoren

### 1

Multiplizieren Sie `10` mit `5`, und geben Sie das Resultat auf der Konsole aus.


```

Antwort:



```
### 2
Dividieren Sie `10` durch `5` und geben Sie das Resultat auf der Konsole aus.

```

Antwort:



```

### 3
Inkrementieren den Wert von x um eins nach oben: (inkrementieren = Schrittweisen Erhöhung oder Verminderung einer Größe oder Variablen)

```
int x = 10;

x______ ;
//alternativ:

_______x;
```
### 4
Addieren Sie in der Kurzschreibweise `5` zur Variablen `x`

```java
int x = 10;

x _______ 5;

```

## String
### 1
Vervollständigen Sie den Code, damit die Variable `greeting` vom Typ`String` mit dem Wert`Hello` initilaisiert wird.

```java

____________ ___________ = _____________ ;


```
### 2
Vervollständigen Sie den Code. Ziel ist auf der Konsole die Länge der Variablen `txt`auszugeben

```java
String txt = "Hello";

System.out.println(____.___________);

```
### 3
Ergänzen Sie den Code so, dass auf der Konsole `Hello World!`ausgegeben wird

```java
String hello = "Hello ";



System.out.println(hello ___ ___________);

```

## Boolische Werte

### 1

Vervollständigen Sie den Code, damit auf der Console

>true 
>
>false

ausgegeben wird.


```java
 __________ isJavaFun = _______;
 
 __________ isFishTasty = _________;
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

System.out.println(x _____ y  );

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

____ (x ____ y) {
  System.out.println("Hello World");
}



```

### 2
Print `x und y sind gleich`, falls `x`und `y`gleich sind, andernfalls print `x und y sind ungleich`

```java

int x = 50;
int y = 50;
____ (x _____ y) {
  System.out.println("Yes");
} _____  {
  System.out.println("No");
}


```

### 3
print `1` wenn `x` gleich `y` ist, print `2` wenn `x` größer als `y`ist. Ansonsten print `3`

```java


int x = 50;
int y = 50;


___ ________ {
  System.out.println("1");
  
}  ____________ {
  System.out.println("2");
  
}  _________{
  System.out.println("3");
}

```

## Schleifen
### 1
Print `i` solange `i`kleiner als `6`ist

```java

int i = 1;

________ ( ____ < _____) {
	System.out.println(i);

_______;
```

### 2

Nutzen sie eine `for`-Schleife um 5 mal `ja`auf der Console auszugeben
```java
String output = "ja";

 _______ (_____ ___ = ___; ___ < ____; _____ ) {
 
  System.out.println(_____);
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

 _______ (_____ ___ = ___; ___ < ___________; _____ ) {

System.out.println(_________________);

}
```

## Arrays
### 1
Erstellen Sie ein array vom Typ `Char` mit dem Namen`vokale`. Befüllen Sie dieses mit allen Vokalen (a, e, i .......)

```java 

_______  __________ = _____________________________



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


 _______ (_____ ___ = ___; ___ < ___________; _____ ) {

System.out.println(_________________);

}
```

### Übertragen Sie die Code fragmente sinnvoll auf Ihren PC und überprüfen Sie Ihre Antworten





