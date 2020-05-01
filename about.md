---
title: About Me
layout: page
permalink: /about
---

{%- if author.picture contains "://" -%}
	{%- assign author_picture = author.picture -%}
{%- else -%}
	{%- assign author_picture = author.picture | relative_url -%}
{%- endif -%}

<img src="{{ author_picture }}" class="author-avatar u-photo" alt="{{ author.name }}">

I'm a Malware Analyst/Reverse Engineer with 3+ years of experience who currently works at [S21Sec](https://www.s21sec.com/).  I like to participate in CTFs as a hobby, and my team is [Ripp3rs](https://ctftime.org/team/50984).
In my spare time I go to electronic music festivals like Tomorrowland, Ultra Music Festival or EDC Las Vegas.

If you wanna know more, feel free to reach out on the following social media:

* [Github](https://github.com/sisoma2)
* [Twitter](https://twitter.com/sisoma2)
* [Telegram](https://t.me/sisoma2)
