A fun lisp like language. By lisp like, it should have prefix notation and lisp macros.

##Goals

Interact with C libraries in a lispy way.

##Test

`gcc -o test tokenizer.c   tokenizer_test.c`, then `./test`.

To test `eval.c` run `gcc -o test eval.c eval_test.c` and then `./test`

(otherwise main.c doesn't do much yet)
