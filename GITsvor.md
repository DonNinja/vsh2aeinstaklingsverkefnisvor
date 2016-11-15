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