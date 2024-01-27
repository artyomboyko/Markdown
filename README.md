# Примеры оформления README.md файла для репозиториев Github.


## Заголовки.
Для задания заголовка и его уровня используется символ #

	# Заголовок 1 уровня.
	
# Заголовок 1 уровня.

	## Заголовок 2 уровня.
## Заголовок 2 уровня.

	### Заголовок 3 уровня.
### Заголовок 3 уровня.

	#### Заголовок 4 уровня.
#### Заголовок 4 уровня.
----


## Примеры шрифтов.
Для выделения текста с помощью используются символы * или _.
Текст, выделенный курсивом:

	*Пример*
*Пример*

	_Пример_
_Пример_

Текст, выделенный полужирным шрифтом:

    **Пример**
**Пример**

	__Пример__
__Пример__


Текст, выделенный курсивным полужирным шрифтом:

	***Пример***
***Пример***

	___Пример___
___Пример___

## Надстрочный и подстрочный интервалы в тексте.

Для задания надстрочного и подствочного интервалов в языке Markdown используются HTML теги /<sub></sub> и /<sup></sup>.  
Например:

	SSR(p) = |f - g<sub>p</sub>|<sup>2</sup>

Будет выглядеть так:    

SSR(p) = |f - g<sub>p</sub>|<sup>2</sup>


## Зачеркнутый текст.
Любой текст, заключенное в две тильды, будет зачеркнут.
Например,

	~~ Зачёркнутый текст ~~

Будет выглядеть так:

~~Зачёркнутый текст~~


## Абзацы
Вы можете создать новый абзац, оставив пустую строку между строками текста.


## Списки
### Неупорядоченные списки
Можно создать неупорядоченный список, поставив перед одной или несколькими строками текста знак - или *. ***Важно закончивать пункт любого списка одним символом пробела.*** 

Например,

	- Первый пункт неупорядоченного списка 
	* Второй пункт неупорядоченного списка 
	
Будет выглядеть так:

- Первый пункт неупорядоченного списка 
* Второй пункт неупорядоченного списка 

### Вложенные списки
Можно создать вложенный список, разместив один или несколько элементов списка под другим элементом.

Например,

	1. Первый элемнт списка 
	   - Первый вложенный элемент списка 
		 - Второй вложенный элемент списка 

Будет выглядеть так:

1. Первый элемнт списка 
   - Первый вложенный элемент списка 
     - Второй вложенный элемент списка 
   
### Упорядоченные списки
Чтобы упорядочить список, ставьте перед каждой строкой номер.

Например,	

	1. Первый элемент списка	
	2. Второй элемент списка	

Будет выглядеть так:

1. Первый элемент списка 
2. Второй элемент списка.


## Дополнительные элементы - символ обратного слеша ("\\")
Символ обратного слеша может использоваться в Markdown перед специальными символами для того, чтобы они воспринимались в их буквальном (а не служебном) значении. 

Например,

	\&Alpha;

Будет выглядеть так:

\&Alpha;

Но!

	&Alpha; 
	
Будет выглядеть так:

&Alpha;


## Ссылки.
Пример оформления ссылки выглядит следующим образом:
    
	[Ваза](https://ru.wikipedia.org/wiki/%D0%92%D0%B0%D0%B7%D0%B0 "Необязательная подсказка, выводится при наведении курсора мыши")    
В результате на экран выводится следующее:    
[Ваза](https://ru.wikipedia.org/wiki/%D0%92%D0%B0%D0%B7%D0%B0 "Необязательная подсказка, выводится при наведении курсора мыши")  

### Упрощенный порядок создания ссылок
В Markdown поддерживается упрощённый порядок автоматического создания ссылок для URL-адресов и адресов электронной почты. Для этого необходимо поместить URL-адрес или почтовый адрес в угловые скобки

Например,

	<blademoon@yandex.ru>
	<https://www.yandex.ru>
	
Будет выглядеть так:

<blademoon@yandex.ru>    
<https://www.yandex.ru>	


## Картинки
Для вставки в текст картинок используется соответсвующий HTML код. В тегах width и height необходимо указать размер картинки, для ее правильного отображения.

	<p align="center">
	  <img width="400" height="250" src="https://github.com/blademoon/Markdown/blob/main/Picture/cat.jpg">
	</p>

В итоге вставляемая картинка будет выглядеть так:

<p align="center">
  <img width=400" height="250" src="https://github.com/blademoon/Markdown/blob/main/Picture/cat.jpg">
</p>

В теге align указывается выравнивание картинки. Картинку можно выровнять по центру (align="center"), а так же по левому (align="left") или правом (align="right") краю. 

## Вставка ссылки на видео с превью
Для того чтобы вставить видео с YouTube с превью картикой нужно использовать следующий синтаксис:

```text
[![Текст к картинке](https://img.youtube.com/vi/YOUTUBE_ID_ВИДЕО/0.jpg)](https://www.youtube.com/watch?v=YOUTUBE_ID_ВИДЕО)
```
Получить ID от YouTube видео просто. ID это последние символы в ссылке получаемой по нажатию кнопки "Поделиться". Например, полученная с YouTube ссыулка на видео имеет следующий вид `https://youtu.be/94HLyui6eVk?si=lEgmVEtMnxgfZjvj`, тогда ID `lEgmVEtMnxgfZjvj`.
В итоге видео `[![Best job in the world!](https://img.youtube.com/vi/94HLyui6eVk/0.jpg)](https://www.youtube.com/watch?v=94HLyui6eVk)` будет выглядеть так:

[![Best job in the world!](https://img.youtube.com/vi/94HLyui6eVk/0.jpg)](https://www.youtube.com/watch?v=94HLyui6eVk)


### Упрощенный порядок вставки картинок.
Более простой вариант вставки картинки можно сделать так:

	![Image of cat](https://github.com/blademoon/Markdown/blob/main/Picture/cat.jpg)


В итоге вставляемая картинка будет выглядеть так:

![Image of cat](https://github.com/blademoon/Markdown/blob/main/Picture/cat.jpg)

***НО! Выравнивание картинки по левому краю!***


## Блоки кода и подсветка синтаксиса.
Для вставки кода в документ необходимо использовать либо _блоки кода_ (начинаются и заканчиваются сиволами "```"), либо отсупы в 4 символа пробела ( или одину табуляцию). В блоках кода можно использовать подстветку синтаксиса путем указания языка на котором написан этот код.    
Пример болка кода:

	```c++
	#include <iostream>
	
	using namespace std
	
	int main() {
		cout << "This is a C++ code example!"
	}
	```

Будет выглядеть так:

```c++
#include <iostream>
	
using namespace std
	
int main() {
	cout << "This is a C++ code example!"
}
```

Пример выделения кода с помощью отступов:

	#include <iostream>
	
	using namespace std
		
	int main() {
		cout << "This is a C++ code example!"


## Список задач
Список задач в языке Markdown формируется с помощью следующего синтаксиса:

	- [ ] ***Задача №1***
	- [X] **Отмеченная задача**
	- [ ] *Не выполненная задача*
	
Будет выглядеть так:

- [ ] ***Задача №1***
- [X] **Отмеченная задача**
- [ ] *Не выполненная задача*


## Таблицы
Таблицы
Можно создавать таблицы, собирая список слов и разделяя их дефисами - (для первой строки), а затем разделяя каждый столбец вертикальной чертой |:
Пример синтаксиса:

	Первый столбик заголовка| Второй столбик заголовка
	------------ | -------------
	Содержимое ячейки 1| Содержимое ячейки 2
	Содержимое ячейки 3 | Содержимое ячейки 4
	
Будет выглядеть так:

Первый столбик заголовка| Второй столбик заголовка
------------ | -------------
Содержимое ячейки 1| Содержимое ячейки 2
Содержимое ячейки 3 | Содержимое ячейки 4
		

## Цитаты.
Для обозначения цитат в языке Markdown используется символ знак «больше» («>»). ***Уровень цитирования не может превышать 15!*** Цитирование можно использовать как перед каждой строкой цитаты, так и только перед первой строкой параграфа. Например:
    >Это пример цитаты,
    >в которой перед каждой строкой
    >ставится угловая скобка.
	
>Это пример цитаты,
>в которой перед каждой строкой
>ставится угловая скобка.	
	

    >Это пример цитаты,
    в которой угловая скобка
    ставится только перед началом нового параграфа.
	
    >Второй параграф.
	
>Это пример цитаты,
в которой угловая скобка
ставится только перед началом нового параграфа.

>Второй параграф.

Вложение цитаты в цитату выглядит следующим образом:

    > Первый уровень цитирования
    >> Второй уровень цитирования
    >>> Третий уровень цитирования
    >
    >Первый уровень цитирования

> Первый уровень цитирования
>> Второй уровень цитирования
>>> Третий уровень цитирования
>
>Первый уровень цитирования



## Греческие буквы.
Для вставки в текст [греческих символов](https://ru.wikipedia.org/wiki/%D0%93%D1%80%D0%B5%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9_%D0%B0%D0%BB%D1%84%D0%B0%D0%B2%D0%B8%D1%82)  используются либо обозначения этих символов, либо их код в кодировке UNICODE. Ниже приведена таблица с заглавными и прописными символами греческого алфавита.    

Заглавные греческие буквы:

| Имя кода | Код | Описание | Отображаемый символ |                                                                 
| -- | -- | -- | -- |                                                                                                   
| \&Alpha; | \&#913; | Большая (заглавная) греческая буква "альфа"| Α |                                                                   
| \&Beta; | \&#914; | Большая (заглавная) греческая буква "бета" | Β |                                                                     
| \&Gamma; | \&#915; | Большая (заглавная) греческая буква "гамма" | Γ |                                                                   
| \&Delta; | \&#916; | Большая (заглавная) греческая буква "дельта" | Δ |                                                                   
| \&Epsilon; | \&#917; | Большая (заглавная) греческая буква "эпсилон" | Ε |                                                               
| \&Zeta; | \&#918; | Большая (заглавная) греческая буква "дзета (зита)" | Ζ |                                                                     
| \&Eta; | \&#919; | Большая (заглавная) греческая буква "эта (ита)" | Η |                                                                       
| \&Theta; | \&#920; | Большая (заглавная) греческая буква "тэта (фита)" | Θ |                                                                   
| \&Iota; | \&#921; | Большая (заглавная) греческая буква "йота" | Ι |                                                                     
| \&Kappa; | \&#922; | Большая (заглавная) греческая буква "каппа" | Κ |                                                                   
| \&Lambda; | \&#923; | Большая (заглавная) греческая буква "лямбда (лямда)" | Λ |                                                                 
| \&Mu; | \&#924; | Большая (заглавная) греческая буква "мю (ми)" | Μ |                                                                         
| \&Nu; | \&#925; | Большая (заглавная) греческая буква "ню (ни) | Ν |                                                                         
| \&Xi; | \&#926; | Большая (заглавная) греческая буква "кси" | Ξ |                                                                         
| \&Omicron; | \&#927; | Большая (заглавная) греческая буква "омикрон" | Ο |                                                               
| \&Pi; | \&#928; | Большая (заглавная) греческая буква "пи" | Π |                                                                         
| \&Rho; | \&#929; | Большая (заглавная) греческая буква "ро" | Ρ |                                                                       
| \&Sigma; | \&#931; | Большая (заглавная) греческая буква "сигма" | Σ |                                                                   
| \&Tau; | \&#932; | Большая (заглавная) греческая буква "тау (тав)" | Τ |                                                                       
| \&Upsilon; | \&#933; | Большая (заглавная) греческая буква "ипсилон" | Υ |                                                               
| \&Phi; | \&#934; | Большая (заглавная) греческая буква "фи" | Φ |                                                                       
| \&Chi; | \&#935; | Большая (заглавная) греческая буква "хи" | Χ |                                                                       
| \&Psi; | \&#936; | Большая (заглавная) греческая буква "пси" | Ψ |                                                                       
| \&Omega; | \&#937; | Большая (заглавная) греческая буква "омега" | Ω |

Маленькие греческие буквы:

| Имя кода | Код | Описание | Отображаемый символ |                                                                 
| -- | -- | -- | -- |                                                                                                   
| \&alpha; | \&#945; | Маленькая греческая буква "альфа" | α |                                                                     
| \&beta; | \&#946; | Маленькая греческая буква "бета"| β |                                                                       
| \&gamma; | \&#947; | Маленькая греческая буква "гамма" | γ |                                                                     
| \&delta; | \&#948; | Маленькая греческая буква "дельта" | δ |                                                                     
| \&epsilon; | \&#949; | Маленькая греческая буква "эпсилон" | ε |                                                                 
| \&zeta; | \&#950; | Маленькая греческая буква "дзета (зита)" | ζ |                                   
| \&eta; | \&#951; | Маленькая греческая буква "эта (ита)" | η |                                                                         
| \&theta; | \&#952; | Маленькая греческая буква "тэта (фита)" | θ |                                                                     
| \&iota; | \&#953; | Маленькая греческая буква "йота" | ι |                                                                       
| \&kappa; | \&#954; | Маленькая греческая буква "каппа" | κ |                                                                     
| \&lambda; | \&#955; | Маленькая греческая буква "лямбда (лямда)" | λ |                                                                   
| \&mu; | \&#956; | Маленькая греческая буква "мю (ми)" | μ |                                                                           
| \&nu; | \&#957; | Маленькая греческая буква "ню (ни)" | ν |                                                                           
| \&xi; | \&#958; | Маленькая греческая буква "кси" | ξ |                                                                           
| \&omicron; | \&#959; | Маленькая греческая буква "омикрон" | ο |                                                                 
| \&pi; | \&#960; | Маленькая греческая буква "пи" | π |                                                                           
| \&rho; | \&#961; | Маленькая греческая буква "ро" | ρ |                                                                         
| \&sigma; | \&#963; | Маленькая греческая буква "сигма" | σ |                                                                     
| \&tau; | \&#964; | Маленькая греческая буква "тау (тав)" | τ |                                                                         
| \&upsilon; | \&#965; | Маленькая греческая буква "ипсилон" | υ |                                                                 
| \&phi; | \&#966; | Маленькая греческая буква "фи" | φ |                                                                         
| \&chi; | \&#967; | Маленькая греческая буква "хи" | χ |                                                                         
| \&psi; | \&#968; | Маленькая греческая буква "пси" | ψ |                                                                         
| \&omega; | \&#969; | Маленькая греческая буква "омега" | ω |  





 


