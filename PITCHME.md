
## Диаграммы классов

---

@snap[north]
@size[1em](Унифицированный язык моделирования)
@snapend

@snap[span-60 auto-margin]
![logo](images/UML_logo.png)
@snapend

---
@snap[north]
@size[1.25em](Группы диаграмм)
@snapend

@snap[west span-50 auto-margin] 
  @ul[split-screen-list](false)
  @size[1em](Статические диаграммы)
  - классов
  - объектов
  - компонентов
  - развертывания
@ulend
@snapend

@snap[east span-50 auto-margin]
  @ul[split-screen-list](false)
  @size[1em](Динамическеие диаграммы)
  - деятельности
  - сценариев
  - взаимодействия 
  - состояний
@ulend
@snapend

---

@snap[north]
@size[1em](Диаграммы классов (Class Model))
@snapend

@snap[span-60 auto-margin]
![main](images/diagram.png)
@snapend

+++

@snap[north]
@size[1.25em](Представление классов)
@snapend

@snap[span-100 auto-margin] 
![man](images/man.png)
@snapend

+++

@snap[north]
@size[1.25em](Генерация кода класса)
@snapend

```php
class Man
{
	/**
	 * @var string
	 */
	protected $name;
	/**
	 * @var string
	 */
	protected $surname;
	/**
	 * @return string
	 */
	public function getName():string
	{
		// TODO: implement here
		return "";
	}
	/**
	 * @return string
	 */
	public function getFullName():string
	{
		// TODO: implement here
		return "";
	}
	/**
	 * @param string $name
	 * @param string $surname
	 */
	protected function __construct(string $name, string $surname):void
	{
		// TODO: implement here
	}
	/**
	 * @param string $name
	 */
	private function setName(string $name):void
	{
		// TODO: implement here
	}
	/**
	 * @param string $surname
	 */
	private function setSurname(string $surname):void
	{
		// TODO: implement here
	}
}
```
+++

@snap[north]
@size[1.25em](Одиночка)
@snapend

@snap[span-100 auto-margin] 
![man](images/singleton.png)
@snapend

---

@snap[north]
@size[1em](Связи или отношения)
@snapend

@snap[span-100 auto-margin]
![main](images/relationship.png)
@snapend

+++

@snap[north]
@size[1.25em](Базовые отношения)
@snapend

@snap[span-100]
  @ul[split-screen-list](false)
  - отношение зависимости
  - отношение ассоциации
  - отношение агрегации
  - отношение обобщения
@ulend
@snapend

+++

@snap[north]
    @div[split-screen-list](false)
	Отношение зависимости
	@size[0.8em](dependency relationship)
    @divend
@snapend

@snap[span-100 auto-margin]
![main](images/dependency.png)
@snapend

+++

@snap[north]
    @div[split-screen-list](false)
	Отношение обобщения
	@size[0.8em](generalization relationship)
    @divend
@snapend

@snap[span-60 auto-margin]
![main](images/generalization.png)
@snapend

+++
@snap[north]
    @div[split-screen-list](false)
	Отношение ассоциации 
	@size[0.8em](association relationship)
    @divend
@snapend

@snap[west span-50 auto-margin]
![main](images/association1.png)
@snapend

@snap[east span-50 auto-margin]
![main](images/association2.png)
@snapend

@snap[south span-100 auto-margin]
![main](images/association3.png)
@snapend

+++
@snap[north]
    @div[split-screen-list](false)
	Отношение агрегации 
	(aggregation relationship)
    @divend
@snapend

@snap[span-100 auto-margin]
![main](images/aggregation.png)
@snapend

+++

@snap[north]
@size[1.25em](Базовые отношения)
@snapend

@snap[west span-50]
  @ul[split-screen-list](false)
  - отношение зависимости
  - отношение обобщения
  - отношение ассоциации
  - отношение агрегации
@ulend
@snapend

@snap[east span-50]
![main](images/mainRelationship.png)
@snapend

+++


---
