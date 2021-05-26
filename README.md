# ModularizedMonolith
Materials from my presentation on modularizing a monolith

#Abstract

Ile razy słyszeliście że 'nie mikrosewisy tylko modularny monolit'. i nawet się z tym zgadzasz. Ale po konferencji siadasz do kodu i... Jak to właściwie zrobić?

Tytuł jak wzięty z konferencji z poprzedniej epoki, prawda? Teraz implementuje się Serverless. a w starszych systemach - Mikroserwisy. A może jest inaczej - może to tytuł z następnej epoki gdy historia zatoczy koło? A może jednak temat jest bardzo aktualny, bo wszystie te trzy architektury mają swoje zastosowanie. Szczególnie dużo o modularnym monolicie i wyznaczaniu granic mówi się w kontekście mikroserwisów. 

Prezentacja to Case Study na bazie produktu który zaczął się jako monolit i skończył jako modularny monolit. Pokazuje proces modularyzacji kodu. Zaczynając od zwykłego przesuwania klas między paczkami, przez ograniczanie dostępu po definiowanie wspólnych modeli oraz pokazanie jak korzystam z narzędzia do wymuszania tych reguł - ArchUnit. Bo przecież  tak nie chcemy tego pilnować ręcznie na Code Review. 

Prezentacja zakłada że granice modułów są już wymyślone. Skupimy się na tym jak te wyznaczone granice zaimplementować i dopilnować. 
