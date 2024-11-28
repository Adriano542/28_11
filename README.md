DOM (Document Object Model) - reprezentacja dokumentu HTML w przeglądarce
elementy strony (tag, atrybuty) są węzłami, które mogą być:
1. Pobierane
2. Modyfikowane
3. usunięte
4. tworzone

Strukura DOM przypomina drzewo, na szczycie którego jest obiekt: document

DOM nie jest częścią JS, ale JS umożliwia prace z DOM, jest interfejsem sposobem na prace ze stroną internetową, który możemy obslługiwać za pomocą JS


I. POBIERANIE ELEMENTÓW ZE STRONY INTERNETOWEJ 
Aby w przyszłości zmodyfikować element, najpierw należy go pobrać
1. Pobieranie właściwości obiektu Document
   Przykładowe właściwości
   document - całą strona
   document.documentElement - odnosi się do HTML pierwszego znacznika
   document.body
   document.body.h1 - z h1 nie zadziała bo ten element musimy sobie wyszukać
   document.images - zbiera wszystkie obrazki

   HTMLCollection - przypomina tablicę, jest to obiekt tablicoodporny



   
II. MODYFIKOWANIE ELEMENTÓW NA STRONIE INTERNETOWEJ
Mam dużo metod i właściwości, które umożliwiają mi modyfikację tego co widzę na stronie internetowej

III. ZDARZENIA AKCJE NASŁUCHIWANIE
Możemy nasłuchiwać, wyczekiwać na jakieś zdarzenie, czyli jak wystąpi zdarzenie to zaprogramujemy jakąś akcję, np. na click 

IV. TWORZENIE I DODAWANIE ELEMENTÓW
Na początku muszę coś stworzyć aby potem zmodyfikować
