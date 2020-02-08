# AndroApp

notatka

//        biblioteka retrofit zamiana json > obiekt
//        plugin json to kotlin data class do android studio np https://www.json2kotlin.com/
//        wątki rxjava -> chaining
//        zapytanie sieciowe - trzeba dodać zależności do projektu/
//        napisać implementację jako intrfejs API
//        podać url i co to będzie zwracać
//        sukces i kiedy porażka - obsł zdarzeń

//        Kotlin view Model Overview (należy do androida) cykl życia widoku

live data 
d = mutableLiveData<String>(value "")
def getMoreData(){
  d.value = d.value + "LIVE DATA"
}

wyłapywanie zmian - > np kolejnych wciśniętych klawiszy

pole tekstowe musi obserwować zmiany: i aktualizować się Data Binding Library

dataBinding {
  enabled = true
  }


flutter library (like react)

nowy proj
minSdkVersion 26
obfuskowane - jak przy minimalizacji 
gradlew
androidx = 

ctrl + shift + t
testy jednostkowe
@test
fun test1{
Assert.assertTrue(true)
}

fun 'Komentarz ktory wyswietli sie w logach'(){}

class Calc{
fun addTwo(first: Int; second: Int){
return first.plus(second)
}

class mainTest{
//given
//when
//then
}

sprawdz czy sa biblioteki

cykl zycia aktywnosci
enter view -> akcja -> Text View
onclick show new page

uprawnienia dla aplikacji do korzystania z internetu
w android manifest
wątki, coruntime
