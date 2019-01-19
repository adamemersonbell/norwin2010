---
layout: post
title: Books I Read in 2018 Part 1
image: https://lh3.googleusercontent.com/wBVXgAhHDglNIXd3_-20AbDwAQf2Sajn-cfDicWhz86Hrq0tNlhSrp_tPF-tOTDwLFsiKG3ceVmIzFYwiV1cjiIZNrjRS8a12ECvlRaSp5RnL1qEprYQzY0TYX3HZBhSGJCx2L1zRtk=w2400
tags: books
summary: I start recounting the books I read in 2018 and some brief thoughts on each.
---
At the start of 2018, I set a goal to try to read a book on average each week. I didn't quite make it to 52, but I read more books than I probably would have otherwise. 

My reading goes in cycles - sometimes I can barely put books down until every page has been read, while other times I can't seem to make it through ten pages without wanting to do literally anything else. A lot of this depends on how well a book can get its hooks into me, but even then it may take a few tries to get moving. Lately, it's been newer science fiction and fantasy books that have hooked me in.

Reading non-fiction books in anything but short bursts has always been difficult for me. I enjoy the way that these books present an opportunity to learn much more in-depth information about a single topic than you can find anywhere else, but there's only so much of any given topic that I can keep focus on for a long time. As a result, only a few of these made the "completed" list.

Tabletop Roleplaying rulebooks make up a large portion of my completed books for 2018. I've been slowly getting more and more into TTRPGs since I was first introduced to it in ~2012, but until this year had only played Dungeons and Dragons (briefly 4e and a fair amount of 5e), a small stint in Pathfinder, and a couple of sessions of Fiasco. In 2017, I started running my very first game of D&D and found myself enjoying that aspect of the hobby a lot more than I thought I would. I began reading other game systems to see what else the hobby had to offer, and found many of the issues I have with D&D answered by these games.

Below are some of the books that I finished this year. It's not everything, but I may come back to write about the other books eventually.

---

{% for book in site.data.2018bookspt1 %}
<div><h4>{{ book.title }} by {{ book.author }}</h4></div>
<div class="row">
	<div class="col s12 m4">
		<img class="responsive-img" src="{{ book.image }}">
	</div>
	<div class="col s12 m8">
		<p>
		{{ book.synopsis }}
		</p>
	</div>
</div>

---

{% endfor %}

