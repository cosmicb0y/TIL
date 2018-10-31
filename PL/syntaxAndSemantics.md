# Syntax and Semantics

- Syntax: the form or structure of the expressions, statements, and program units
- Semantics: the meaning of the expressions, statements, and program units
- Syntax와 semantic은 언어의 정의를 제공한다
------
- A language is a set of sentences
- A sentence is a string of characters over some alphabet
- A lexeme is the lowest level syntactic unit of a language
- A token is a category of lexemes

## Lexical Analysis

- Lexical analyzer는 lexer나 scanner라고 불린다.
```
Source Program -> Lexical Analyzer -> Stream of Tokens
```

## Syntax Analysis

- Syntax analyzer는 parser라고 불린다
```
Stream of Tokens -> Parser -> Abstract Syntax Tree
```

## Grammars

- Grammars express languages
- CFG: 자연언어의 syntax를 묘사하는데 사용
- BNF: John Backus가 Algol 58의 syntax를 묘사하는데 사용
- Derivation: grammar가 어떻게 sentence를 생성할 수 있는지

