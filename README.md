### House_price_analysis-SCB ###

## Mål ##
Projektets mål är att analysera hur bostadspriser i Sverige har utvecklats över tid och hur priserna skiljer sig mellan olika regioner.
Projektet är kopplat till AI-utvecklarrollen eftersom det visar hur man samlar in, bearbetar, analyserar och visualiserar data innan det används inom AI och machine learning.

## Metod ##
Projektet är utvecklat i Python och Jupyter Notebook.
Jag använder:
SCB API – hämtar bostadsdata
Pandas – bearbetar och analyserar data
NumPy – numeriska beräkningar
Matplotlib – visualisering
Requests – API-anrop
Funktioner – återanvändbar kod
Klasser och arv – objektorienterad programmering
Try/except – felhantering
Data analyseras både över tid och mellan olika svenska regioner.

## Resultat ##
Projektet hämtade 353 tidsobservationer och data från 25 regioner.
Analysen visar att bostadspriserna har ökat kraftigt över den analyserade perioden. Den nationella prisutvecklingen ökade med cirka 443 % mellan den första och sista observationen.
Regionalt finns också tydliga skillnader. Exempelvis hade Gotlands län en förändring på cirka 548,97 %.
Resultaten visas även med diagram.

## Analys ##
Resultaten visar att svenska bostadpriser har ökat kraftigt samtidigt att bostadspriserna inte utvecklas lika i alla delar av Sverige.
För en AI-utvecklare visar projektet vikten av att kunna hämta och strukturera data innan den används i AI- eller machine-learning-modeller. Datakvalitet och korrekt analys är viktiga för att få tillförlitliga resultat.
En viktig lärdom jag tog från det här projekt är att datakvalitet är en central del av AI-utveckling. Om data är felaktig, ofullständig eller felaktigt strukturerad kan även resultaten från en modell bli missvisande och kan skaffa massa problem.
Reflektion
Det som gick bra var att hämta data direkt från SCB och analysera den med Python.
Den interaktiva menyn gjorde dessutom projektet mer användarvänligt eftersom användaren kan välja vilken region som ska analyseras och jätte nojd med den.
Det svåraste var att förstå SCB API och strukturera JSON-data.
Det var även utmanande att förstå hur dimensioner, variabelkoder och värden hänger ihop.
Under utvecklingen uppstod även olika programmeringsfel, exempelvis NameError, KeyError, TypeError och AttributeError. Genom att felsöka problemen och svar från chatgpt blev det tydligare hur Python hanterar variabler, dictionaries, funktioner och objekt.
En annan utmaning var att organisera projektet så att koden blev både funktionell och lätt att förstå.
Projektet kan i framtiden utvecklas med machine learning för prisprognoser, fler ekonomiska variabler och en interaktiv webbapplikation. Google Cloud Professional Data Engineer passar för den utökade datahanteringen, medan Azure AI Engineer är relevant för AI och machine learning. 

## GitHub ##
Repository:
https://github.com/musishxo/house_price_analysis-SCB

## Installation ##
Installera Python och biblioteken:
pip install pandas numpy matplotlib requests jupyter
Starta sedan Jupyter Notebook rekomenderar google colab eller vscode.
Öppna House_price_analysis_SCB.ipynb och kör cellerna uppifrån och ner.

