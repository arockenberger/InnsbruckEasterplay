---


---

<h1 id="innsbruck-easter-play">Innsbruck Easter Play</h1>
<h2 id="about-this-project">About this Project</h2>
<p>InnsOS is a small project I started to try out some complex network analysis for humanities applications, namely character networks in literary texts such as plays. I’ve been inspired by the work done by <a href="https://dlina.github.io/">DLiNA</a> and thought I might as well do something similar with a rather different corpus of dramatic texts: German medieval religious plays. My favorite play is the <a href="https://de.wikipedia.org/wiki/Innsbrucker_Osterspiel">Innsbruck or Neustift Easter Play from 1391</a> which is thought to have originated in my hometown of <a href="https://de.wikipedia.org/wiki/Schmalkalden">Schmalkalden</a>/<a href="https://de.wikipedia.org/wiki/Th%C3%BCringen">Thuringia</a> (in the Thuringian Forest in the middle of Germany) and is quite famous for its extended non-religious, burlesque scene: The so-called Peddler’s Play.</p>
<p>Unlike the hundreds of neatly <a href="http://www.tei-c.org/">XML-TEI</a> encoded and curated German and Russian dramatic texts in the Drama Corpus <a href="https://dracor.org/">dracor</a>, medieval religious plays are not available in digital format, sometimes not even in a printed edition. Thus, I have to gather the necessary data for my analyses manually - usually in form of edges lists and nodes lists that I create as csv files. They can be found in <a href="https://github.com/arockenberger/InnsbruckEasterplay/tree/master/data">data</a> but originate from a Google spreadsheet with significantly more information (that is not needed for CNA).</p>
<p>I play around with network analysis tools, like <a href="https://gephi.org/">Gephi</a>, and try my hand at CNA in Python with the <a href="https://networkx.github.io/">NetworkX</a> library.<br>
You find a <a href="https://github.com/arockenberger/InnsbruckEasterplay/blob/master/CNA_tests.ipynb">Jupyter notebook</a> in which I try to follow along the book <a href="https://pragprog.com/book/dzcnapy/complex-network-analysis-in-python">Complex Network Analysis</a> by Dmitri Zinoviev and another <a href="https://github.com/arockenberger/InnsbruckEasterplay/blob/master/InnsOS_charnet.ipynb">notebook</a> where I try to apply what I learned from the book to the Innsbruck Easter Play data. I’m not very good, though…</p>
<p>In the long run, I want to create a data model for character interaction networks for medieval religious plays, so that relevant data can be collected (manually, I suppose) in a standardized way, gathered in a centrally hosted repository and used for mid-distance ‘reading’ (i.e. analysis) of medieval plays.</p>
<p>Additionally, I want to use this project to teach myself CNA and especially literary network analysis so I can add this to my DH repertoire and teach others in how to do it.</p>
<p>Ultimately, I want to create a corpus of all Norwegian (bokmål/nynorsk) dramatic texts in the digital collection of the <a href="https://www.nb.no/">National Library of Norway</a> and extract character network data in a systematic fashion. This should include the complete edition of <a href="http://ibsen.uio.no/skuespill.xhtml">plays by Henrik Ibsen</a> and <a href="http://holbergsskrifter.no/holberg-public/view?docId=adm/HolbergsWritings.xml&amp;sort=category&amp;lang.set=no#class_skue">plays by Ludvig Holberg</a>, too. To integrate these into larger, international drama corpora would be the final stage.</p>
<p>In the meantime, I will work on this project in my after work hours and publish preliminary outcomes on my weblog <a href="https://textology.hypotheses.org/tag/innsbruck-easter-play">Digital Textology</a>.</p>
<h2 id="overview">Overview</h2>
<p><a href="https://github.com/arockenberger/InnsbruckEasterplay/tree/master/data">Data</a><br>
<a href="https://github.com/arockenberger/InnsbruckEasterplay/tree/master/images">Images</a></p>
<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>

<!--stackedit_data:
eyJoaXN0b3J5IjpbNzQ1MzkzODA0XX0=
-->