---
layout: post
title: Books I Read in 2018 Part 1: Fiction
---

At the start of 2018, I set a goal to try to read a book on average each week. 

[introduction - goal to read a book a week, reasons for choosing certain books, etc]

{% for book in site.data.2018bookspt1.yaml %}
<div class="mediatitle">{{ book.title }}</div>
<div class="mediaoverview row">
	<img class="mediaimg column" src="book.image">
	<div class="mediatext row">
		<details>
			<summary>
				{% for line in book.synopsis %}
				<p>{{ line }}</p>
				{% endfor %}
			</summary>
			{% for line in book.reaction %}
			<p>{{ line }}</p>
			{% endfor %}
		</details>
	</div>
</div>
{% endfor %}

***


[wrap up]
-Adam


***
¹

²

³

