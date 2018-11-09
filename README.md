# Fractions

Fractional expressions for the [Occam](http://djalbat.com/occam) proof assistant.

These are defined in the `expression.bnf` file simply as follows:
```
fractionalExpression ::= expression "/" expression ;

expression           ::= fractionalExpression ;
```

## Notes

* BNF files for expressions are not currently supported by Occam, something that is awaiting the next release.

## Contact

* james.smith@openmathematics.org
* http://djalbat.com
