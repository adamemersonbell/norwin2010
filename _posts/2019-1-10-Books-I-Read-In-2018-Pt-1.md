---
layout: post
title: Books I Read in 2018 Part 1
image: https://lh3.googleusercontent.com/wBVXgAhHDglNIXd3_-20AbDwAQf2Sajn-cfDicWhz86Hrq0tNlhSrp_tPF-tOTDwLFsiKG3ceVmIzFYwiV1cjiIZNrjRS8a12ECvlRaSp5RnL1qEprYQzY0TYX3HZBhSGJCx2L1zRtk=w2400
tags: books
summary: I start recounting the books I read in 2018 and some brief thoughts on each.
---
At the start of 2018, I set a goal to try to read a book on average each week. I didn't quite make it to 52, but I read more books than I probably would have otherwise. 

I very much go in cycles with my reading - some months I will read well over one per week and other months I barely read at all. It really depends on how well a book can get its hooks into me. There were a few trilogies that I ripped through on this list.

Unfortunately, I didn't record the date that I finished each book, so the following overviews are in no particular order.

TKTKTK make this introduction readable.

---

{% for book in site.data.2018bookspt1 %}
<div class="mediatitle">{{ book.title }} by {{ book.author }}</div>
<div class="mediaoverview row">
	<img class="mediaimg column" src="{{ book.image }}">
	<div class="mediatext column">
		{{ book.synopsis }}
		<details>
			<summary>
				Spoilers:
			</summary>
			{{ book.reaction }}
		</details>
	</div>
</div>

---

{% endfor %}

***


[wrap up]
-Adam


***
¹

²

³

