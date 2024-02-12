Scopo dell’applicazione è creare una pagina web che mostri il valore di un numero random compreso tra 1 e 6 (come un dado )<br/>
Come fare?<br/>
Creare il progetto con lo Spring Initializr, aggiungendo le dipendenze Spring Web e Thymeleaf<br/>
Aggiungere una classe Controller che risponde alla root dell’applicazione (“/”), con un metodo annotato @GetMapping nel quale calcolate il numero random in Java e lo passate come attributo del Model.<br/>
Nella cartella resources/templates aggiungete il file .html con il template nel quale in un opportuno tag html mostrate il valore del numero random passato come attributo<br/>
Il metodo del controller deve restituire il nome del template<br/>
# BONUS:
passate come parametro della request il tipo di dado da tirare, cioè il valore massimo del numero random che viene generato (Attenzione che se aggiungete ai parametri del metodo un valore annotato come @RequestMapping il metodo si aspetta sempre che ci sia quel parametro nella query string della request)
