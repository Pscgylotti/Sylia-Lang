

<center><h1>Lexicon and Syntax for Sylia-Lang</h1><span style="color:#8f8f8f">By Pscgylotti, Oyyko</span></center>



---

## Lexicon(Not the order in real implementation):

### Basic

​		$\text{ID}\to\text{\lbrack A-Za-z\_\rbrack\lbrack A-Za-z\_0-9\rbrack}^*$

​		$\text{ELSE}\to\text{else}$

​		$\text{WHILE}\to\text{while}$

​		$\text{FOR}\to\text{for}$

​		$\text{SWITCH}\to\text{switch}$

​		$\text{CASE}\to\text{case}$

​		$\text{BREAK}\to\text{break}$

​		$\text{CONTINUE}\to\text{continue}$

​		$\text{RETURN}\to \text{return}$

​		$\text{CLASS}\to\text{class}$

​		$\text{LABEL}\to\text{label}$

​		$\text{ENAME}\to \text{ename}$

​		$\text{RENAME}\to\text{rename}$

​		$\text{OPERATOR}\to\text{operator}$

​		$\text{ASSIGNMENT}\to\text{=}$

​		$\text{INLINECOMMENT}\to \text{//\lbrack}\wedge\text{\\n\rbrack*}$		

​		$\text{MULTILINECOMMENT}\to\text{/*\lbrack}\wedge\text{*\rbrack}^*(\text{*}^+\text{\lbrack}\wedge\text{/\rbrack\lbrack}\wedge\text{*\rbrack}^*)^*\text{*}^+/$

​		$\text{LOCALANONYMOUSFUNCTIONCALL}\to \$$

### Structure

#### Splitter

​		$\text{DOT}\to \text{.}$

​		$\text{SEMICOLON}\to\text{;}$

​		$\text{COMMA}\to \text{,}$

​		$\text{DQT}\to \text{"}$

​		$\text{QT}\to\text{'}$

​		$\text{COLON}\to\text{:}$

#### Braces

​		$\text{LBRACE}\to\text{(}$

​		$\text{RBRACE}\to\text{)}$

​		$\text{LBRACK}\to\text{\lbrack}$

​		$\text{RBRACE}\to\text{\rbrack}$

​		$\text{LBRACS}\to\text{\{}$

​		$\text{RBRACS}\to\text{\}}$

### Relation

​		$\text{LT}\to\text{<}$

​		$\text{GT}\to {>}$

​		$\text{LEQ}\to{<=}$

​		$\text{GEQ}\to\text{>=}$

​		$\text{EQV}\to\text{==}$

​		$\text{EQU}\to\text{===}$

​		$\text{NEQ}\to\text{!=}$

### Calculation

#### Binocular Operator

​		$\text{PLUS}\to\text{+}$ 

​		$\text{MINUS}\to\text{-}$

​		$\text{PRODUCT}\to\text{*}$

​		$\text{DIVIDE}\to\text{/}$

​		$\text{MODULAR}\to\text{\%}$

​		$\text{ANDOP}\to\text{\&}$

​		$\text{OROP}\to\text{|}$

​		$\text{XOROP}\to\wedge$​

​		$\text{AND}\to\text{\&\&}$

​		$\text{OR}\to\text{||}$

#### Monocular Operator

​		$\text{INVERSE}\to\text{-}$​

​		$\text{NOT}\to\text{!}$

​		$\text{NEGATION}\to\sim$

### Type

#### Datatype

​		$\text{INT}\to\text{int}$

​		$\text{LONG}\to\text{long}$

​		$\text{SHORT}\to\text{short}$

​		$\text{BYTE}\to\text{byte}$

​		$\text{FLOAT}\to\text{float}$

​		$\text{DOUBLE}\to\text{double}$

​		$\text{STRING}\to\text{string}$

​		$\text{BOOLE}\to\text{boole}$

#### Nametag

​		$\text{OBJECT}\to\text{object}$

### Data

​		$\text{INTEGER}\to\text{\lbrack+-\rbrack}?\text{\lbrack0-9\rbrack}^+|\text{0x}\text{\lbrack A-Fa-f0-9\rbrack}^+$

​		$\text{FLOATPOINT}\to\text{\lbrack+-\rbrack}?(\text{\lbrack0-9\rbrack}^+\backslash.|\text{\lbrack 0-9\rbrack}^*\backslash.\text{\lbrack 0-9\rbrack}^+|\text{\lbrack 0-9\rbrack}^+(\backslash.\text{\lbrack0-9\rbrack}^*)?\text{\lbrack eE\rbrack \lbrack0-9\rbrack}^+)$

​		$\text{STRING}\to\text{"(\lbrack}\wedge\text{\\"\\\\}\text{\rbrack}^*(\text{\\\\}\lbrack\wedge\text{\\"}\rbrack)^*\text{(\\\\")}^*\text{)}^*\text{"}$

​		$\text{TRUE}\to\text{true}$

​		$\text{FALSE}\to\text{false}$

​		$\text{NULL}\to\text{null}$

​		

### Restriction

​		$\text{STATIC}\to\text{static}$

​		$\text{PUBLIC}\to \text{public}$

​		$\text{PRIVATE}\to \text{private}$

​		$\text{PROTECTED}\to\text{protected}$

​		$\text{FINAL}\to\text{final}$

​		$\text{GLOBAL}\to\text{global}$

​		$\text{CONST}\to\text{const}$

## Syntax:

​		
