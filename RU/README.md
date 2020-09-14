## Заметки о книгах для .Net-разработчика
Версия: **2016** год. Комментарии из **2020** в колонке UPD2020. Новые позиции [здесь](UPDATES_2020.md)



#### Платформа: Начальный уровень
С этих книг можно начинать с нуля:

Обложка | Название| Перевод | Комментарии | UPD2020
--- | --- | --- | --- | ---
<img alt="TroelsenCSharpAndNetEd7" src="../Covers/TroelsenCSharpAndNetEd7.jpg" width="120" />|*Andrew Troelsen*  C# 6.0 and the .NET 4.6 Framework (7th edition)|Вроде как есть перевод шестого издания. Про качество - не знаю (вроде раньше было ИД Питер - сейчас Диалектика)| Начало начал. Азбука. | Вышло два новых издания, Pro C# 7.0 With .Net & .Net Core и Pro C# 8.0 With .Net Core 3. Содержимое обновлено под актуальный стек, про WCF нужно смотреть в старых изданиях
<img alt="AlbahariCSharpInNutshell" src="../Covers/AlbahariCSharpInNutshell.jpg" width="120" />|*Joseph Albahari, Ben Albahari* C# 6.0 in a Nutshell| Есть перевод актуального издания (нормальный)|Не путать с Pocket Reference /Карманный справочник | Тоже два обновления, C# 7.0 in a Nutshell, C# 8.0 in a Nutshell. Можно смело смотреть последнее издание. И по прежнему не путать с Pocket Reference

#### Платформа: Профессиональный уровень

Разобравшись с азами языка и платформы, можно начинать углубляться:

Обложка | Название| Перевод | Комментарии | UPD2020
--- | --- | --- | --- | ---  
<img alt="SkeetCSharpInDepth" src="../Covers/SkeetCSharpInDepth.jpg" width="120" />|*Jon Skeet* C# in Depth (3rd edition)|Есть перевод актуального издания (третье) (говорят норм)|Второе издание слишком старое и спорное | Вышло четвертое издание, инкрементальное обновление
<img alt="MichaelisLippertEssentialCSharp" src="../Covers/MichaelisLippertEssentialCSharp.jpg" width="120" />|*Mark Michaelis, Eric Lippert* Essential C# 6.0|Есть старый перевод "По существу о C# 4.0", без Липперта|Продвинутый вариант Троелсена | Два обновления, про C# 7.0 и C# 8.0
<img alt="RichterClrViaCSharp" src="../Covers/RichterClrViaCSharp.jpg" width="120" />|*Jeffrey Richter* CLR via C# (4th edition)|Есть перевод актуального издания (нормальный) - розовая обложка|Ни в коем случае не третье издание (если про перевод) | Спрашивал лично у Рихтера - говорит пятого издания не будет

#### Платформа: Экспертный уровень
За тонкими моментами, внутренностями и производительностью - это сюда:

Обложка | Название| Перевод | Комментарии | UPD2020
--- | --- | --- | --- | ---
<img alt="LidinNetILAsm" src="../Covers/LidinNetILAsm.jpg" width="120" />|*Serge Lidin* .Net IL Assembler (2014)|Есть перевод 2002 года - слишком стар|Наиболее цельное описание внутренностей Ilasm | Без изменений, впрочем и сам IL не особо то и поменялся (привет .ldftn)
<img alt="WatsonWritingHighPerfNetCode" src="../Covers/WatsonWritingHighPerfNetCode.jpg" width="120" />|*Ben Watson* Writing High-Performance .NET Code (2014)|Не переводилось|Разбор полетов с механизмами .Net, влияющими на перформанс | Вышло второе издание - 2018 года +50% контента
<img alt="RahmanCSharpDeconstructed" src="../Covers/RahmanCSharpDeconstructed.jpg" width="120" />|*Mohammad Rahman* C# Deconstructed|Не переводилось|Разбор C# до уровня работы CLR и OS/железа | - 
<img alt="RahmanExpertCSharp5WithNet45Framework" src="../Covers/RahmanExpertCSharp5WithNet45Framework.jpg" width="120" />|*Mohammad Rahman* Expert C# 5.0 with .Net 4.5 Framework |Не переводилось|C# Deconstructed + щепотка CLR via C# на стероидах с описанием внутренностей платформы | -
<img alt="GoldshteinProNetPerformance" src="../Covers/GoldshteinProNetPerformance.jpg" width="120" />|*Sasha Goldshtein et al* Pro .Net Performance|Вроде как есть перевод 2014 года: Оптимизация приложений на платформе .Net|Самая популярная книга по перформансу | -

#### Общие вещи:
Базовые вещи, не связанные напрямую со специфичными технологиями:

Обложка | Название| Перевод | Комментарии | UPD2020
--- | --- | --- | --- | ---
<img alt="TeplyakovNetDesignPatterns" src="../Covers/TeplyakovNetDesignPatterns.jpg" width="120" />|*Сергей Тепляков* Паттерны проектирования на платформе .Net|Не требует перевода|**ЕДИНСТВЕННАЯ** нормальная книга по паттернам на .Net | Появилась нормальная книга от Нестерука, но  данный труд по прежнему актуален.
<img alt="SeemanDependencyInjectionInNet" src="../Covers/SeemanDependencyInjectionInNet.jpg" width="120" />|*Mark Seemann* Dependency Injection in .Net|Есть перевод "Внедрение зависимостей в .NET"|Материал неплохой, но автор местами - полный абсолютист и настоящий ситх, поэтому текст нужно читать с осторожностью, во избежание радикализации | Вышла вторая редакция, обновленный список контейнеров, автор стал еще более радикальным и, предсказуемо, ударился в Haskell. Теперь воюет не только с ServiceLocator, но и с AmbientContext. На ссылки на blog.ploeh.dk уже выработался рефлекс
<img alt="DaviesAsyncInCSharp5" src="../Covers/DaviesAsyncInCSharp5.jpg" width="120" />|*Alex Davies* Async in C# 5.0|Есть перевод "Асинхронное программирование в C# 5.0"|Обзор async в TPL с разбором.. Но для C# 5.0 (то бишь некоторые косяки исправлены) | Совсем устарела, нужно смотреть на Stephen Cleary

#### Технологии: WPF
Десктопная разработка, крутая кривая обучения:

Обложка | Название| Перевод | Комментарии | UPD2020
--- | --- | --- | --- | ---
<img alt="McDonaldProWPF45inCSharp" src="../Covers/McDonaldProWPF45inCSharp.jpg" width="120" />|*Matthew McDonald* Pro WPF 4.5 in C#|Есть перевод: WPF: Windows Presentation Foundation в .NET 4.5 с примерами на C# 5.0 для профессионалов|WPF с 0 | Обновлений нет, как впрочем и у WPF
<img alt="SellsProgrammingWPF2ndEd" src="../Covers/SellsProgrammingWPF2ndEd.jpg" width="120" />|*Chris Sells* Programming WPF 2nd edition|Не переводилось|Расширенный разбор | Аналогично

#### Технологии: WCF

Сетевые не-web сервисы

Обложка | Название| Перевод | Комментарии | UPD2020
--- | --- | --- | --- | ---
<img alt="LowyProgrammingWcfServices4thEd" src="../Covers/LowyProgrammingWcfServices4thEd.jpg" width="120" />|*Juval Lowy* Programming WCF Services 4th edition|Не переводилось|Серьезный разбор стека, с косяками и сопроводительными библиотеками. Вводный курс можно из Троелсена взять | WCF старательно закапывают. OpenWCF существует, но все тонкости напрямую не переносятся

#### Технологии: ASP.NET

Веб-страницы и веб-сервисы:

Обложка | Название| Перевод | Комментарии | UPD2020
--- | --- | --- | --- | ---
<img alt="FreemanProAspNet45inCSharp" src="../Covers/FreemanProAspNet45inCSharp.jpg" width="120" />|*Adam Freeman* Pro ASP.NET 4.5 in C#|Есть перевод|Ввод в ASP.NET (WebForms + IIS), до MVC | WebForms тоже закапывают. Зато можно смотреть на цикл жизни в React да Blazor и вспоминать поляков в космосе
<img alt="EspositoProgrammingMsAspNetMvc3rdEd" src="../Covers/EspositoProgrammingMsAspNetMvc3rdEd.jpg" width="120" />|*Dino Esposito* Programming Microsoft ASP.NET MVC 3rd edition|Не переводилось|Переход к MVC. Именно Эспозито, именно третья редакция. От других авторов - совершенно иные книги | Знания немного переносятся на .Net Core, но уж лучше Гэллоуэя
<img alt="GallowayProfessionalAspNetMvc5" src="../Covers/GallowayProfessionalAspNetMvc5.jpg" width="120" />|*Jon Galloway et al* Professional ASP.NET MVC 5|Не переводилось|Именно Galloway, не Freeman | Вообще с книгами под Core печально, и только Фриман штампует одну и ту же книгу под новые версии регулярно