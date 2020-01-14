---
title: Home
layout: default
---

<div style="text-align: center">
	<img class="post-image" src="{{ site.baseurl }}/files/profile.png" />
</div>



<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<div class="socialmedia" style="text-align: center">
<a href="https://ie.linkedin.com/in/albertoponcelas/en">
	<i class="fa fa-linkedin-square"></i>
</a>
<a href="https://scholar.google.com/citations?user=OHKfbi4AAAAJ">
	<i class="fa fa-graduation-cap"></i>
</a>
<a href="https://github.com/alberto-poncelas">
	<i class="fa fa-github-square"></i>
</a>
<a href="https://twitter.com/albponcelas">
	<i class="fa fa-twitter-square"></i>
</a>
</div>

{% if site.metadata.social-media %}
<div id="social-media">
    {% assign sm = site.metadata.social-media %}
    {% for entry in sm %}
        {% assign key = entry | first %}
        {% if sm[key].id %}
            <a href="{{ sm[key].href }}{{ sm[key].id }}" title="{{ sm[key].title }}"><i class="fa {{ sm[key].fa-icon }}"></i></a>
        {% endif %}
    {% endfor %}
</div>
{% endif %}




# About me

I am currently a researcher at ADAPT Centre. As I am passionate about languages, my research interests are Machine Translation and NLP. I hold a PhD in Machine Translation from Dublin City University in Ireland and a M.Sc. in Machine Learning from the University of the Basque Country. I have also worked as a Software and Big Data Engineer.



You can find me in:

* [LinkedIn][linkedin]
* [Google Scholar][gscholar]
* [Github][github]
* [ResearchGate][researchgate]
* [Twitter][twitter]
* [ORCID][ORCID]


[linkedin]: https://ie.linkedin.com/in/albertoponcelas/en
[gscholar]: https://scholar.google.com/citations?user=OHKfbi4AAAAJ
[github]: https://github.com/alberto-poncelas
[researchgate]: https://www.researchgate.net/profile/Alberto_Poncelas
[twitter]: https://twitter.com/albponcelas
[ORCID]: https://orcid.org/0000-0002-5089-1687
