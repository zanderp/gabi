# Aplicatie News Feed

 ## 1. Aplicatia Newsfeed:
 +[http://rss.stirileprotv.ro/](http://rss.stirileprotv.ro/)  +[http://rss.realitatea.net/stiri.xml](http://rss.realitatea.net/stiri.xml)

 Aplicatia va trebui sa aiba o icoana de meniu, de unde sa se deschida un meniu in genul celui de la facebook [DEMO HERE](http://images.mobile-patterns.com/1366735342502-2013-04-16%2015.10.02.png) , overlay peste continut, in care sa ai setari si informatii despre aplicatie. Daca apesi oricare item din meniu se va deschide un popup ![Minion] (https://cdn.dribbble.com/users/479285/screenshots/2342273/popup_1x.jpg) unde vom avea o descriere pentru pagina de informatii despre autor si versiune iar pe pagina de setari vom avea urmatoarele:
 + selector dimensiune font
 + Selector culoare aplicatie
 + Un input unde vom itroduce feedurile RSS
 + Un tabel unde vom avea insirate feedurile existente, salvate in local storage cu optiunea de a le sterge/edita.
 [DEMO HERE](https://www.phpflow.com/wp-content/uploads/2015/06/angular_complete.png)

 ## 2. Aplicatia va arata stirile intr-un format wall.
 [DEMO HERE](https://i.stack.imgur.com/I28sp.png), fiecare element din wall va avea un buton x in dreapta sus de unde se va ascunde stirea permanent(salvat in local storage), dedesubt va avea buton de share pentru retele sociale si alte aplicatii + buton de comment (unde vom lasa comentarii asupra unei stiri in local storage).

 ## 3. Cand se deschide aplicatia
 Cand se deschide aplicatia vom folosi un loader [LOADER]( http://imgur.com/8YsAmq3 ) pana se incarca informatia pentru stiri, nu vom afisa mai mult de 10 stiri la inceput, iar cand efectuam scroll vom afisa stire dupa stire pana cand nu vor mai fi stiri disponibile si vom afisa un mesaj (de genul No more news for now, add a new rss link or wait until tomorrow).

 4. Tehnologii folosibile (this is my commment ::: wtf?????):
  + Html
  + Css
  + Javascript( jQuery, EmberJs, Angular)
