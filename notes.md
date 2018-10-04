ng new app-name
ng serve (localhost:4200)

[(ngModel)]="variable_name"
import { FormsModule } from '@angular/forms'; (app.module.ts)
imports: [ FormsModule ] (app.module.ts)#

 <!-- cli add component -->
ng generate component component-name
ng g c component-name

 <!-- String Interpolation  -->
 ({{ data }})

 <!-- Property Binding -->
 ([property]="data")

 <!-- Event Binding -->
 ( {event}="expression")

 <!-- Two way binding -->
 ([(ngModel)]="data")

 