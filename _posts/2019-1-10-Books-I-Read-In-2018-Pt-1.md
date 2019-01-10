---
layout: post
title: Books I Read in 2018 Part 1
image: https://lh3.googleusercontent.com/wBVXgAhHDglNIXd3_-20AbDwAQf2Sajn-cfDicWhz86Hrq0tNlhSrp_tPF-tOTDwLFsiKG3ceVmIzFYwiV1cjiIZNrjRS8a12ECvlRaSp5RnL1qEprYQzY0TYX3HZBhSGJCx2L1zRtk=w2400
tags: books
---

At the start of 2018, I set a goal to try to read a book on average each week. 

[introduction - goal to read a book a week, reasons for choosing certain books, etc]

{% for book in site.data.2018bookspt1 %}
<div class="mediatitle">{{ book.title }} by {{ book.author }}</div>
<div class="mediaoverview row">
	<img class="mediaimg mycolumn" src="{{ book.image }}">
	<div class="mediatext myrow">
		<details>
			<summary>
				{{ book.synopsis }}
			</summary>
			{{ book.reaction }}
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

