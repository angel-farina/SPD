## Integrantes

    Aldana Colomer
    Lucía Corbo
    Di girolamo Matias
    Juan Clemente
    Angel Farina

## Proyecto: Dojo Número Uno 

## Descripción

1- El semáforo tiene que tener 2 leds de cada color como mínimo, 
en caso de que uno se  rompa. 
2- Tiene que implementar los tiempos correctos como se detallan 
a continuación. 
3- El verde dura 5 segundos. 
4- El amarillo dura 3 segundos. 
5- Rojo dura 5 segundos. 
6- Tiene que tener señalización para personas no videntes como 
se detalla a  continuación. (Buzzer o piezo)
7- Durante el rojo: Tiene que sonar 2 vez por segundo en un
tono FUERTE. 

## Función principal

Esta funcion se encarga de asignar el tono que tendra el Buzzer.

(Breve explicación de la función)

void BUZZER_ON(int estado)
{
  if (estado == HIGH)
  {
  tone(BUZZER_PIN, 1000);
  }
  else
  {
    noTone(BUZZER_PIN);
  }
}

void EncenderBinario(int estado3, int estado2,int estado1,int estado0)
{
  digitalWrite(B3,estado3);
  digitalWrite(B2,estado2);
  digitalWrite(B1,estado1);
  digitalWrite(B0,estado0);
}


## 🤖 Link al proyecto

   [proyecto](https://www.tinkercad.com/things/9i6uA1OmOEe-copy-of-ejercicio-4-2/editel?sharecode=JiKHCeYjMAWXr09GrSCSp3lAyFiopx7qNBOvKjX8blA)
