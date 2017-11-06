---
layout: base
title:  'Statistics of nmod:npmod in UD_English-PUD'
udver: '2'
---

## Treebank Statistics: UD_English-PUD: Relations: `nmod:npmod`

This relation is a language-specific subtype of <tt><a href="en_pud-dep-nmod.html">nmod</a></tt>.
There are also 2 other language-specific subtypes of `nmod`: <tt><a href="en_pud-dep-nmod-poss.html">nmod:poss</a></tt>, <tt><a href="en_pud-dep-nmod-tmod.html">nmod:tmod</a></tt>.

19 nodes (0%) are attached to their parents as `nmod:npmod`.

14 instances of `nmod:npmod` (74%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.26315789473684.

The following 7 pairs of parts of speech are connected with `nmod:npmod`: <tt><a href="en_pud-pos-NUM.html">NUM</a></tt>-<tt><a href="en_pud-pos-NOUN.html">NOUN</a></tt> (6; 32% instances), <tt><a href="en_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_pud-pos-NOUN.html">NOUN</a></tt> (3; 16% instances), <tt><a href="en_pud-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_pud-pos-NOUN.html">NOUN</a></tt> (3; 16% instances), <tt><a href="en_pud-pos-ADJ.html">ADJ</a></tt>-<tt><a href="en_pud-pos-NOUN.html">NOUN</a></tt> (2; 11% instances), <tt><a href="en_pud-pos-ADV.html">ADV</a></tt>-<tt><a href="en_pud-pos-NOUN.html">NOUN</a></tt> (2; 11% instances), <tt><a href="en_pud-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_pud-pos-PRON.html">PRON</a></tt> (2; 11% instances), <tt><a href="en_pud-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_pud-pos-PRON.html">PRON</a></tt> (1; 5% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 7 nmod:npmod	color:blue
1	Such	such	ADJ	JJ	Degree=Pos	2	amod	_	_
2	settlements	settlement	NOUN	NNS	Number=Plur	4	nsubj	_	_
3	probably	probably	ADV	RB	_	4	advmod	_	_
4	began	begin	VERB	VBD	Mood=Ind|Tense=Past|VerbForm=Fin	0	root	_	_
5	around	around	ADV	RB	_	6	case	_	_
6	1000	1000	NUM	CD	NumType=Card	4	obl	_	_
7	BC	bc	NOUN	NN	Number=Sing	6	nmod:npmod	_	SpaceAfter=No
8	,	,	PUNCT	,	_	12	punct	_	_
9	when	when	ADV	WRB	PronType=Int	12	advmod	_	_
10	eastern	eastern	ADJ	JJ	Degree=Pos	11	amod	_	_
11	Melanesians	Melanesians	PROPN	NNPS	Number=Plur	12	nsubj	_	_
12	travelled	travel	VERB	VBD	Mood=Ind|Tense=Past|VerbForm=Fin	4	advcl	_	_
13	north	north	ADV	RB	_	12	advmod	_	SpaceAfter=No
14	.	.	PUNCT	.	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 11 nmod:npmod	color:blue
1	The	the	DET	DT	Definite=Def|PronType=Art	4	det	_	_
2	Tell	Tell	PROPN	NNP	Number=Sing	4	compound	_	_
3	Amarna	Amarna	PROPN	NNP	Number=Sing	2	flat	_	_
4	letters	letter	NOUN	NNS	Number=Plur	13	nsubj	_	SpaceAfter=No
5	,	,	PUNCT	,	_	6	punct	_	_
6	dating	date	VERB	VBG	VerbForm=Ger	4	acl	_	_
7	from	from	ADP	IN	_	10	case	_	_
8	the	the	DET	DT	Definite=Def|PronType=Art	10	det	_	_
9	14th	14th	ADJ	JJ	Degree=Pos|NumType=Ord	10	amod	_	_
10	century	century	NOUN	NN	Number=Sing	6	obl	_	_
11	BCE	bce	NOUN	NN	Number=Sing	10	nmod:npmod	_	SpaceAfter=No
12	,	,	PUNCT	,	_	6	punct	_	_
13	include	include	VERB	VBP	Mood=Ind|Tense=Pres|VerbForm=Fin	0	root	_	_
14	ten	ten	NUM	CD	NumType=Card	15	nummod	_	_
15	letters	letter	NOUN	NNS	Number=Plur	13	obj	_	_
16	from	from	ADP	IN	_	18	case	_	_
17	the	the	DET	DT	Definite=Def|PronType=Art	18	det	_	_
18	kings	king	NOUN	NNS	Number=Plur	15	nmod	_	_
19	of	of	ADP	IN	_	20	case	_	_
20	Gezer	Gezer	PROPN	NNP	Number=Sing	18	nmod	_	_
21	swearing	swear	VERB	VBG	VerbForm=Ger	18	acl	_	_
22	loyalty	loyalty	NOUN	NN	Number=Sing	21	obj	_	_
23	to	to	ADP	IN	_	26	case	_	_
24	the	the	DET	DT	Definite=Def|PronType=Art	26	det	_	_
25	Egyptian	egyptian	ADJ	JJ	Degree=Pos	26	amod	_	Proper=True
26	pharaoh	pharaoh	NOUN	NN	Number=Sing	21	obl	_	SpaceAfter=No
27	.	.	PUNCT	.	_	13	punct	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 6 nmod:npmod	color:blue
1	On	on	ADP	IN	_	4	case	_	_
2	the	the	DET	DT	Definite=Def|PronType=Art	4	det	_	_
3	1st	1st	ADJ	JJ	Degree=Pos|NumType=Ord	4	amod	_	_
4	January	January	PROPN	NNP	Number=Sing	10	obl	_	_
5	49	49	NUM	CD	NumType=Card	4	nummod	_	_
6	BC	bc	NOUN	NN	Number=Sing	4	nmod:npmod	_	SpaceAfter=No
7	,	,	PUNCT	,	_	10	punct	_	_
8	Marco	Marco	PROPN	NNP	Number=Sing	10	nsubj	_	_
9	Antonio	Antonio	PROPN	NNP	Number=Sing	8	flat	_	_
10	read	read	VERB	VBD	Mood=Ind|Tense=Past|VerbForm=Fin	0	root	_	_
11	a	a	DET	DT	Definite=Ind|PronType=Art	12	det	_	_
12	declaration	declaration	NOUN	NN	Number=Sing	10	obj	_	_
13	from	from	ADP	IN	_	14	case	_	_
14	Caesar	Caesar	PROPN	NNP	Number=Sing	12	nmod	_	_
15	in	in	ADP	IN	_	16	case	_	_
16	which	which	PRON	WDT	PronType=Rel	19	obl	_	_
17	the	the	DET	DT	Definite=Def|PronType=Art	18	det	_	_
18	proconsul	proconsul	NOUN	NN	Number=Sing	19	nsubj	_	_
19	declared	declare	VERB	VBD	Mood=Ind|Tense=Past|VerbForm=Fin	12	acl:relcl	_	_
20	himself	himself	PRON	PRP	Case=Acc|Gender=Masc|Number=Sing|Person=3|PronType=Prs|Reflex=Yes	19	obj	_	_
21	a	a	DET	DT	Definite=Ind|PronType=Art	22	det	_	_
22	friend	friend	NOUN	NN	Number=Sing	19	xcomp	_	_
23	of	of	ADP	IN	_	24	case	_	_
24	peace	peace	NOUN	NN	Number=Sing	22	nmod	_	SpaceAfter=No
25	.	.	PUNCT	.	_	10	punct	_	_

~~~

