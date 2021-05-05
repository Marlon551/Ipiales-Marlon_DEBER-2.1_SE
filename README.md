# Ipiales-Marlon_DEBER-2.1_SE
Ipiales Marlon_DEBER 2.1_SE
/*
*CAPITULO II: PUERTOS DIGITALES
*DEBER 2.1: Manejo de puertos configurados como salidas
*OBJETIVO: Endencer y apagar leds de forma sincronizada
*NOMBRE: Marlon Ipiales 
*/

//Variables: Numericas enteras (int), Decimales (float), Caracteres (chart)
#define led1 8 //uso de #define, es una varieble que no puede alterar su valor, no existe una depuracion de errores 
int led2 = 9;  //se puede considerar como una variable normal, no es muy recomendable  
const int led3 = 10; //variable constante, es la recomendable
const int led4 = 11;
void setup() {
  pinMode(led1,OUTPUT); //declaro el pin 8 como salida
  pinMode(led2,OUTPUT); //declaro el pin 9 como salida
  pinMode(led3,OUTPUT); //declaro el pin 10 como salida
  pinMode(led4,OUTPUT); //declaro el pin 11 como salida
}
void loop() {
  digitalWrite(led1, HIGH); //Enviando 5V al pin8
  delay(500); //Se detiene el microcontrolador por medio segundo
  digitalWrite(led1, LOW); //Envia 0V al pin8
  delay(500); //Se detienen el microcontrolador por medio segundo
  digitalWrite(led2, HIGH);
  delay(500); //Se detienen el microcontrolador por medio segundo
  digitalWrite(led2, LOW); 
  delay(500);
  digitalWrite(led3, HIGH);
  delay(500); //Se detienen el microcontrolador por medio segundo
  digitalWrite(led3, LOW); 
  delay(500);
  digitalWrite(led4, HIGH);
  delay(500); //Se detienen el microcontrolador por medio segundo
  digitalWrite(led4, LOW); 
  delay(500);
}
