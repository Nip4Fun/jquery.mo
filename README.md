jquery.mo

By Nip4Fun
Модальное окно v 1.1

Все примеры описаны в demo.html

На данный момент работают 3 разных эфекта вывода.

Что бы обвизать комплекс картинок\текста в модальное окно, нужно:
1) Завизать их на общий id и data-mo-id.
2) Выбрать анимацию в data-animation одну из (fadeAndPop/fade/none), если не указывать data-animation, то по умолчанию будет none.

Пример:


<div> &lt;a href=&quot;#&quot; data-mo-id=&quot;1&quot; data-animation=&quot;fadeAndPop&quot;&gt;</div> <div> Появление и скачек(fade pop)</div> <div> &lt;/a&gt;</div> <div> &lt;div id=&quot;1&quot; class=&quot;mo&quot;&gt;</div> <div> &lt;a class=&quot;close-mo&quot;&gt;&amp;#215;&lt;/a&gt;</div> <div> &lt;h1&gt;Заглавный текст&lt;/h1&gt;</div> <div> &lt;p&gt;просто текст для проверки модального окна(fadeAndPop)&lt;/p&gt;</div> <div> &lt;/div&gt;</div>
