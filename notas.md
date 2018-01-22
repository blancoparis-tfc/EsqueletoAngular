## Como crear un modulo con ruta

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

