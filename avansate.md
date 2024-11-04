![image](https://github.com/user-attachments/assets/f7812446-7ea1-4f8d-aa32-1c8ce70371df)

# Inserarea ecuatiilor si formulelor mathjax

**Sintaxa** 

formulele `MathJax` sunt inserate in aceeasi linie daca sunt plasate intr-o pereche de simboluri `$` 

*exemple* 
Aceasta este o ec $a=bc$ 

formulele `latex` (prin Mathjax) se introduc pe rand nou intre doua perechi de simboluri `$$` 

*exemplu:* 

$$ a=c^b $$

# ridicarea la putere (subscript) 

Se foloseste meta-caracterul `latex` : `_` 

*exemplu:* 

$$ a_i = b^c $$

# Gruparea elementelor din formule

Elementele din formula se grupeaza prin meta-caracterele `{` si `}` 

*exemplu:*  

$$ 10^{10} $$

$$ 10^{5} $$

# Litere grecesti

*Exemple:* 

`\alpha` - alpha litera mica ($$\alpha$$)

`\Alpha`- Alpha cu litera maren ($$\Alpha$$) 

# Parantezele 

-parantezele rotunde se scriu direct (nu au un inteles special `latex` )

-parantezele drepte se scriu direct (nu au un inteles special `latex` )

-ACOLADELE, deoarece ele sunt meta-caractere de grupare, vor fi renderizate corect daca sunt `escapate` de intelesul lor special,punand in fata lor `meta-caracterul` `\` 

*exemplu:* 

$$ a= (a+b){3x}-[3+6x] $$

# Fractiile

` \frac{numarator}{numitor}` 

$$ a = \frac{(a+b)}{(d-c)} $$

# Semne de multiplicare si respectiv diviziune

*Exemple:*

$$ a= c+ 10 \times x $$

$$ a= c+ 10 \cdot x $$ 

$$ a= b \div c $$ 

# Suma de la i=0 la n #

*Exemple:*

$$ \sum_{i=0}^n i^2 - \frac{(a+b) \times (b+c)}{6} $$

# Integrale

*Exemple*

$$ \int_0^1 x^4 dx $$

$$ \iint dubla $$

$$\iiint tripla $$ 














