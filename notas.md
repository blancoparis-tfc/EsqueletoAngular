## Como crear un modulo con ruta

En este apartado lo que hacemos es esplicar como se crear un componente que vamos asociar a una ruta en cuestión.

1. Crear el componente:
``` bash
ng generate component inicio --module app-routing.module.ts
```
2. Establecer la ruta:

``` typescript
const routes: Routes = [
   { path: 'inicio', component: InicioComponent }
];
```
> En el fichero app-routing.module.ts

