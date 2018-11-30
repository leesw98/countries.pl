# countries.pl

Prolog implementation of NLP-like queries about country statistics

Authors: Tom Lee, Susie Chen, James Luo

Usage: Import via consulting in SWI-Prolog

```prolog
?- ["<filepath>/countries.pl/main.pl"].
true
?- q(Ans).
"List of score attributes that you can inquire about:"
"Country, Region, Happiness Rank, Happiness Score, GDP score, Family score,"
"Life Expectancy score, Freedom score, Government Corruption score, "
"Generosity score, Dystopia Residual score"

"Sample Queries: what is the happiness rank of sweden?"
"                what is the gdp score of france."
"                what countries are in western europe"

"Please enter query in lowercase."
Ask me: what is the family score of argentina?
Ans = 1.15137
false.
```

Testing: Only applicable to `grammar.pl`

```prolog
?- ["<filepath>/countries.pl/grammar.pl"].
true
?- run_tests.
% PL-Unit: grammar ............ done
% All 16 tests passed
true.
```

Disclaimer: This project was made as a part of UBC CPSC 312 Project. This project will not be maintained after December 2018.
