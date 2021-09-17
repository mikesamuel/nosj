# NOSJ
(rhymes with Sausage)

A grammar for parsing JSON right-to-left.

For example, it recognizes

    [ llun, { 32+e20.6: "rebmun" }, ""\\\n\" ]

but rejects invalid inputs like

    "\"\\"

and

    90

Take a gander at the [railroad diagram](https://mikesamuel.github.io/nosj/),
or try out some NOSJ using Paul Kline's [BNF playground][playground] with
[this compatible grammar](https://github.com/mikesamuel/nosj/blob/main/grammar.ebnf).

[playground]: https://bnfplayground.pauliankline.com/
