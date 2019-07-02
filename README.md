# C-compiler---for-and-switch-contructs
A lex-Yacc C compiler for FOR and SWITCH contructs

Simple examples to be checked are given in test-1/2/3
Tokens are recognized using the c_tokens lex file
Abstract symbol tree is generated for given tests from c_AST
With the AST generated intermediate code is generated with c_ICG, which also Optimizes the ICG, considering few of the optimizing rules.
