# KotoScience

## Опис проекту
Проект представляє собою Computer Vision модель з веб-формою для отримання даних.
Ціль проекту - створити модель, що зможе розпізнавати та визначати вид тварини за фото
наданим через веб-форму. Користувач також зможе отримати довідку за розпізнаним видом.

## Актуальність проекту
Актуальність нашого продукту полягає в тому, що продуки з схожим функціоналом платні або обмежені операційною системою.  
За допомогою веб доступу, кожен користувач зможе розширити кругозір про тварину на фотографії.
## Функціонал продукту
Кожен користувач зможе завантажити фото через веб-форму, дізнатись вид тварини, та
отримати довідку та цікаві факти про розпізнану тварину. 

## Стек технологій

**Python**

`Python` наразі є однією з найпопулярніших мов програмування, причинами цього стали:
* Простий та легкий синтаксис.
* Швидкість розробки. На перший погляд, це не так вже і важливо, але час розробника – це гроші замовника. Корпорації на кшталт Google та Apple вже майже десятиліття більшість своєї внутрішньої розробки ведуть, використовуючи цю мову.
* Спільнота. Любов до цієї мови зі сторони розробників створила величезну групу прихильників, яка активно підтримує перспективні проєкти, фреймворки, відповідає на складні питання на StackOverFlow, та розвиває мову.
* Універсальність. Ця мова на сьогодні є дуже гнучкою: за допомогою неї, можна навчати дітей програмуванюю, створювати веб-додатки, сервіси, тестувати сайти чи програми, використовувати машинне навчання та програмувати пристрої для Internet Of Things.

Якщо в інших сферах можливо знайти якісь альтернативи, то для задач машинного навчання `Python` посідає перше місце. Так, для статистики та деяких задач існує чудова мова `R`. Але для запуску програмного продукту ця мова не згодиться. Тому `Python` мова, яку однаково зручно використовувати, як для початкового концепту, так і для фінального. Google та Microsoft використовують цю мову як основну у задачах машинного навчання.

**PyTorch**

`PyTorch` - це бібліотека, написана мовою `Python`, що забезпечує тензорні обчислення з GPU-прискоренням, подібно до `NumPy`. `PyTorch` пропонує насичений API для вирішення прикладних завдань, пов'язаних з нейронними мережами. Перевагами цієї бібліотеки є:
* Динамічний граф. В порівняні з `TensorFlow`, яка використовує статичний граф, `PyTorch` використовує техніку, звану автодиференціацією у зворотному режимі, яка дозволяє змінювати спосіб поведінки мережі з прикладанням відносно невеликих зусиль, тобто динамічний обчислювальний граф або DCG.
* Налагодження. Так як обчислювальний граф визначається під час виконання програми, є можливість використовувати будь-який інструмент налагодження: `pdb`, `ipdb`, `PyCharm`.
* Паралелізм даних. Використовуючи `torch.nn.DataParallel` з будь-яким модулем можна домогтися майже магічного паралелізму даних за розміром батча.
* Візуалізація. Існує інтеграція з `Tensorboard`, проте для простішого використання з меншим функціоналом є `visdom`. Крім названих інструментів, можна використовувати стандартні засоби візуалізації - `matplotlib` і `seaborn`.

**Flask**

## Timeline

![timeline](https://github.com/shooterdimon/KotoScience/blob/main/timeline/timeline.png)
