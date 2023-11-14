# cpp-digest-7

C++ Дайджест №7 (30 октября – 12 ноября 2023) 

Теги: дайджест, c++-дайджест, c++

Хабы: Программирование, C++

## Аннотация

Привет, Хабр! Сегодня я хочу вам представить подборку интересных новостей и материалов из мира C++ за последние две недели.

Приятного чтения!

## ⚡️️ Новости и релизы

1. 21 ноября, бесплатно, [C++ митап в Москве и онлайне](https://engineer.yadro.com/cpp-meetup/?utm_source=habr&utm_medium=referral&utm_campaign=cppdigest13112023) — Константин Владимиров, Илья Шишков и инженеры YADRO поговорят о С++23, lifetime extension и технических собеседованиях.
2. [CLion Nova Explodes onto the C and C++ Development Scene](https://blog.jetbrains.com/clion/2023/11/clion-nova/) — Презентация CLion Nova — того же CLion, но на движке [ReSharper C++](https://www.jetbrains.com/resharper-cpp/) ([Rider C++](https://www.jetbrains.com/lp/rider-unreal/)): улучшение производительности основных операций (подсветка кода, полнотекстовый поиск, индексирование файлов); улучшение отзывчивости UI; частичный отказ от [clang language server](https://clangd.llvm.org/).

## 📝 Статьи

1. Marco Arena: [SObjectizer Tales – 4: Handling commands](https://marcoarena.wordpress.com/2023/11/02/sobjectizer-tales-4/) — Продолжение серии статей, посвященной построению программ на основе акторной модели с помощью [SObjectizer](https://github.com/Stiffstream/sobjectizer): Об обработке команд.
2. Rainer Grimm: [The Ranges Library in C++20: Design Choices](https://www.modernescpp.com/index.php/the-ranges-library-in-c20-design-choices/), [The Ranges Library in C++20: More Design Choices](https://www.modernescpp.com/index.php/the-ranges-library-in-c20-more-design-choices/) — Краткий обзор основых особенностей диапазонов (*ranges*, C++20).
3. Dian-Lun Li: [A Concise Introduction to Coroutines](https://www.modernescpp.com/index.php/a-concise-introduction-to-coroutines-by-dian-lun-li/) — Введение в корутины (C++20): О Promise Type, Awaitable и Coroutine Handle.
4. Sandor Dargo: [C++23: Removing garbage collection support](https://www.sandordargo.com/blog/2023/11/01/cpp23-garbage-collection) — Повесть о поддержке сборки мусора в C++: включенной в C++11, так нигде и не реализованной, окончательно удаленной в C++23.
5. Sandor Dargo: [Extern templates to reduce binary size](https://www.sandordargo.com/blog/2023/11/08/extern-templates) — Об использовании `extern template` для сокращения размеров бинарных файлов.
6. Herb Sutter: [Trip report: Autumn ISO C++ standards meeting (Kona, HI, USA)](https://herbsutter.com/2023/11/11/trip-report-autumn-iso-c-standards-meeting-kona-hi-usa/) — Отчёт о недавно прошедшей встрече WG21 (Комитет по стандартизации C++) в Коне: какие пропозалы вошли в C++26 (pack indexing, `<linalg>`, `<debugging>`); какие вот-вот войдут, но требуют небольших доработок (contracts, reflection); и для каких поезд уже ушёл.
7. a4z: [Compile time string literals processing, but why?](https://a4z.gitlab.io/blog/2023/11/04/Compiletime-string-literals-processing.html) — О том, какие операции над строковыми литералами мы можем выполнять в компайл-тайме.
8. The CLion Blog: [Striving For Better C++ Code, Part I: Data Flow Analysis Basics](https://blog.jetbrains.com/clion/2023/11/striving-for-better-cpp-code-part-i-data-flow-analysis-basics/) — О том, что такое анализ потоков данных, и какие ошибки в вашем коде с его помощью может находить CLion.

## 📺 Видео и доклады

1. Jason Turner: [C++ Weekly — Ep 400 — C++ is 40... Is C++ DYING?](https://www.youtube.com/watch?v=hxjSpasg3gk) — Юбилейный эпизод с слегка кликбейтным заголовком. Пациент жив или мертв? О статистике и примерах использования C++ в различных областях и динамике его эволюции.
2. Jason Turner: [C++ Weekly — Ep 401 — C++23's chunk view and stride view](https://www.youtube.com/watch?v=3ZeV-F1Rbaw) — Завершение серии видео о новых представлениях (*views*), добавленных в C++23: О [chunk_view](https://en.cppreference.com/w/cpp/ranges/chunk_view) и [stride_view](https://en.cppreference.com/w/cpp/ranges/stride_view).

### MUC++

1. Elizaveta Shulankina: [Analyzing C++ applications for performance optimization](https://www.youtube.com/watch?v=M1D8iez1Ph0) — Введение в анализ производительности программ на C++ с помощью [Intel VTune Profiler](https://www.intel.com/content/www/us/en/developer/tools/oneapi/vtune-profiler.html) и [Intel Advisor](https://www.intel.com/content/www/us/en/developer/tools/oneapi/advisor.html).
2. Tristan Brindle: [Iteration Revisited](https://www.youtube.com/watch?v=bMitr8ReVeg) — О проблемах безопасности итераторов и библиотеке [Flux](https://github.com/tcbrindle/flux), предлагающей более безопасные и не менее производительные абстракции для итерации по последовательностям.
4. Björn Fahller: [Moar functional in C++23](https://www.youtube.com/watch?v=NoSfRWUX6j0) — О [функциях высшего порядка](https://w.wiki/88wg) и том, как они могут сделать ваш код более гибким и выразительным.

## Послесловие

> Дайджест составлен и опубликован при поддержке московского сообщества программистов [C++ Moscow](https://t.me/cppmoscow_info)

Заметили ошибку или опечатку? Сообщите в личку ([telegram](https://t.me/eoanermine), [habr](https://habr.com/ru/conversations/eoanermine/))

Прислать ссылку можно [через форму](https://forms.yandex.ru/cloud/64f48043e010db921819c447/) или просто написав мне в личные сообщения ([telegram](https://t.me/eoanermine), [habr](https://habr.com/ru/conversations/eoanermine/))

← Предыдущий выпуск: [C++ Дайджест №6](https://habr.com/ru/articles/770958/)
