Za **Start.java**:

1. **Smanjena složenost koda:** Izostavljene su nepotrebne promenljive i skraćene definicije.
2. **Jednostavnija logika za izlazak:** Korišćen je `equalsIgnoreCase` umesto `equals` kako bi se omogućilo korisniku da unese "Izlaz" ili "izlaz" i izađe iz programa.
3. **Optimizovano korišćenje metoda:** Koristi se `Calculator.evaluateExpression` umesto `Calculator.Run` za izračunavanje rezultata izraza.
4. **Kraći izraz za ispis rezultata:** Korišćena je `System.out.println` za ispisivanje rezultata izračunavanja izraza.
5. **Zatvaranje Scanner objekta:** Dodata je linija koda `scanner.close()` kako bi se zatvorio Scanner objekat kada korisnik izađe iz programa.

Za **Calculator.java**:

1. **Jednostavnija logika za izlazak:** Izostavljena je provera izraza "exit" unutar metode `evaluateExpression`.
2. **Optimizovano korišćenje metoda:** Korišćenje `try-catch` bloka za obradu grešaka pri evaluaciji izraza umesto provere unosa unutar metode.
3. **Izostavljanje nepotrebnih linija koda:** Izostavljena je nepotrebna linija koda za proveru izraza "exit" unutar metode `evaluate`.
4. **Kraći izraz za obradu grešaka:** Korišćena je jedna linija za povrat "ERROR" u slučaju greške umesto dve linije.

Ove izmene omogućavaju kraći, čistiji i efikasniji kod za obe klase.
