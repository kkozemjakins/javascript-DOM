# DOM Atomic 02: Hide Many Elements

## Questions

---

> How did you go about selecting the DOM elements to hide? Describe the "contract" for that function.

Nu, vajag izmantot. getElementsByClassName (). Laukā () norādiet, kuru klasi vēlaties apkopot. Tā tiks atgriezta kolekcija, un jums būs jāpārmeklē kolekcija, lai paslēptu visus tajā esošos elementus.

---

> Describe how you were able to hide each element. Were you able to do it as one operation, or did you use a loop of some kind? Describe the "contracts" that were utilized to accomplish your goal.

A loop was used to move through the collected elements.  It was necessary to indicate the size of the loop and what was to be done to each attribute of the class.

---