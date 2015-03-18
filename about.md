---
layout: page
permalink: /about/index.html
title: About Me
tags: [about doctor500]
imagefeature:

---
<figure>
  <img src="{{ site.url }}/images/dotor500-profile.png" alt="dotor500 - David Layardi">
</figure>

{% assign total_words = 0 %}
{% assign total_readtime = 0 %}
{% assign featuredcount = 0 %}
{% assign statuscount = 0 %}

{% for post in site.posts %}
    {% assign post_words = post.content | strip_html | number_of_words %}
    {% assign readtime = post_words | append: '.0' | divided_by:200 %}
    {% assign total_words = total_words | plus: post_words %}
    {% assign total_readtime = total_readtime | plus: readtime %}
    {% if post.featured %}
    {% assign featuredcount = featuredcount | plus: 1 %}
    {% endif %}
{% endfor %}

Indonesia :

Hi, saya **David Layardi**, terima kasih telah mengunjungi blogku. Saya baru memberikan {{ site.posts | size }} postingan di dalam {{ site.categories | size }} kategori dengan {{ total_words }} kata. {% if featuredcount != 0 %} Ada <a href="{{ site.url }}/featured">{{ featuredcount }} featured post</a>, yang aku rekomenkasikan untuk anda.{% endif %}

Saya hanya manusia biasa yang tertarik dengan komputer. berkecimpung dalam dunia programming diawali dari rasa penasaran saya. ya seperti yang selalu ada di deskripsi blog ini. Pengetahuan berawal dari Keingintahuan, jadi semua dilakukan dengan otodidak.

awalnya saya hanya belajar **Desktop Programming** , lalu saya belajar dan belajar hingga saya bisa menciptakan sebuah program bernama **Frost Antivirus** . Frost Antivirus cukup membanggakan bagi saya karena antivirus ini telah beradu dalam beberapa kompetisi dan memenangkan beberapa penghargaan :D
lalu setelah beberapa tahun berkecimpung di dunia dosktop programming, lalu saya menemukan hobi saya di dunia **Fotografi** , sayapun mulai mempelajari dunia Fotografi selama beberapa bulan sebagai selingan.
ketika sedang mencari referensi tehnik fotografi. saya melihat sudut pandang lain pada web yang saya lihat, lalu saya mulai mempunyai ketertaikan dengan dunia **Web Programming** , maka sayapun belajar web programming :)

selain fotografi, desktop programming dan web programming. saya juga dan menguasai beberapa office tool seperti word, excel, presentation, dsb. dan saya belajar tentang OS linux, serta mencoba beberapa hardware open source.
saat ini saya mencoba membentuk tim developer yang bernama **White Frost Developer** . kami akan mencoba membuat beberapa project, (Doakan kami ya :D)

English :
(''Hello'')

##Short Biodata

* Nick Name : Doctor500
* Real Name : David Layardi
* Address    : Some Place at West Java
* Hobby     : Coding, Photography, Exploring Computer, linux, and android

###Had Learn...
* Visual Basic 6
* Pascal
* DOS
* PHP
* HTML
* basic CSS
* basic SQL Database
* CMS Modification and Management
* basic Ruby
* basic Markup
* Office Word
* Ofiice Excel
* Office Presentation
* Web Designer
* Basic Web Security
* Photoshop
* Paint :P
* Movie and Sound Editor
* Photography
* Android
* Entrepreneurship, and i forget :D

itu hanya segelintir ilmu yang saya pelajari di dunia ini, dan saya ingin belajar lebih banyak lagi dan memperdalam lagi ilmu yang sudah saya dapat.

that just a little knowledge what i learned from this world, and i want to stuy more and more.

