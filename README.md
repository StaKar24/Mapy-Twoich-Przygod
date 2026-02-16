MTP to aplikacja strony internetowej do postowania i przeglądania map wycieczek po świecie napisana przy użyciu leaflet.js, express.js i react (aktualnie używa bazy danych sqlite). 
Strona używa openrouteservice.org do renderowania tras na mapie.
http://16.16.182.120/

Stwożyłem ją z myślą o wycieczkach autostopowych. Chciałem mieć miejsce by zapisywać i dzielić się w sposób graficzny moimi podróżami. 
Pomysł się rozrusł i teraz strona może służyć do zapisywania najróżniejszych wycieczek używających różnych środków transportu.

Z powodu deadline-u stdiów i pierwotnego pomysłu na projekt (mój osobisty blog), strona działa w następujący sposób.
Są na rodzaje użytkowników: admin i user.
  Niezalogowani użytkownicy mogą tylko przeglądać mapy i opisy segmentów 
  Users mogą dodać usgestie dla twórcy podrózy jak i dodawać komentarze pod danym segmentem podróży
  Admin może dodawać, edytować i usuwać SWOJE podróże (jak i przeglądać sugestie on użytkowników)
Z powodów limitacji wybranego silnika baz danych i podstawowego serwisu routingowego tylko wybrani użytkownicy mogą twożyć trasy.

Z tego powodu jest to narazie wersja demo 1.0 (data 16.2026)

Plan na przyszłość:
  Przejść na MySQL lub PostgreSQL by weliminować problem z dapisywaniem danych przez wielu użytkowników jednocześnie
  Umożliwnie dodawania zdjęć na mapie do segmentów 
  Umożliwienie wszystkim zainteresowanym użtykownikom by mogli twożyć swoje mapy
  Dodanie wyszukiwarki twórców map lub danej podróży (aktualnie jest tylko drop down menu do wyboru danej trasy
  Opcje językowe (aktualnie aplikacja jest napisana tylko po polsku)

