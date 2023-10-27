- ## Вкладка "Выбор полиса":

- ### Кнопки

***1.  Квартира***

//span[contains(text(),'Квартира')]

***2. Дом***

//span[contains(text(),'Дом')]

***3. Сдается в аренду - ДА***

//button[@id="mat-button-toggle-58']

***4. Сдаётся в аренду - НЕТ***

//*[contains(text(),'Нет')]

***5. Расположена на первом или последнем этаже -ДА***

//div[text()='Расположена на первом или последнем этаже']/following: :button[1]

***6. Расположена на первом или последнем этаже -НЕТ***

//div[text()='Расположена на первом или последнем этаже']/following: :button[2]

***7. Установлена охранная сигнализация - ДА***

//button[@id="mat-button-toggle-79-button"]

***8. Установлена охранная сигнализация - НЕТ***

//button[@id="mat-button-toggle-80-button"]


***9. Промокод***

//*[contains(text(),'Промокод')]

***10. Применить***

//*[contains(text(),'Применить')]

***11. Оформить***

//*[contains(text(),'Оформить')]

***12. Материал несущих стен - кирпич или монолит***

//*[contains(text(),'Кирпич или монолит')]


***13. Материал несущих стен - дерево***

//*[contains(text(),'Дерево')]

***14. Заполнить по Сбер ID***

//*[contains(text(),'Заполнить по Сбер ID')]

----

- ### Вкладка "Оформление":

***1. Мужской***

//button[contains(.,'Мужской')]


***2. Женский***

//button[contains(.,'Женский')]

***3. Вернуться***

//button[contains(.,'Вернуться')]

***4. Оформить***

//button[contains(.,'Оформить')]

----

## Поля для ввода данных:

***Выбор полиса***


***1. Регион проживания***

//input[@formocontrolname='registrationRegion']

***2. Дата начала***

//input[@formocontrolname='startDate']

***3. Cумма***

//input[@mask='separator.0']

***4.Промокод***

//input[@formcontrolname='promoCode']

***5. Фамилия***

//*[contains(text(),'Фамилия')]


***6. Имя***

//*[contains(text(),'Имя')]

***7. Отчество***

//*[contains(text(),'Отчество')]


***8. Дата рождения***

//input[@formcontrolname='birthDate']

***9. Паспортные данные Страхователя: серия****

//input[@formcontrolname='docSeries']

***10. Номер***


//input[@formcontrolname='docNumber']

***11. Дата выдачи***

//input[@formcontrolname='docDate']


***12. Кем выдан:***

//textarea[@formcontrolname='docIssuer']

***13. Код подразделения***

//input[@formcontrolname='docDepartmentCode']

***14.город или населенный пункт***

//input[@formcontrolname='registrationCity']

***15. Улица***


//input[@formcontrolname='registrationstreet']

***16. Дом, литера, корпус, строение***

//input[@formcontrolname='registrationHouse']

***17. Квартира***

//input[@formcontrolname='registrationFlat']

***18. Телефон***

//input[@formcontrolname='contactPhone']

***19. Электронная почта***

//input[@formcontrolname='contactEmail']

***20. Повтор электронной почты***

//input[@formcontrolname='repeatEmail']

---

## ЧЕК бокс


***1. Отчество отсутствует***

//labek[@class='mat-checkbox-layout'][contains(.,'Отчество отсутствует')]

***2. Улица отсутствует***

//labek[@class='mat-checkbox-layout'][contains(.,'Улица отсутствует')]

--- 

## СБЕР ЛОГО

***1. CБер Страхование ЛОГО***

.//div[@class=("sber-logo")]

----

## Дата пикер

***1. Дата начала***

//input[@formcontrolname='startDate']/fillowing::button [1]


***2. Дата рождения***

//input[@formcontrolname='birthDate']/fillowing::button [1]



***3. Дата выдачи***

//input[@formcontrolname='docDate']/fillowing::button [1]

---

## Cлайдер блока суммы

//div[@class='mat-slider-wrapper']

---

## Хедер "Что будет застраховано"

//h4[text()='Что будет застрахновано']

---

## Текстовые блоки



***1. Мебель, техника и ваши вещи*** 


//div[text(),'Мебель, техника и ваши вещи')]/ancestor::ul

 
***2.Падение летательных аппаратов и их частей ***

//div[text(),'Мебель, техника и ваши вещи')]/ancestor::ul

----

## Колонки "Страховая защита включенная в программу"

***1. Чрезвычайная ситуация***

//div[text(),'Чрезывачайная ситуация')]/ancestor::ul


***2. Стихийные бедствия***



//div[text(),'Стихийные бедствия')]/ancestor::ul
