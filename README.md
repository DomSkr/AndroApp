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
