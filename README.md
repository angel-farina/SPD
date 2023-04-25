## Integrantes

    Aldana Colomer
    Lucía Corbo
    Di girolamo Matias
    Angel Farina
    Juan Clemente

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

## 🤖 Link al proyecto

   [proyecto](https://www.tinkercad.com/things/9i6uA1OmOEe-copy-of-ejercicio-4-2/editel?sharecode=JiKHCeYjMAWXr09GrSCSp3lAyFiopx7qNBOvKjX8blA)
