# DynamicTableViewLesson4

## Home Work: 

Вам нужно будет продолжить ваш старый проект c ВК или написать с нуля новый.   
В ваш проект нужно будет добавить новый экран с лентой новостей вк.    

**Лента новостей:**

Лента новостей состоит из кастомной ячейки с аватором, названием, датой поста, картинкой, текстом над картинкой, и кнопками для лайка, комментария, шаринга с числами соотвественно для каждого (кроме последнего). 

**Ваша задача:** 

1) Добавить рандомные данные в ячейку, и сделать динамическую высоту, чтобы ячейка подстраивалась под контент. Рандомный контент должен так же включать отсудствие картинки/текста, разную высоту текста. 
2) Добавить pull-to-refresh, т.е. тянуть таблицу вниз, чтобы прокрутился лоадер и ваши данные таблицы заново перегенерились. 
3) Объеденить ваш профиль пользователя и новости в UITabBarController, чтобы можно было переключаться между табами и выбирать.   
4) По нажатию на ячейку открывать данные в новом окне детальной информации.   
5) По нажатию на кнопку шаринга открывать UIActivityViewController из вашего основного контроллера (в которой таблица) и дать возможность шарить инфу - текст из ячейки.  
6) Верстка как обычно на автолайаутах  
7) Чистый код, ничего лишнего, комментарии к методам, Mark-и для логического разделения методов

### Helpers: 

Pull to refresh (UIActivityIndicator): https://developer.apple.com/documentation/uikit/uiactivityindicatorview  
Реализация прим.: https://medium.com/anantha-krishnan-k-g/pull-to-refresh-how-to-implement-f915743703f8 
  
UITabBarController: https://developer.apple.com/documentation/uikit/uitabbarcontroller 

UIActivityViewController: https://developer.apple.com/documentation/uikit/uiactivityviewcontroller 
