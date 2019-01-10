---
layout: post
title: Books I Read in 2018 Part 1
image: https://lh3.googleusercontent.com/UUvKZ5XV_B5nMhbq3RwOmz7eU65vIBPUrzY72Cf3rfbt_jZxXMFMHCih2CnDC3Q7P9oBOw8blAks7fi7zTzjcYMeDs6G2HycK3Jd68KHzBOCQEcxbEGBMTKPbWtsWdSBWyze36BhlC45QBjcFm69YEwTKS-HXa0oH22uLdqvcncwZ-i_mbFMnWR64bywEST8lFsFyHfQrYox_iM4YaV1LhpnqAc_3_og88l6kasfFK-LJ_N4L2kaEncEzwdrgBtjA3onrbL08BCSlRyA-HmhrbRhXesomROfNYQOMf7Nlp3lK0_4fG7aXU2JVfMcOE4eW65y9fDrhEY49FYAe8egWhyU4ehhgo6wk968E8ZA1Liiig1DYmeceoUl9GY4UUgXehzxSqqUGYND8Qhto4kUZshQkOwMX3cMJqhOuep8KWh9CeoC2XIFCxZsCjJeUdz_poy42ZFu-Kjef5W_FPmHyKTstuuF2iZ677ShXC8a1JXZTVxe5_AvPwMflknjYqP7_6WMCcWnp2-kXexJaCmVRr_gG6T5TjRzhgop-jH8juSlax68UVrMWFxZ1qe3ySZg_0cWaiTfWba1IB1v3fA2lUx9XuN9XiEStDQ5zIGW9wGoHf4fW9uu4FYqoRXmJRhCc4Kb1tAxx7KsiHNZTld3KhC4iQ=w774-h1032-no
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

