### Concesionaria de Autos y Motos

<p>
Este proyecto implementa la simulación para una concesionaria de vehículos (Autos y Motos) desarrollado en Java con Spring Boot, utilizando Maven como gestor de dependencias.

El mismo tiene como objetivo:
</p>

- Mostrar un catálogo (lista) de vehículos (autos y motos).
- Implementación de una solución orientada a objetos, creando una clase abstracta (Vehiculo).
- Implementación de interfaz Collection.
- Implementación de interfaz Comparable<Vehiculo>.
- Generar reportes: vehículo más caro/más barato, filtrado por características, y ordenamientos.

> Hacer uso de :

- Lombok.
- Streams API.
- Separación de responsabilidades. 

<p>
La clase Vehículo se encarga solo de representar las propiedades de un vehículo, mientras que Concesionaria maneja la lógica de negocio.</p> 

> Aplicando:

- Herencia: 
	- Auto y Moto extienden de Vehiculo.
	- Heredan campos comunes (marca, modelo, precio).
- Polimorfismo: 
	- Método getCaracteristicaEspecifica() es abstracto en Vehiculo y se implementa diferente en cada subclase.

Como beneficios el proyecto muestra:
- Extensibilidad: Añadir nuevos tipos de vehículos (ej: Camion) sin modificar la lógica existente.
- Reutilización: Código común (marca, modelo) en la superclase.
- Flexibilidad: El método imprimirVehiculos() funciona con cualquier subclase de Vehiculo.

Desarrollado © 2025 **{<∫geedev>_}** by Elvis Guaiquire.
