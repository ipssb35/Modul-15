# Modul_15

## Задание.
Необходимо улучшить код с точки зрения DRY, KISS, YAGNI, SOLID. Проверить семантику и валидность верстки сайта. 
Исправить верстку по БЭМ. Использовать линтеры.

***

## DRY 
**Селекторы с одинаковыми стилями сгруппированы вместе:**
`.header,
.main-section,
.how_i_work,
.portfolio-section,
.offer-section {background-color: #eeeff1; padding: 0;}`

**C целью уменьшения длины кода, селекторы и стили прописаны в одну строку:**

`.fixed-container {padding: 0 20px; margin: 0 auto; max-width: 1240px;} `


***

## KISS
**Удалены неиспользуемые стили**

***

## YAGNI

Как пример, вместо 10-ти имен использовалось 15-16. 


[Ссылка](https://github.com/ipssb35/Modul_13)

***


## Семантика и валидность

**[Ссылка на изначальный вариант](https://github.com/ipssb35/Modul__7)**

 В файлах mobile-style.css и slyle.css объединены селекторы с одинаковыми стилями.
Всё проверено с помощью W3C валидатора.

***

## Линтеры
Код преобразован в Beautify. 

***

## БЭМ 

Удалены селекторы с id из html, так как они не использовались.

**[Изначальный вариант](https://github.com/ipssb35/Modul__7)**

***

  
  
  
  

