# NiceScrabble

The game of scrabble where being nice matters.

Words are scored against the [AFIN-111](http://www2.imm.dtu.dk/pubdb/views/publication_details.php?id=6010) sentiment analysis wordlist. Words not found in the list score zero, and yes, you can get a negative score for using nasty words.

Given words are scored in entirety, double/triple letter tiles have been removed as they no longer make sense.

Thanks to [Hans Huebner](https://github.com/hanshuebner) for the [initial code](https://github.com/hanshuebner/html-scrabble).
