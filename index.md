---
layout: default
---
# Hi, welcome and thanks for your time

## Palestine

What is happening in Palestine has fundamentally changed the way I see the world. I share below some of the resources I found most important. As Francesca Albanese put it, ["knowledge is subversive and the primary tool to keep alive the possibility of a peaceful future."](https://www.esquerda.net/artigo/francesca-albanese-o-ultimo-ano-mudou-completamente-minha-forma-de-olhar-para-o-mundo/92452)

[This investigation by Al Jazeera](https://www.aljazeera.com/program/investigations/2024/10/7/war-crimes-in-gaza-i-al-jazeera-investigations) of what is going on in Gaza is extremely hard to watch _and_ extraordinarily important. Please watch it only when you feel like you can handle it.

In the three episodes of [Along the Green Line](https://www.youtube.com/playlist?list=PLa_1MA_DEorGnakB7QV1Q_LBpHgtGQDxi), Matthew Cassel (The Guardian) travels along the 1949 Armistice border, or ‘Green Line’, and meets Palestinians and Israelis living just kilometres apart.

## Latest from [Blog](/blog)

{% assign sorted_items = site.posts | sort: 'date' | reverse %}
{% for post in sorted_items limit:6 %}
{% unless post.draft %}

* {{ post.date | date: "%Y-%m-%d" }}: [{{ post.title | xml_escape }}]({{ post.url | strip }})

{% endunless  %}
{% endfor %}

## Latest from [Atualidade](/atualidade)

{% assign sorted_items = site.shorts | sort: 'date' | reverse %}
{% for post in sorted_items limit:5 %}

* {{ post.date | date: "%Y-%m-%d" }}: [{{ post.title | xml_escape }}]({{ post.link | strip }})

{% endfor %}

## Politics, Economics and the Media

I am deeply concerned about the insane levels of _inequality_ we have today.

Today, even within wealthy countries, it is possible for someone to make 10 000 000 times more money per year than someone else working full-time.

[The disparity in wealth is all the more extreme and all the more absurd.](https://wid.world/)

While the rate of return of capital remains higher than the (real) economic growth _per capita_, the gap will only widen — unless capital is regularly re-distributed. Closing the gap must be a top priority.

__Workers must be the ones to reap the fruits of our labor.__

I would much like to see rich countries lowering the taxes for those that earn/have less than the median (or even those below the 90th percentile) while raising the overall tax revenue - so that universal education and healthcare may improve without putting the burden on those who have less.

Governments must not shy away from bold investments in education, healthcare and in the green transition.

However, they must not spend hard-earned resources in luxury projects or subsidizing consumerism.

I have gathered [here](https://mesquita.xyz/links) some ((exclusively) external) content on economics and politics. I'm aware french economists are very much over-represented. While i really appreciate their work, i'll try and expand this list with additional interesting material coming from other parts of the globe. Please do share with me other bodies of work you recommend!

I am a member of [Bloco de Esquerda](https://www.bloco.org/). Whatever[^1] your political inclinations, I urge you to join a political party — there's __plenty__ to do and not enough people take up their civic duty, in my opinion.

I get most of my news from The Guardian (which i subscribe to) and hold a lifetime subscription to [Jacobin](https://jacobin.com/). I also support [Fumaça](https://fumaca.pt) (PT).

## My view on charity

While I don't see charity as the principal tool for a better tomorrow, [relatively rich people in rich countries can effectively help out people in poor countries](https://duckduckgo.com/?q=peter+singer+effective+youtube&t=newext&atb=v330-3&iax=videos&ia=videos&iai=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DDiuv3XZQXyc). My contribution won't solve world hunger, but i'm sure each of us is capable of ending someone's hunger — actually, multiple people's — and that can only be worthwhile.

Since 2020, I have been donating 10% of the money i earn. I currently support [Give Directly](https://www.givedirectly.org/) (see [its finances](https://www.givedirectly.org/financials/); [and a study on unconditional cash transfers](https://haushofer.ne.su.se/publications/Haushofer_Shapiro_UCT_QJE_2016.pdf)), the [World Central Kitchen](https://wck.org/) (present in [Gaza](https://wck.org/relief/chefs-for-gaza/)) and [Doctors Without Borders](https://www.doctorswithoutborders.org) (also in [Gaza](https://www.doctorswithoutborders.org/latest/our-response-israel-gaza-war)).

I would urge you to please consider giving away the money you can spare.

## Internet Usage

The internet is amazing, and technology does not have to come coupled with predatory practices. I use [Signal](https://signal.org/) exclusively for messaging. It is a great open-source app functionally equivalent to Whatsapp.

[“Once the technology is in place, there will always be the temptation to use it. And it is poor civic hygiene to install technologies that could someday facilitate a police state.”](https://www.schneier.com/essays/archives/2013/07/mission_creep_when_e.html)

## Bio

I was born and raised in the Azores, and have been living happily abroad (Leuven, Lisbon, New York and Paris).

I complain a lot. That does not mean i do not appreciate how extraordinarily lucky i have been so far. I can only hope it keeps that way.

Feel free to drop me an email at f at mesquita dot xyz.

## Have a great fucking day, _foda-se_!

\- f.

(last update: 2026.02.23)

[^1]: well... _whatever_ might be too strong of a term.
