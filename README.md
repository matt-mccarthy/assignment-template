# assignment-template

This is a simple template and document class made simplify the creation of simple documents.
This template is tailored towards math-heavy documents.
The class, by default uses bibtex instead of biber.
If you wish to change this, you need to edit simple.cls.

## Commands:

These commands must be before `\begin{document}`.

`\headerbuffer{ N }`
	
This specifies how much space to give the header.
N represents a length such as 12px or 1em.
If LaTeX gives you a warning, just modify N until it does not.

`\lefthead{ N }`

Displays N in the left header on each page.
	
`\righthead{ N }`

Displays N in the right header on each page.

`\centerfoot{ N }`

Displays N in the center footer on each page.

Note that all of the following must be inside math mode.

| Command     | Description                                                               |
|:----------- |:--------------------------------------------------------------------------|
| `\AA`       | Prints the symbol for the algebraics over the rationals.                  |
| `\CC`       | Prints the symbol for the complex numbers.                                |
| `\FF`       | Prints the symbol `\mathbb{F}` (typically used for arbitrary fields).     |
| `\HH`       | Prints the symbol for the quaternions.                                    |
| `\KK`       | Prints the symbol `\mathbb{K}` (typically used for arbitrary fields).     |
| `\NN`       | Prints the symbol for the natural numbers.                                |
| `\QQ`       | Prints the symbol for the rational numbers.                               |
| `\RR`       | Prints the symbol for the real numbers.                                   |
| `\ZZ`	      | Prints the symbol for the integers.                                       |
| `\Re`       | Prints "Re" (used to denote the real part of a complex number).           |
| `\Im`	      | Prints "Im" (used to denote the imaginary part of a complex number).      |
| `\charec`   |	Prints "char" (used to denote the characteristic of a ring).              |
| `\ceil{n}`  | Same functionality as `\lceil n \rceil`.                                  |
| `\floor{n}` | Same functionality as `\lfloor n \rfloor`.                                |
| `\set{n}`   | Same functionality as `\lbrace n \rbrace`.                                |
| `\paren{n}` | Same functionality as `\left( n \right)`.                                 |
| `\brac{n}`  | Same functionality as `\left[ n \right]`.                                 |
| `\angl{n}`  |	Same functionality as `\langle n \rangle`.                                |
| `\abs{n}`   |	Same functionality as `\left| n \right|`.                                 |
