# HelloWorld_301_Nov30
Aprender la bases de github

# Encabezado
## Manuel Arias Alcocer
### Carrera - ITC

# Tipos de Letra

**Bold**
*Italica*
🌆🎄

# Lista Ordenada
1. Pizza Pepperoni 🍕
2. Pizza Queso 🧀
3. María, Héctor, Luis, Diego, (Encargados)

# Lista desordenada actividad en vacaciones
- Familia
- Dormir
- Ver series(Programación Orientada a Objetos)
- Estudiar c++
- Chambear $$$ (el esfuerzo que se requere para ganar 800 pesos)
- Fiestas
- Ir a Linares - Comprar Glorias de Linares - Visitar a Chava
- Cocinar
- Ejercicio

----------------------------------------------------------------

# Codigo

```c++
#include "Circulo.h"

    //Metodos Constructores
    Circulo::Circulo(){
    Coordenada c{1,1};

    centro = c;
    radio = 1;
    }
    Circulo::Circulo(Coordenada _centro, int radio){
    centro = _centro;
    radio = _radio;
    }


    //Metodos Modificadores -set
    void Circulo::setCentro(Coordenada _centro){
    centro = _centro;
    }
    void Circulo::setRadio(int _radio){
    radio = _radio;
    }


    //Metodos de Acceso
        Coordenada getCentro(){
    return centro;
    }
    int getRadio(){
    return radio;
    }


    //Metodo str
    string Circulo::str(){
    return "Centro = " + centro.str() + "Radio = " + to_string(radio);
    }
```

# 1. [Markdown](https://www.markdownguide.org/cheat-sheet/)
[Link - ...](https://www.markdownguide.org/cheat-sheet/)

# Imagen
![imagen](https://www.gardeningknowhow.com/wp-content/uploads/2020/11/christmas-tree-400x300.jpg)

![pizza](https://cdn2.cocinadelirante.com/1020x600/filters:format(webp):quality(75)/sites/default/files/images/2019/11/como-hacer-pizza-hawaiana.jpg)

# Planecion de estudiar C++

| Fecha | Description |
| ----------- | ----------- |
| Diciembre | Apuntes 1 y 2 |
| Enero | POO - Presentacion 1-2 - programar al menos 3 hrs a la semana  |
| Febrero | POO - Presentacion 3 - programar al menos 3 hrs a la semana  |
| Marzo | POO - Presentacion 4 - programar al menos 3 hrs a la semana  |
