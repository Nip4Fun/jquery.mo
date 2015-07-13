<plaintext>
jquery.mo
By Nip4Fun
Модальное окно v 1.1

Все примеры описаны в demo.html

На данный момент работают 3 разных эфекта вывода.

Что бы обвизать комплекс картинок\текста в модальное окно, нужно:
1) Завизать их на общий id и data-mo-id.
2) Выбрать анимацию в data-animation одну из (fadeAndPop/fade/none), если не указывать data-animation, то по умолчанию будет none.

Пример:


<a href="#" data-mo-id="1" data-animation="fadeAndPop">
	Появление и скачек(fade pop)
</a>
<div id="1" class="mo">
	<a class="close-mo">&#215;</a>
		<h1>Заглавный текст</h1>
			<p>просто текст для проверки модального окна(fadeAndPop)</p>
</div>
