---
id: getting-started
title: Начало работы
permalink: docs/getting-started.html
next: add-react-to-a-website.html
redirect_from:
  - "docs/"
  - "docs/index.html"
  - "docs/getting-started-ko-KR.html"
  - "docs/getting-started-zh-CN.html"
  - "docs/installation.html"
  - "download.html"
  - "downloads.html"
  - "docs/try-react.html"
  - "docs/tooling-integration.html"
  - "docs/package-management.html"
  - "docs/language-tooling.html"
  - "docs/environments.html"
---

На этой странице мы сделаем небольшой обзор документации и других ресурсов, которые могут пригодиться при первом использовании React.

**React** — это JavaScript-библиотека для разработки пользовательского интерфейса. Чтобы составить первое впечатление о React, зайдите на [главную страницу](/) или во [введение](/tutorial/tutorial.html).

---

- [Пробуем React](#try-react)
- [Изучаем React](#learn-react)
- [Информация о релизах](#staying-informed)
- [Документация на старые версии React](#versioned-documentation)
- [Обратная связь](#something-missing)

## Пробуем React {#try-react}

React изначально был спроектирован так, чтобы его можно было внедрять постепенно. Другими словами, **вы можете начать с малого и использовать только ту функциональность React, которая необходима вам в данный момент.** Информация в этом разделе будет полезна в любой ситуации: при первом знакомстве с React, при создании простой динамической HTML-страницы и даже при проектировании сложного React-приложения.

### Онлайн-песочницы {#online-playgrounds}

Если вы просто хотите немного поиграть с React, попробуйте онлайн-песочницу. Например, вот простейший шаблон на [CodePen](codepen://hello-world), [CodeSandbox](https://codesandbox.io/s/new) или [Stackblitz](https://stackblitz.com/fork/react).

Если вы предпочитаете работать в своём редакторе, [скачайте тестовый HTML-файл](https://raw.githubusercontent.com/reactjs/reactjs.org/main/static/html/single-file-example.html), добавьте в него код и запустите на своём компьютере. При открытии тестового файла браузер преобразует JSX в обычный код на JavaScript. Такое преобразование достаточно медленно, поэтому мы рекомендуем использовать этот файл только для простых демонстрационных примеров. 

### Добавляем React на сайт {#add-react-to-a-website}

Вы можете [добавить React на свой сайт буквально за одну минуту](/docs/add-react-to-a-website.html). После этого можно разместить на сайте несколько динамических виджетов и постепенно наращивать использование React в своём проекте.

### Создаём React-приложение {#create-a-new-react-app}

Когда вы начинаете проект на React, [то простая HTML-страница со script-тегами](/docs/add-react-to-a-website.html) может быть лучшим вариантом. Её можно сделать за минуту.

Однако для разработки более развесистого приложения вам, скорее всего, придётся рассмотреть другие варианты настройки рабочего окружения, объединяющие в себе различные технологии. Вот несколько наборов JavaScript-инструментов, которые мы рекомендуем для создания приложения. Каждый из этих инструментов может работать практически без настройки и позволит раскрыть все возможности экосистемы React. [Подробнее об инструментах.](/docs/create-a-new-react-app.html)

## Изучаем React {#learn-react}

Люди приходят к React с разным опытом и стилем обучения. Некоторые предпочитают учиться на ходу, а кому-то нравится сначала овладеть теорией. В любом случае мы надеемся, что этот раздел будет для вас полезен.

* Если вам больше нравится **учиться на ходу**, начните с [введения](/tutorial/tutorial.html).
* Если вы хотите **сначала овладеть теорией**, то начните с [пошагового описания React](/docs/hello-world.html).

React сначала может показаться сложным, но приложив усилие, вы *обязательно* его освоите. Терпение и труд все перетрут!

### Простые примеры {#first-examples}

На [главной странице](/) есть несколько простых примеров использования React. Их можно отредактировать и запустить прямо на нашем сайте. Даже если вы пока ничего не знаете о React, попробуйте что-нибудь поменять в коде и посмотрите на результат.

### React для новичков {#react-for-beginners}

Если документация кажется вам сложной и усваивается не так быстро, как хотелось, прочтите [блог Тани Раша (Tania Rascia)](https://www.taniarascia.com/getting-started-with-react/). Таня написала о том, как начала работать с React и доходчиво рассказала об его основных принципах. Попробуйте почитать этот пост, а потом вернуться к документации.

### React для дизайнеров {#react-for-designers}

Если вы в первую очередь занимаетесь дизайном, вам могут пригодиться ресурсы, собранные [на этом сайте](https://reactfordesigners.com/).

### Ресурсы по JavaScript {#javascript-resources}

Изучение React предполагает наличие некоторых знаний о программировании на языке JavaScript. Глубоких знаний не потребуется, но учить React и JavaScript одновременно может быть тяжело. 

Чтобы освежить ваши знания, мы рекомендуем просмотреть [обзор языка JavaScript на сайте mozilla.org](https://developer.mozilla.org/ru/docs/Web/JavaScript/A_re-introduction_to_JavaScript). Для этого потребуется от 30 минут до часа. Надеемся, что теперь вы будете чувствовать себя более комфортно, изучая React.

>Совет
>
>Если всё-таки у вас есть пробелы в знаниях, то сайты [MDN](https://developer.mozilla.org/ru/docs/Web/JavaScript) и [learn.javascript.ru](https://learn.javascript.ru/) будут отличными источниками информации о JavaScript. Также всегда можно задать вопрос или попросить помощи на [форумах нашего сообщества](/community/support.html).

### Введение {#practical-tutorial}

Если вы предпочитаете **изучать технологии на практике**, воспользуйтесь [введением](/tutorial/tutorial.html). В нём описан процесс разработки игры в крестики-нолики. Даже если вы не планируете программировать игры, всё равно уделите внимание этому разделу документации. Приёмы, которые вы освоите — фундамент для разработки *любых* приложений на React. [Введение](/tutorial/tutorial.html) даст вам более глубокое понимание React. 

### Пошаговое описание React {#step-by-step-guide}

Если вам больше нравится **познавать предмет шаг за шагом**, то лучше начать с [пошагового описания React](/docs/hello-world.html). Каждая последующая глава описания опирается на знания из предыдущей, поэтому вы ничего не упустите в процессе изучения материала.

### Философия React {#thinking-in-react}

Многие вспоминают, как чтение [Философии React](/docs/thinking-in-react.html) поставило всё на свои места. Пускай это и самое древнее руководство по React, но оно всё так же актуально.

### Рекомендуемые курсы {#recommended-courses}

Некоторым больше нравится учиться по книгам или видеокурсам от сторонних авторов, а не по официальной документации. Для них мы разместили [список рекомендуемых ресурсов](/community/courses.html). Часть этих ресурсов бесплатны.

### Углублённое изучение React {#advanced-concepts}

После того, как вы изучите [основные принципы React](/docs/hello-world.html) и немного поиграетесь с ним, можно углубиться в более продвинутые темы документации. В этих главах описаны полезные, но не так часто используемые возможности React. Например, [контекст](/docs/context.html) и [рефы](/docs/refs-and-the-dom.html).

### Справочник API {#api-reference}

Этот раздел документации описывает нюансы использования React API. Например, в главе [`React.Component` API](/docs/react-component.html) рассказывается о работе функции `setState()` и различных методах управления жизненным циклом компонентов.

### Глоссарий и FAQ {#glossary-and-faq}

[Глоссарий](/docs/glossary.html) содержит перечень наиболее употребляемых терминов, которые встречаются в документации. Также есть раздел FAQ. В нём короткие вопросы и ответы на самые животрепещущие темы, такие как [использование AJAX](/docs/faq-ajax.html), [состояние компонентов](/docs/faq-state.html) или [структура проекта](/docs/faq-structure.html).

## Информация о релизах {#staying-informed}

В [официальном блоге](/blog/) мы сообщаем о новых релизах React. Все самые важные новости, включая списки изменений и не рекомендуемых к использованию функций, публикуются в первую очередь здесь.

Также вы можете подписаться на наш аккаунт [@reactjs](https://twitter.com/reactjs) в Twitter. Однако вы не пропустите ничего важного, если будете следить только за блогом.

В блоге мы пишем не о всех релизах React, но всегда есть возможность посмотреть полный список изменений [в файле `CHANGELOG.md` в репозитории React](https://github.com/facebook/react/blob/main/CHANGELOG.md), а также на странице [Релизы](https://github.com/facebook/react/releases).

## Документация на старые версии React {#versioned-documentation}

Документация на сайте всегда соответствует последнему стабильному релизу. Начиная с 16 версии React, мы публикуем старые версии документации на [отдельной странице](/versions). Учтите, что копии документации создаются в момент выхода релиза и больше не обновляются.

## Обратная связь {#something-missing}

Если вы обнаружите в документации какие-нибудь неточности, ошибки или любые другие непонятки, пожалуйста, [создайте ишью в репозитории документации](https://github.com/reactjs/reactjs.org/issues/new) с указанием способа решения проблемы или просто [твитните в Twitter @reactjs](https://twitter.com/reactjs). Мы всегда рады слышать вас!
