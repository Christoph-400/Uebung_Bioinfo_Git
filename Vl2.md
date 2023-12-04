# Methoden bei Klassen erstellen und aufrufen bei Python

In unserer Katzen-Klasse haben wir bisher nur Eigenschaften und nur die Methode __init__().

Bei der Festlegung, welche Methoden für unsere BauplanKatzenKlasse hatten wir notiert:

Eigenschaften:

    Farbe
    Alter
    Rufname

Methoden:

    miauen
    schlafen
    fressen
    schmusen

Also integrieren wir als Methode „miauen“. Eigentlich müssten wir für die Lautsprache von Katzen 10 weitere unterschiedliche Lautarten als Methode integrieren (man sollte seiner Katze mal genauer zuhören – im Gegensatz zum Hund, der nur 10 kann, kann die Katze bis 100 Einzellaute). Aber wir wollen nicht übertreiben. Unsere digitale Katze darf nur „miauen“ als Methode.

Unser bisheriger Code:


    class BauplanKatzenKlasse():
    """ Klasse für das Erstellen von Katzen """

    def __init__(self, rufname, farbe, alter):
        self.rufname = rufname
        self.farbe   = farbe
        self.alter   = alter
    
    katze_sammy = BauplanKatzenKlasse("Sammy", "orange", 3)

