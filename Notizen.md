# Notizen
Hier werden alle Notizen und Links zu Notiz-Dateien abgelegt.

## Links und Dateien

[Debatte zwischen Musk und Ma (Alibaba)](https://www.youtube.com/watch?v=f3lUEnMaiAU)

[Musk und Ma sind sich nicht einig über Intelligenzpotential der Maschinen:](https://www.youtube.com/watch?v=fS_TfL7rrHI)
--> [Transkript](https://news.theceomagazine.com/business/entrepreneurship/jack-ma-elon-musk-artificial-intelligence/)

Interview with Lex Fridman:
[Teil 1](https://www.youtube.com/watch?v=dEv99vxKjVI&list=PLrAXtmErZgOdP_8GztsuKi9nrraNbKKp4)
[Teil 2 Fridman](https://www.youtube.com/watch?v=smK9dgdTl40)
[Transkript 2. Teil](https://lexfridman.com/wordpress/wp-content/uploads/2019/11/elon_musk_lex_fridman_2_transcript.pdf)

### Notizen zu Markdown, Pandoc, Git
Alles was wir brauchen um effektiv zu arbeiten:

<https://nyenhuis.diskstation.me/wb/pages/topics/dokumentationen-mit-markdown-und-pandoc-erstellen.php>


[Templates für outputs](https://github.com/jgm/pandoc/wiki/User-contributed-templates) (einfach Eisvogel benutzen)

<https://www.youtube.com/channel/UCYspUZGexLdDLjHRkuERQlg/videos>
//TODO: Install Template, create script for various outputs...

Argdown map produzieren: `argdown map zentrale_argumente.argdown --format svg`
Markdown beamer Präsentation: `pandoc Projektvorstellung.md --filter pandoc-citeproc -t beamer -o Vorstellung_pres.pdf`

``\begin{columns}
\begin{column}{0.5\textwidth}
   some text here some text here some text here some text here some text here
\end{column}
\begin{column}{0.5\textwidth}
    \begin{center}
    test
     \end{center}
\end{column}
\end{columns} ``