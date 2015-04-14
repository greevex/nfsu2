NFS U2 Configurator
===

Авторизация в программе
---

  * Login: GreeveX
  * Password:  (empty - пустой)

История изменений
---

v0.8
-

  # Оптимизирован код.
  # Проверка файла вынесена в отдельный метод.
  # Вызов метода проверки перенесен из метода выбора машины в метод выбора файла.
  # При выборе неправильного файла настроек теперь программа пытается заменить его на правильный, если это невозможно, выводит соответствующее сообщение.
  # Расстановка колес вынесена в отдельную вкладку, так как в следующей версии планируется ввести помимо изменения подвески и расстановки колес в ширину еще и положение относительно кузова ближе к передней или задней части машины. Проще говоря можно будет двигать колеса не только влево и вправо, но и вперед-назад.

  * (!)Баги с приводом машины НЕ исправлены.


v0.7
-

  # Оптимизирован код.
  # Переписан мап загрузки данных.
  # Переработан алгоритм загрузки сохранённых файлов настроек машин разрешения *.car*
  # Добавлен отдельный мап загрузки сохранений.
  # В настройке движка текст-боксы заменены на трекБары(ползунки).
  # Все текст-боксы заменены на маск-боксы с соответствующей маской.
  # Устранены баги при выборе управления от другой машины из списка.
  # Добавлена возможно изменять привод машины. Имеются уже известные баги:
    * Привод меняется не на всех машинах.
    * Не определяется привод машины при загрузке данных для текущей машины..
  # Доделаны пункты меню, исправлены линки, теперь при клике они открываются.
  # Добавлена проверка правильности файла настроек.
  # Мелкие доработки.



v0.6
-

  # Оптимизирован код.
  # Добавлена возможность сохранять и загружать настройки для каждой машины отдельно. При этом вес файла такой настройки - менее 1 кб, что позволяет легко обмениваться настройками друг с другом.
  # Ускорена загрузка информации из файла настроек. (теперь занимает ~0.2 секунды)
  # Добавлена возможность изменять управление машины, просто выбрав управление от другой из списка.
  # Переписан мап загрузки данных.
  # Добавлены окна "О программе" и "Контакты".



v0.5.1
-

  # Добавлена строка меню сверху.
  # Исправлены мелкие баги.



v0.5
-

  # Оптимизирован код.
  # Исправлены баги при загрузке данных для выбранной машины.
  # Исправлены неправильные подписи для текст-боксов в изменении оборотов двигателя.
  # Исправлены все трекБары, так как 5 из 6 не работали.
  # Переписан мап загрузки данных.
  # Убрана кнопка "Загрузить" при выборе файла, теперь файл загружается автоматически.
  # Убрана кнопка "Загрузить" при выборе машины из списка, при выборе машины настройки загружаются автоматически.
  # Мелкие исправления.



v0.4
-

  # Добавлены вкладки. "Управление", настройки положения колес и подвеска вынесены во вкладку "Колеса".
Создана вкладка "Другие настройки", пустая :D
  # Ускорена загрузка информации из файла настроек. (теперь занимает ~1 - 1.5 секунды)
  # Добавлены текстбоксы глобального изменения ЭКУ и ТУРБО.