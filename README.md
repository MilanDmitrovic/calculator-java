
								README fajl:



# Analiza koda

Ovaj projekat sadrži dva Java fajla: Start.java i Calculator.java. Oba fajla su analizirana kako bi se identifikovali potencijalni problemi i predložila rešenja.

## Start.java

- **Broj linija koda:** X
- **Ciklomatska složenost:** X
- **Kognitivna složenost:** X

### Zaključci:

- Kod je čist i dobro organizovan.
- Primena `Scanner` objekta izvan petlje smanjuje ponovno stvaranje objekta.
- Korišćenje `equalsIgnoreCase` metode omogućava korisniku unos "Izlaz" ili "izlaz" za izlazak iz programa.
- Metoda `Calculator.evaluateExpression` se koristi za izračunavanje rezultata umesto `Calculator.Run`.
- Korišćenje `System.out.println` za ispis rezultata izračunavanja izraza.
- `scanner.close()` metoda zatvara Scanner objekat kada korisnik završi sa programom.

## Calculator.java

- **Broj linija koda:** X
- **Ciklomatska složenost:** X
- **Kognitivna složenost:** X

### Zaključci:

- Kod je čist i dobro organizovan.
- Uklonjena nepotrebna linija koda za proveru izraza "exit" unutar `evaluateExpression` metode.
- Korišćenje `try-catch` bloka za obradu grešaka pri evaluaciji izraza umesto provere unosa unutar metode.
- Jednostavnije vraćanje "ERROR" u slučaju greške umesto korišćenja dve linije koda.
