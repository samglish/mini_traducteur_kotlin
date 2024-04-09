# mini traducteur en kotlin
### Traduction par dictionnaire
Nous avons deux dictionnaires, l'un en francais et l'autre en fulbe representant la
traduction du prémier en gardant la même position.

val motsFR = array("semence","Abraham"............."bonjour")

val motsFB = aOfrrayOf("aawdiiri","Ibrahim"............"awali djam")

En gros nous avons utilisé une méthode de traduction littérale (une traduction
qui respecte la morphologie et la syntaxe du texte original mot par mot,
syntagme par syntagme ou phrase par phrase)
un mot ne figurant pas dans le dictionnaire n’est donc pas traduit et sera donc
affiché tel qu’il est.
