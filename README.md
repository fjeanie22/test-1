test
====

Тестовое задание, цель которого проверить уровень владения и освоения WordPress.

# Задача
Сделать каталог фильмов и вывести по ним данные.

# Требования
1. Ставим чистый WordPress на бесплатный хостинг типа http://www.hostinger.ru/ или https://www.openshift.com/
2. Поставить тему Unite http://wordpress.org/themes/unite
3. Сделать для темы дочку http://wpmag.ru/2013/dochernie-temy-wordpress/
4. Добавить новый тип записи Фильмы для создания базы фильмов. Можно использовать расширение CPT UI http://wordpress.org/plugins/custom-post-type-ui/
5. И к фильмам добавляем таксономии Жанры, Страны, Год и Актеры. Чтобы классифицировать фильмы по жанрам. Можно использовать тоже расширение что в п.4
6. Добавляем 2 текстовых поля к типу поста Фильмы: Стоимость сеанса и Дата выхода в прокат. Лучше использовать расширение ACF http://wordpress.org/plugins/advanced-custom-fields/
7. У каждого фильма после описания выводим Страну и Жанр, а также стоимость и дату выхода.
8.  Через хук выводим на странице списка фильмов. http://casepress.org/kb/web/dobavlyaem-informatsiyu-o-zapisi-na-sajte-bez-pravki-shablona-cherez-huk-the_content-wordpress/
9.  На странице фильма выводим через создание и правку шаблона. Нужно создать шаблон архива типа записи в дочерней теме. Подсказка тут http://truemisha.ru/blog/wordpress/template-hierarchy.html
