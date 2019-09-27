# Scores

Schrijf een programma dat scores van 0 t/m 10 vanuit de terminal inleest en een barchart van `#`-jes uitprint.

## Gebruik

    $ python scores.py
    Vul een score in: 5
    Vul een score in: 3
    Vul een score in: 7
    Vul een score in: -1
      #
      #
    # #
    # #
    ###
    ###
    ###

    $ python scores.py
    Vul een score in: 1
    Vul een score in: 20
    Vul een score in: 2
    Vul een score in: 3
    Vul een score in: -1
      #
     ##
    ###

## Specificatie

* Schrijf een programma `scores.py` dat scores (integers) inleest totdat er een negatieve score wordt ingevuld. Daarna print het programma een verticale barchart.
* Negeer alle scores hoger dan 10 en vraag vervolgens de gebruiker opnieuw om input.
* Je mag aannemen dat de gebruiker altijd een integer invult.

## Tips

* Python is handig met strings, zo kun je strings vermenigvuldigen: `"a" * 3`
* Maak gebruik van een lijst om de input te verzamelen.
* Gebruik de `input` functie om input van de gebruiker te winnen. Dit kan bijvoorbeeld zo: `name = input("What's your name?")`
* Je kan strings naar integers veranderen door de `int()` functie. Bijvoorbeeld zo: `int("517")`
* Python scheidt print output normaal gesproken automatisch met een spatie. Wil je dat niet gebruik dan het extra `sep` argument als volgt: `print("foo", "bar", sep="")`.
* Wil je niet dat er standaard een newline (`\n`) wordt geprint? Maak dan gebruik van het optionele `end` argument als volgt: `print("foo", end="")`

## Testen

	check50 minprog/cs50x/2019/scores/more
