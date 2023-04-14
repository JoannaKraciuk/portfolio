# **Testy eksploracyjne aplikacji**  🚀
  

💻 **Link do testowanej aplikacji: [skleptest.pl](https://skleptest.pl/)**

 ## 📌***Opis***
    
Aplikacja jest aplikacją testową, stworzoną w celach ćwiczenia umiejętności testowania oprogramowania. Jest również modelem aplikacji sklepu internetowego, która służy do zakupu odzieży, obuwia oraz dodatków.


## 📌 ***Funkcjonalności***

Funkcjonalności w aplikacji, to:

-   rejestracja konta – zarejestrowanie nowego użytkownika,
    
-   logowanie – zalogowanie już utworzonego użytkownika,
    
-   przypomnienie hasła – resetowania hasła do aplikacji,
    
-   zapamiętanie w systemie danych logowania – zapisanie danych logowania, w celu ponownego wykorzystania,
    
-   subskrypcja – zapisanie do newslettera,
    
-   wyszukiwanie – wyszukiwanie produktów po nazwie,
    
-   wyszukiwanie po kategorii produktu – wyszukiwanie produktów z listy rozwijalnych kategorii,
    
-   wyszukiwanie najbardziej popularnych produktów – przekierowanie na podstronę z najbardziej popularnymi produktami,
    
-   powrót do strony głównej poprzez logo strony – przekierowanie na stronę główną poprzez użycie głównego logo strony,
    
-   dodawanie produktu do koszyka – dodanie produktu do koszyka przy użyciu buttona pod zdjęciem produktu,
    
-   wyświetlanie koszyka – wyświetlenie zawartości koszyka przy użyciu buttona pod zdjęciem produktu,
    
-   zmiana ilości produktów na stronie produktu – zmiana ilości produktów, które zostaną dodane do koszyka,
    
-   zmiana ilości produktów w koszyku – zmiana ilości produktów znajdujących się w koszyku,
    
-   dodanie kuponu w koszyku – wpisanie numeru oraz zatwierdzenie kuponu promocyjnego w koszyku,
    
-   obliczanie opłaty za dostawę – wpisanie kraju oraz kodu miasta w celu obliczenia opłaty za dostawę,
    
-   aktualizacja koszyka – aktualizacja koszyka po uprzedniej zmianie ilości produktów w koszyku lub dodania kuponu,
    
-   tagi – przekierowanie do artykułów na blogu zawierających tagi,
    
-   buttony "Shop Now" , "Buy now" - możliwość natychmiastowego przekierowania do strony produktu w celu dokonania zakupu,
    
-   koszyk – zawiera produkty przeznaczone do zakupu,
    
-   przekierowanie do podsumowania zamówienia,
    
-   dane faktury – wprowadzanie danych w celu wystawienia faktury
    
-   zmiana adresu dostawy – możliwość podania innego adresu dostawy,
    
-   kontakt – możliwość kontaktu z obsługą sklepu za pomocą maila,
    
-   blog – zawiera artykuły o tematyce związanej z szeroko pojętą branżą modową,
    
-   wyszukiwanie na blogu – możliwość hasłowego wyszukiwania informacji na blogu.
    
  
## 📌 ***Ocena interfejsu***

Interfejs aplikacji jest dosyć przejrzysty i czytelny. Łatwo znaleźć potrzebne funkcjonalności, jak panel wyszukiwania czy kategorie produktów. Logo aplikacji prawidłowo umieszczone w lewym, górnym rogu, niestety na podstronach zmienia swoje położenie.

Pod zdjęciem głównym umieszczony został panel z informacjami o dostawie, kontakcie i lokalizacji, który powinien znajdować się na dole strony. Kolorystycznie elementy strony współgrają ze sobą, a ciemne tło w połączeniu ze zdjęciem głównym daje poczucie ciepła i miękkości. Zmian można by dokonać ujednolicając buttony pod zdjęciami produktów "Add to cart", ponieważ występują one w rożnych kolorach, nie zawsze przyjaznych dla oka. Nie wszystkie zdjęcia na stronie głównej wyświetlają się prawidłowo, co stwarza wrażenie strony w trakcie tworzenia.

## 📌***Ocena intuicyjności***

Aplikacja jest intuicyjna, logo, panel wyszukiwania, panel logowania oraz koszyk, umieszczone są w odpowiednich miejscach.


## 📌***Błędy w aplikacji***

- **STRONA GŁÓWNA:**
    

	❌   Nieprawidłowo wyświetlane zdjęcia.
	![tekst alternatywny](https://github.com/JoannaKraciuk/portfolio/blob/93b9fab88aad1e22104d4a230b62b1fc325474c7/Images/1.png)
    
	❌   Nie można wejść w opis produktu, po kliknięciu w jego zdjęcie.
    
	-   Wszystkie buttony "Shop now" na stronie głównej przekierowują do nieistniejącej strony (status code 404).
	![tekst alternatywny](https://github.com/JoannaKraciuk/portfolio/blob/0737f395f90f9794cad9e54a18b3deb55bf2ccb4/Images/2.png)
	![tekst alternatywny](https://github.com/JoannaKraciuk/portfolio/blob/0737f395f90f9794cad9e54a18b3deb55bf2ccb4/Images/3.png)

    
	-   Button "Learn more" przekierowuje do strony z formularzem kontaktowym.
    
	-   Po kliknięciu w strzałki, które powinny przewijać produkty, przekierowują na górę strony głównej.
    
	-   Po kliknięciu pod zdjęciem produktu "View cart" nie zostaje wykonana żadna akcja.
	![tekst alternatywny](https://github.com/JoannaKraciuk/portfolio/blob/0737f395f90f9794cad9e54a18b3deb55bf2ccb4/Images/4.png)
    
	-   W opis produktu można wejść jedynie poprzez umieszczenie produktu w koszyku, a następnie z tego miejsca przejście do karty produktu.
    
	-   Po dodaniu produktów do koszyka, cena w koszyku na stronie głównej nie zmienia się; dopiero po kliknięciu <My Cart> zostaje zaktualizowana.
    
	-   Cena w koszyku wyświetlana jest z symbolem „zł” na początku oraz z dwoma miejscami po przecinku, nawet jeśli są to zera.
	![tekst alternatywny](https://github.com/JoannaKraciuk/portfolio/blob/0737f395f90f9794cad9e54a18b3deb55bf2ccb4/Images/5.png)
    
	-   Można subskrybować newsletter, w polu e-mail wpisując dowolny znak.
   
	
- **STRONA LOGOWANIA I REJESTRACJI:**
	
	-  Możliwość wielokrotnej rejestracji na tego samego maila.
	-  Możliwość zapisania się do newslettera bez poprawnego maila.
	![tekst alternatywny](https://github.com/JoannaKraciuk/portfolio/blob/0737f395f90f9794cad9e54a18b3deb55bf2ccb4/Images/6.png)
	
- **MOST WANTED:**
	
	- Logo sklepu jest przesunięte w prawo względem pozycji ze strony głównej.
	- Po wyswietleniu produktu i powiększeniu jego zdjęcia, kliknięcie w lupkę powiększającą przekierowuje do koszyka.
	![tekst alternatywny](https://github.com/JoannaKraciuk/portfolio/blob/0737f395f90f9794cad9e54a18b3deb55bf2ccb4/Images/7.png)
	- Po wyświetleniu zdjęcia, nie działa powiększenie, jak również zamknięcie zdjęcia poprzez button krzyżyka.
	- Będąc na stronie przediotów MOST WANTED, można je dodać do koszyka jedynie w ilości 99 lub 100 sztuk, po uprzednim usunięciu minusa przed ilością produktów.
	- Kolejne dodanie 99 lub 100 sztuk produktu do koszyka, powoduje nieprawidłowe zwiększenie jego ilości.
	- Na stronie nie dział sortowanie według ceny (low-high oraz high-low).
	
- **CATEGORIES:**
	
	- Literówka w panelu głównym "CATERGRIES" zamiast "CATEGORIES".
	![tekst alternatywny](https://github.com/JoannaKraciuk/portfolio/blob/0737f395f90f9794cad9e54a18b3deb55bf2ccb4/Images/8.png)
	- W rozwijalnym menu, po wyświetleniu wszystkich produktów (ALL) większość zdjęć kategorii, nie jest widoczna.
	- W kategorii "Shoes" wyświetlają się również bluzki.
	
- **ABOUT US:**
	
	- Nie ma możliwości wysłania maila po wpisaniu prawidłowych danych.
	![tekst alternatywny](https://github.com/JoannaKraciuk/portfolio/blob/0737f395f90f9794cad9e54a18b3deb55bf2ccb4/Images/9.png)

- **KOSZYK:**
    
	 -   Nominał „zł” przy cenie produktu, jest umieszczony w prawym górnym rogu, zamiast na dole za ceną.
	![tekst alternatywny](https://github.com/JoannaKraciuk/portfolio/blob/0737f395f90f9794cad9e54a18b3deb55bf2ccb4/Images/10.png)
        
   	 -   Nie działa button „x” przy produkcie; nie można usunąć produktu z koszyka, jedynie za pomocą zmniejszenia jego ilości do 0, a następnie aktualizacji koszyka.
        
   	 -   Znak „x” jest przesunięty w dół, względem pomarańczowego tła.
        
   	 -   Po zmianie ilości produktu w koszyku (jednego lub wielu) i kliknięciu <UPDATE CART>, koszyk zostaje zaktualizowany, ale znikają „-” i „+”, które służyły do zmiany ilości produktów.
        
	 -  Możliwość wpisania ujemnej liczny produktów (problem z walidacją pola).
        
	 -  Wpisując dwa minusy w liczbie produktów, usuwamy produkt z koszyka.
        
   	 -  Po aktualizacja produktów w koszyku do liczby 4-cyfrowej, wartość ta, nie jest w całości wyświetlana w polu "Quantity".
        
   	 -  Na stronie głównej, cena w koszyku zostaje aktualizowana dopiero po kliknięciu w prawym górnym rogu "My Cart".
        
	 -  Zaktualizowana cena wyświetlana jest z dwoma miejscami po przecinku, nawet jeśli są to zera.
	
	
- **BLOG:**
	- Na stronie widnieją trzy pola wyszukiwania:
	![tekst alternatywny](https://github.com/JoannaKraciuk/portfolio/blob/0737f395f90f9794cad9e54a18b3deb55bf2ccb4/Images/11.png)
	
- **CHECKOUT:**
	
	- Nie ma możliwości dodania alternatywnego adresu dostawy po zaznaczeniu odpowiedniej opcji.
	![tekst alternatywny](https://github.com/JoannaKraciuk/portfolio/blob/0737f395f90f9794cad9e54a18b3deb55bf2ccb4/Images/12.png)

