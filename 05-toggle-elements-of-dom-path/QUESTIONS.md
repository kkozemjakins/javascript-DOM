# DOM Atomic 05: Toggle Elements of DOM Path

## Questions

---

> Describe the contract you used for finding the movies to toggle in the DOM. How is this function different from other functions that find elements in the DOM?

Šajā gadījumā, tā vietā, ko izmantoju, es izmantoju. getElementsByClassName (), es izmantoju. querySelectorAll ().. getElementsByClassName () pieņem tikai vienu argumentu, tāpēc nevar pārvietoties uz koku. Tomēr. querySelectorAll () ļauj iegūt konkrētu informāciju. Šajā gadījumā, kā argumentu, ko esam ievietojuši “ul.second _ five Li”, viņš norāda, ka datoram ir jāatrod visi tagi ar klasi “ul”, tad no šīm atzīmēm ņemsim tikai tos, kas atzīmēti “second_five”, atstarpe ir simbolisks pēctecis, kas norāda, ka jāņem tikai tie elementi ar pirmajiem diviem atribūtiem, kuri ir atzīmēti kā saraksta elementi.

---