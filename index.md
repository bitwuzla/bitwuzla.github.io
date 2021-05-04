---
layout: default
---

{%- assign gh = site.github.public_repositories |where: "name", "bitwuzla" |first -%}

# About Bitwuzla

Bitwuzla is a Satisfiability Modulo Theories (SMT) solver for the theories of
fixed-size bit-vectors, floating-point arithmetic, arrays and uninterpreted
functions and their combinations. Its name is derived from an Austrian dialect
expression that can be translated as "someone who tinkers with bits".

### Pronunciation of Bitwuzla

- **Bit**...
- '**w**' as 'v' in 'vector',
- '**u**' as 'oo' in 'good' (but short),
- '**z**' as 'ts' in 'tsunami',
- '**l**' just an 'l',
- '**a**' as 'u' in 'cut'

### Citing Bitwuzla

{% include_relative bibtex-include.md %}

# News

- Bitwuzla is now available on [GitHub]({{ gh.html_url }})
- Bitwuzla [won 17 out of 26](smt-comp.html#smtcomp2020) (participated) divisions at [SMT-COMP 2020](http://www.smt-comp.org/2020)
- Bitwuzla participating at [SMT-COMP 2020](https://smt-comp.github.io/2020) ([submitted binary](https://www.starexec.org/starexec/secure/details/solver.jsp?id=28818))


