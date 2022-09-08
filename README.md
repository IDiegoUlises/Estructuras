# Estructuras editar

```c++
//Se crea la estructura
struct estructura
{
  String cadena;
  int valor;
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
  variables.valor = 12; 

  //Se imprime los valores de la estructura
  Serial.println(variables.cadena);
  Serial.println(variables.valor);

  //Retardo para no llenar de mensajes el puerto serial
  delay(500);
}
```
