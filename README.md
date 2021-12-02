## Hello-World
### My Great Heading {#9879}
# Hola me llamo Iván Alejandro Ortiz Valadez
## Hoy es 02/12/21
### H3
Este es mi primer repositorio para la clase TC1033


**bold text**

	*italicized text*
  *esto es texto en italica*
  
  
> blockquote
    
1. naranja 
2. Platano
3. Limon

- Roca
- Zapato
- Mochila

```````
#include "Episodio.h"
#include <iostream>
//Iván Alejandro Ortiz Valadez --- A00834559
Episodio::Episodio(){
    titulo = "El ataque de los booleanos";
    temporada = 1;
    calificacionPromedio = 100;

}

Episodio::Episodio(std::string _titulo, int _temporada, double _calificacion){
    titulo = _titulo;
    temporada = _temporada;
    calificacionPromedio = _calificacion;

}
Episodio::~Episodio(){
    std::cout << "Se destruyo un objeto Episodio!\n";
}
//Metodos modificadores-cambiar el valor del atributo
void Episodio::setTitulo (std::string _titulo){
    titulo = _titulo;
}
void Episodio::setTemporada (int _temporada){
    temporada = _temporada;
}
void Episodio::setCalificacion (double _calificacion){
    calificacionPromedio= _calificacion;
}


//Metodos de acceso-retorna el valor de un atributo
std::string Episodio:: getTitulo(){
    return titulo;
}
int Episodio::getTemporada(){
    return temporada;
}

double Episodio::getCalificacion(){
    return calificacionPromedio;
}


//Metodo que retome todos los atributos concatenados y separados por,
std::string Episodio::str(){
    return titulo + ',' + std::to_string(temporada) + ',' + std::to_string(calificacionPromedio);
}
```````

![alt text](foto.jpeg)



| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |


```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
---

[Referencia](https://www.youtube.com
Hola mucho gusto . [^1]

[^1]: Esta es una nota de pie.

Anonadado
: Dícese de un sujeto que se encuentra en total asombro 

~~Dios no existe~~.

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

