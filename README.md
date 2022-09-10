# Estructuras

```c++
//Se crea la estructura
struct estructura
{
  String cadena;
  int entero;
};

void setup()
{
  Serial.begin(9600);
}

void loop()
{
  //Se declara la estructura y se le asigna un nombre
  estructura variables;

  //Se le asigna el valor a las variables
  variables.cadena = "Hola Mundo";
  variables.entero = 12;

  //Se imprime los valores de la estructura
  Serial.println(variables.cadena);
  Serial.println(variables.entero);

  //Retardo de 5 segundos
  delay(5000);
}
```

* Las estructuras es una agrupacion de datos, los cuales pueden ser de diferentes tipos
