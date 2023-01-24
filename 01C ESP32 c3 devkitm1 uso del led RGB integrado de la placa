/*
    COMO CONTROLAR EL LED RGB INTEGRADO EN LA PLACA
    CODIGO ORIGINAL DE ADAFRUIT 
    MODIFICADO POR : JOSE MARIA MENDEZ RUIZ
    ENERO 2023
    CODIGO LIBRE PARA UTILIZAR COMO QUIERAS

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
*/


#include <Adafruit_NeoPixel.h> //Libreria necesaria, instalarla desde el gestor de librerias

Adafruit_NeoPixel LED_RGB(1, 8, NEO_GRBW + NEO_KHZ800);  // Creamos el objeto que manejará el led rgb

void setup() {
  LED_RGB.begin();            // Inicia el objeto que hemos creado asociado a la librería NeoPixel 
  LED_RGB.setBrightness(150); // Para el brillo del led
}

void loop() {
  LED_RGB.setPixelColor(0, uint32_t(LED_RGB.Color(255,   0,   0))); // Encendemos el led rojo
  LED_RGB.show(); // Enciende el color
  delay(1000);    // Pausa de un segundo
  
  LED_RGB.setPixelColor(0, uint32_t(LED_RGB.Color(  0, 255,   0))); // Encendemos el led verde
  LED_RGB.show(); // Enciende el color
  delay(1000);    // Pausa de un segundo
  
  LED_RGB.setPixelColor(0, uint32_t(LED_RGB.Color(  0,   0, 255))); // Encendemos el led azul
  LED_RGB.show(); // Enciende el color
  delay(1000);    // Pausa de un segundo

}
