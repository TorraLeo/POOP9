@startuml
class Animal
{
- nombre: String
- lugarOrigen: String
- color: String
+sonido(Sting): void
+comer(): void
}

class AnimalAcuatico{
    - numeroAletas: int
    +nadar(): void
    +comer(): void
}

class AnimalTerrestre{
    - numeroPatas: int
    +comer(): void
    +correr(): void
}

class AnimalAereo{
    - numeroAletas: int
    +volar(): void
    +comer(): void
}

class Ballena{
    - largo: int
    +pelearConPinocho(): void
}

class Perro{
    - colorCollar: String
    +hacerTrucos(): void
}

class Pajaro{
    - tipoPico: String
    +recolectarRamas(): void
}

Animal <-- AnimalAcuatico
AnimalAcuatico <-- Ballena

Animal <-- AnimalTerrestre
AnimalTerrestre <-- Perro

Animal <-- AnimalAereo
AnimalAereo <-- Pajaro

@enduml