

##1. Hvað gera eftirfarandi Linux skipanir?
*	cd: Setur mann í main directory ef maður setur ekkert á eftir, annars setur það mann í það directory sem maður velur.
*	cd ~ : Setur mann í sitt eigið home directory ef maður skrifar ekkert annað, annars getur það sett mann í home directory-ið hjá einhverjum öðrum eftir því hvaða user á tölvunni maður velur.
*	ls: Skrifar út öll maps og files á því directory sem maður er á.
*	pwd: Sýnir hvaða directory maður er í.
*	mkdir: Býr til directory með því nafni sem maður skrifar eftir mkdir.

##2. Hvað gera eftirfarandi git skipanir og hvers vegna eru þær gagnlegar?
*	git clone: Hleður niður verkefni og öllum versions af því.
*	git log: Skrifar öll versions af verkefninu.
*	git status: Skrifar öll files sem á eftir að leggja inn, sem eru ný eða búið að breyta.
*	git diff: Sýnir allar breytingar á file sem á eftir að leggja inn.
*	git checkout: Switch-ar í það branch sem er skrifað á eftir og update-ar directory-ið sem er að vinna með.

##3. Hver er munurinn á eftirfarandi git skipunum?
Git diff sýnir file breytingar sem er ekki búið að stage-a, git diff --staged sýnir muninn á því file sem er búið að stage-a fyrir og eftir að það var stage-að og git diff commit1 commit2 sýnir muninn á 1 og 2.

##4. Hvað er útgáfustýring (e.version control)?
Version control er prógramm sem hjálpar liði að fylgjast með breytingunum á source code yfir einhvern tíma og GIT er notað því að það er frítt og opið source sem er létt að nota.

##5. Hverjir eru helstu kostir við að nota GIT?
Það er létt og notalegt að nota það þegar maður lærir á það og maður getur líka séð öll eldri versions af projects þegar maður vill.

##6. Hversu oft telur þú að eigi að gera commit í verkefni, rökstuddu?
Mér finnst að maður ætti að gera commit hvert sinn sem maður lagar eitthvað stærra vandamál eða gerir breytingar við file, því að maður vill að einhver þurfi ekki að leita í gegnum kóðann ef hann vill finna hvað þú gerðir þegar þú settir það aftur inn. Megnið á commits fer allt eftir hvað er unnið að og hversu stórt það er.

##7. Hvað er "Working directory" "Staging area" og "Repository" í GIT?
Working directory er það directory sem heldur source code-inum undir stjórn GIT það er eftir að maður er búinn að commit-a það, staging area er það þegar maður er búinn að breyta kóðanum en áður en maður er búinn að commit-a það inn á GIT og repository er það sem að kóðinn er geymdur í eftir að maður er búinn að setja hann inn á GIT.

##8. Hvenær er sniðugt að nota greinar (branches)? 
Þegar maður vill prófa eitthvað, en ekki missa gamla kóðann sem maður var þegar með.

##Yngvi Leó Þráinsson