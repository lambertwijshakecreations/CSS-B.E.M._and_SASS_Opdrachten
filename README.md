# CSS-B.E.M._and_SASS_Opdrachten

Dit was een eindopdracht voor Advanced CSS. waarbij ik 3 opdrachten moest maken waarbij ik Block Element Modifier en SASS moest gebruiken. 
Dit was de opdracht:

Eindopdracht: Advanced CSS
Hallo daar CSS-guru-in-wording 

Het is tijd om je nieuwe CSS skills tot een nieuw level te brengen met deze CSS Challenges. Wanneer je aan de slag gaat als developer, krijg je vaak een design van een UX-afdeling dat jij met jouw expertise om gaat zetten in code. Dat is precies wat we vandaag gaan doen: je krijgt een design dat je om gaat zetten in code. Dit betekent ook dat er niet 1 gouden manier is om een design te bouwen. Met andere woorden: er leiden meerdere wegen naar Rome. We laten de besluiten over code graag over aan jouw expertise. Maak elk van de designs met HTML/CSS. Je hebt geen JavaScript nodig.

Deze eindopdracht bestaat uit 3 losse CSS uitdagingen, die steeds een een stapje lastiger worden.  

Je mag bij deze opdracht gebruik maken van ons Slack kanaal om vragen te stellen aan je mede-cursisten.

Algemene requirements
Maak voor elk onderdeel gebruik van de SCSS principes die je hebt geleerd.

Werk alle onderstaande onderdelen uit in één en dezelfde HTML pagina.
Maak overal gebruik van SCSS nesting
Maak overal gebruik van SCSS variabelen
Maak overal gebruik van SCSS partial imports om je SCSS te scheiden
De site mag niet horizontaal scrollen, tenzij je window heel smal is (minder dan 400px)
Bonus:

Maak gebruik van mixins
Deel 1 - Testimonial maken
Maak het volgende design na in HTML/CSS:

Design


Specificaties
Footer testimonial - paars/blauw: #686de0
Achtergrond pagina - grijs: #c3cfe2
Achtergrondkleur tekst - wit: #fff
Je mag een random portretfoto gebruiken, van jezelf of van een stock-foto.
Deel 2 - Portfolio Grid
In dit deel gaan we een portfolio grid maken. We zetten er nu een plaatje in, maar je kan er van alles inzetten. Je kunt de foto van onze collega Niels bijvoorbeeld vervangen door een testimonial kaartje die je in level 1 hebt gemaakt.

Design & interactie
Bekijk onderstaande video.


Specificaties
Achtergrond pagina grijs: #c3cfe2
Je grid is mobile responsive voor 3 schermen: desktop (3 kolommen), tablet (2 kolommen), en mobiel (1 kolom)
Er komt een button tevoorschijn on hover. De foto verdwijnt smoothly.
Je hebt hier geen JavaScript voor nodig. Denk aan de pseudo classes :hover.

Het over "elkaar heen plaatsen" van elementen noemen we ook wel "stacken". Je kan dit doen met het "position" CSS attribuut.Lees meer over hoe je elementen stackt.

Deel 3 - Social Media Buttons
Zelfgemaakte social media buttons zijn altijd leuk om te hebben. Deze zijn heel fancy, er komt zelfs een kleine animatie bij kijken.

Dit ga je namaken:


Specificaties
Design & interactie

Dat groene aan de rechterkant is een bureaublad, je ziet dat de knoppen tegen de rand van de browser aan staan.

Kleuren

.social-media.blog {
        background-color: #e17b77;
}

.social-media.facebook {
        background-color: #3b5998;
}

.social-media.twitter {
        background-color: #00aced;
}

.social-media.github {
        background-color: #333;
}

.social-media.linkedin {
        background-color: #007bb6;
}
Iconen

Optie 1: Je kunt de icons opzoeken en ze als image in je CSS zetten. Dat is correct en prima.

Optie 2: Next level is iconen toevoegen met ::before met bijvoorbeeld: font awesome:

Font Awesome

Font Awesome

Gebruik in dat geval de volgende code:

.fa-laptop-code::before {
    content: "\f5fc";
}
.fa-twitter::before {
    content: "\f099";
}
.fa-linkedin-in::before {
    content: "\f0e1";
}
.fa-facebook-f::before {
    content: "\f39e";
}
.fa-github::before {
    content: "\f09b";
}
