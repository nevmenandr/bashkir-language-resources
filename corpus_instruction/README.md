# Инструкция: как искать в Национальном корпусе башкирского языка

* [Поиск по слову](#%D0%BF%D0%BE%D0%B8%D1%81%D0%BA-%D0%BF%D0%BE-%D1%81%D0%BB%D0%BE%D0%B2%D1%83)
* [Поиск по лемме](#%D0%BF%D0%BE%D0%B8%D1%81%D0%BA-%D0%BF%D0%BE-%D0%BB%D0%B5%D0%BC%D0%BC%D0%B5)
* [Поиск нескольких слов](#%D0%BF%D0%BE%D0%B8%D1%81%D0%BA-%D0%BD%D0%B5%D1%81%D0%BA%D0%BE%D0%BB%D1%8C%D0%BA%D0%B8%D1%85-%D1%81%D0%BB%D0%BE%D0%B2)
* [Поиск по грамматике](#%D0%BF%D0%BE%D0%B8%D1%81%D0%BA-%D0%BF%D0%BE-%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%D1%82%D0%B8%D0%BA%D0%B5)
* [Поиск по переводу](#%D0%BF%D0%BE%D0%B8%D1%81%D0%BA-%D0%BF%D0%BE-%D0%BF%D0%B5%D1%80%D0%B5%D0%B2%D0%BE%D0%B4%D1%83)
* [Ограничения поиска](#%D0%BE%D0%B3%D1%80%D0%B0%D0%BD%D0%B8%D1%87%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BF%D0%BE%D0%B8%D1%81%D0%BA%D0%B0)

Поисковая форма находится [на этой странице](http://bashcorpus.ru/bashcorpus/search). Она должна выглядеть так:

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/000.png "Поисковая форма")

## Поиск по слову

Самый простой поиск, который можно сделать в корпусе, это поиск по слову. Для этого нужно написать соответствующее слово в поле "Слово". Например, слово "таш":

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/001.png "Поиск по слову")

После этого нажимаем "Enter" или кнопку "Поиск предложений" и внизу, под формой, появляется результат:

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/002.png "Поиск по слову таш")

Это контексты, которые включают нужное нам слово. Если мы покажем на какое-то из слов мышкой, то отобразится его морфологический разбор и перевод. Слово, которое мы искали, будет подсвечено красным цветом.

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/003.png "Поиск по слову таш")

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/005.png "Разбор")

Чтобы узнать, из какого текста нашедшееся предложение, посмотрим на выделенный заголовок над контекстом, там написан автор, название текста и год. Если щёлкнуть по заголовку, то отобразится окно с подробной информацией:

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/004.png "Информация об источнике")

## Поиск по лемме

Леммой называется словарная форма слова. В русском языке для форм "окну", "окном", "окнами" одна лемма -- "окно". Для имен (существительного, прилагательного, числительного) и местоимений это обычно форма единственного числа именительного падежа.

**Внимание!** в принятой в корпусе разметке леммой глагола считается его основа, то есть форма повелительного наклонения. Это **не** инфинитив!

Если мы будем искать по лемме, то найдём все формы интересующего нас слова. 

Поищем лемму "баш". Для этого впишем "баш" в поле "Лемма":

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/006.png "Лемма")

В результате у нас нашлось не только слово "баш", но и "башта", и "башлыҡтарының".

## Поиск нескольких слов

Мы можем задавать поисковый запрос так, чтобы искалось не одно слово, а несколько слов в пределах одного предложения. Для этого нужно нажать на кнопку "Добавить слово" в виде плюса в кружочке справа от поисковой формы:

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/007.png "Добавить слово")

После этого у нас появится ещё одна такая же форма, где мы можем вписать другую лемму:

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/008.png "Куз")

Тогда найдутся контексты с теми словами, которые мы искали:

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/009.png "Поиск по двум леммам")

Чтобы искались слова только в том порядке, как они заданы в нашем запросе, нужно нажать на кнопку с изображением шестеренки слева от поисковой формы, и добавить там галочку "Расстояния между словами только как в запросе":

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/013.png "Куз")

## Поиск по грамматике

В поисковом запросе можно задавать не только конкретные слова, но и грамматические характеристики слова. Искать можно вообще "любое слово", которое при этом стоит в определенной форме. Для того, чтобы задать нужные грамматические характеристики, следует нажать на пиктограмму в правой части поля "Грамматика":

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/010.png "грамматика")

В результате откроется окно с конструктором, в котором можно сформировать правильный запрос с учётом грамматики:

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/011.png "теги")

Нажимая на кнопки с нужными грамматическими характеристиками, мы добавляем их в запрос. После того, как запрос сформирован, нужно нажать на кнопку "ОК" внизу:

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/012.png "теги")

Зададим запрос "существительное" + "прилагательное". Вот результат:

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/014.png "сущприл")

## Поиск по переводу

Кроме поиска по слову, лемме и грамматическим характеристикам, мы можем искать по русскому переводному эквиваленту слова. Для этого нам нужно нажать на кнопку "показать все поля" справа от поисковой формы, она выглядит как указывающая вниз стрелка:

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/015.png "все поля")

В поле "Перевод" впишем какое-нибудь русское слово в словарной форме. Например, "собака":

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/016.png "запрос по переводу")

Результат - все слова, которые имеют такой перевод:

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/017.png "собака")


## Ограничение поиска

Если мы хотим искать не во всем корпусе, а только в таком, который ограничен определенными параметрами, мы можем **задать подкорпус**. Это делается с помощью соответствующей кнопки. При её нажатии всплывает такое окно:

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/018.png "подкорпус")

Здесь мы можем задать те параметры, которыми хотим ограничить поиск. Например, мы хотим, чтобы показывались только контексты из текстов, созданных не позднее 2008 года:

![alt text](https://github.com/nevmenandr/bashkir-language-resources/blob/master/img_instr/019.png "2008")

Результаты поиска подчиняются этим ограничениям.
