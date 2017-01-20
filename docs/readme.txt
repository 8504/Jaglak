Pierwsze co robimy po zaladowaniu juz projektu w Visual Studio to Rebuild, 
jesli sa problemy (errors list) to zachecam do przeczytania 'Troubleshootings'

Przydatne linki:
https://www.asp.net/web-api/overview/getting-started-with-aspnet-web-api/tutorial-your-first-web-api - tworzenie Api w asp.net
https://developer.xamarin.com/guides/xamarin-forms/web-services/authentication/rest/ - xamarin i autentykacja przez Api 
https://developer.xamarin.com/guides/cross-platform/Application_Fundamentals/Web_Services/ - tworzenie Api w asp.net WCF (raczej o to nam chodzi)

IIS Express (lokalnie):

Oczywiscie zeby testowac tworzone Api lokalnie zanim wrzuci sie na serwer developerski trzeba  by ja postawic na lokalnym IIS, jesli nie instalowaliscie
a macie windows 10 i zainstalowane Visual Studio to posiadacie tez IIS 10 ale bez panelu do zarzadzania wiec trzeba wejsc (start) potem 
"Programy i funkcje" tam po lewej "W³¹cz lub wy³¹cz funkcje systemu windows" tam zaznaczamy Internetowe uslugi informacyjne > Konsola zarzadzania uslugami IIS,
mysle ze trzeba tam tez sie przyjrzec funkcja dla .net . Sa tam funkcje zwiazane z WCF.

Pozniej do panelu zarzadzania IIS'em mozna wejsc przez "start" > Menadzer Internetowcyh us³ug informacyjnych 
Important: Zresetujcie po instalacji komputer bo czasami sa problemy przez brak restartu nawet jesli o niego nie wola.
