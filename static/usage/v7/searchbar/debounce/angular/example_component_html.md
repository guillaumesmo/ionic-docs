```html
<ion-searchbar [debounce]="1000" (ionInput)="handleChange($event)"></ion-searchbar>

<ion-list>
  <ion-item *ngFor="let result of results">
    <ion-label>{{ result }}</ion-label>
  </ion-item>
</ion-list>
```
