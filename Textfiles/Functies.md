Functies:
def homepage():
Deze functie rendered de homepage

def quiz():
Methoden: get en post
Deze functie rendered de quiz, hierna zal de rest van de quiz via javascript uitgevoerd worden. Nadat de quiz af is zal deze functie de database updaten met de behaalde score (totaal en per categorie), en mits de gebruiker in de top 10 beland ook met een username. Daarna wordt de leaderboard.html geladen.

def check():
Methoden: get
Deze functie checkt of de score van de gebruiker genoeg is om in de top 10 te komen, zo ja returned het True in met jsonify, in dat geval zal de gebruiker via javascript gevraagd worden een username op te geven.

def leaderboard():
Deze functie haalt de top 10 op plus de gegevens van de gebruiker om deze door te sturen naar de


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwODc5NTc5MTgsLTE1MzI0MjAwNjksLT
E5NTUzMTA1MTVdfQ==
-->