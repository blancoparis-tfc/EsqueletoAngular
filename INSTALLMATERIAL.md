https://material.angular.io/guide/getting-started

# Instalar angular material y angular CDK.

```
npm install --save @angular/material @angular/cdk
```

# Instalar Animation

Hay que configurar las animaciones.



```typescript

import {BrowserAnimationsModule} from '@angular/platform-browser/animations';
import { NgModule } from '@angular/core';

import { AppRoutingModule } from './app-routing.module';

import { AppComponent } from './app.component';




@NgModule({
  declarations: [
    AppComponent
  ],
  imports: [
    BrowserAnimationsModule,
    AppRoutingModule
    
  ],
  providers: [],
  bootstrap: [AppComponent]
})
export class AppModule { }
```

# Configurar la css

```css
@import "~@angular/material/prebuilt-themes/indigo-pink.css";
```

# Instalar el hammer para los movimientos del mobil

```
npm install --save hammerjs
```

Ponemos en el main.ts, la libreria.

**main.ts**
``` typescript
import 'hammerjs';
```