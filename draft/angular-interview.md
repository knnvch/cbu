## Общие вопросы

1. Опыт работы с Angular, AngularJS


1. Event Loop


1. Замыкание


1. ES6 фичи



## TypeScript

1. Основные особенности и возможности TypeScript


1. Декораторы  
_Функции для передачи метаданных в:_

	- Класс
	- Поле
	- Метод
	- Параметр

```typescript
@expression({
    data: 'value'
})
```



## Angular

1. Data Binding

	- Односторонний
		- `<p>{{userInfo}}</p>`
		- `[hero]="selectedHero"`
		- `(click)="selectHero(hero)"`
	- Двусторонний
		- `<input [(ngModel)]="hero.name">`


1. Директивы

	- структурные - влияют на DOM и могут добавлять/удалять элементы (`*ngIf, *ngFor, *ngSwitch`)
	- атрибутные - меняют внешний вид или поведение элементов, компонентов или других директив (`ngClass, ngStyle`)


1. Pipes  
_Элементы для форматирования данных_

	- date
	- currency
	- lowercase
	- uppercase
	- async


1. @Input()



1. @Output()



1. Dependency Injection



1. Life cycle hooks




1. observable, rxjs



1. sass



1. unit tests



## Со звёздочкой

1. Директивы

	- `ng-template`
	- `ng-container`
	- `ng-content`


1. JIT и AOT


1. Zone.js


1. Структура проекта

	- core
	- shared
	- feature-1
	- feature-2
	app.module.ts
	app.component.ts
	app.component.html
