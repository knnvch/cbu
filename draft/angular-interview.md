## Общие вопросы

1. Опыт работы с Angular, AngularJS


1. Event Loop


1. Замыкание


1. ES6 фичи



## TypeScript

1. Основные особенности и возможности TypeScript


1. Декораторы  

	_Функции для передачи метаданных в класс, поле, метод, параметр_ 

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


1. Angular Components
	
	```typescript
	@Component({
		selector: '',
		templateUrl: '',
		styleUrls: [],
		animations: [],
		changeDetection: 'Default | OnPush'
	})
	```


1. Взаимодействие между компонентами

	- @Input()
	- @Output()
	- сервисы


1. Dependency Injection  
	_Патерн внедрения зависимостей_

1. Life cycle hooks

	- ngOnChanges()
	- ngOnInit()
	- ngDoCheck()
	- ngAfterContentInit()
	- ngAfterContentChecked()
	- ngAfterViewInit()
	- ngAfterViewChecked()
	- ngOnDestroy()


1. Observable, rxjs  
	_Патерн для работы с асинхронными аперациями_ 


1. Sass



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
