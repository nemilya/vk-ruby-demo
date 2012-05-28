Демонстрация доступа к VK API через Ruby
========================================

Работающее демо: http://vk-ruby-demo.cloudfoundry.com/


Технологии
----------

* [Ruby](http://ruby-lang.org) - язык программирования Ruby
* [CloudFoundry](http://cloudfoundry.com/) - быстрое развёртывание Ruby приложений
* [Bootstrap](http://twitter.github.com/bootstrap/) - быстрое css оформление от Twitter
* [Sinatra](http://sinatraruby.ru/) - минималистичный веб фреймворк на Ruby
* [omniauth](https://github.com/intridea/omniauth) - универсальная система авторизации
* [omniauth-vkontakte](https://github.com/mamantoha/omniauth-vkontakte) - модуль для OmniAuth для авторизации в ВКонтакте
* [vk-ruby](https://github.com/zinenko/vk-ruby) - Ruby обёртка для API функций ВКонтакте


Принцип работы
--------------

Описание можно прочитать здесь: https://github.com/nemilya/vk-demo/blob/master/README.md

Отличие этой демонстрации - в использовании `vk-ruby` модуля вместо `vkontakte_api`.


Замечания по старту
-------------------

Для локального запуска используется строка (чтобы не было конфликта версий библиотек):


    bindle exec ruby app.rb  -o localhost.vcap.me -p 3000

Подробнее о настройке локального тестирования читайте в https://github.com/nemilya/vk-demo/blob/master/README.md