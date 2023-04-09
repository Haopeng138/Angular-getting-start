# Apuntes angular 

Apuntes basado sobre el tutorial de [Tour of Heroes](https://angular.io/tutorial/tour-of-heroes/toh-pt1) de la documentación oficial de angular 

## Cap 1:

`@Component` es una función decorador que especifica los metadatos de angular para el componente

`Interface` define los propiedades de una clase

`Pipes` 'filtro' para formatear 

`ngModel` enlaces de datos bidireccionar, para usar ngModel se debe importar 'FormsModule' de angular. 
Cada componente debe declarar solo un NgModel,pero no hace falta declarar en cada uno de ellos porque en app.module.ts en 'declarations' esta los componentes que se utiliza.

## Cap 2:

`ngFor` usar esto dentros de las etiquetas html de esta forma: 'ngFor="let heroe of heroes"'

`ngIf` para incluir o excluir bloques HTML 

Se puede CSS con enlace class 

## Cap 3: 

Crea un componente reutilizabre,refactorizando

