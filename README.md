# Τελική αναφορά στο μάθημα: Τεχνολογία Λογισμικού

### Ονοματεπώνυμο: Δημήτριος Τριανταφύλλου
### Αριθμός Μητρώου: Π2015077


* [gh-pages (τρέχον κώδικας)](https://github.com/DimitrisTria/D3js-uk-political-donations 'Αποθετήριο κώδικα gh-pages (τρέχον κώδικας)')

### Εισαγωγή
  Η παρακάτω εργασία, D3js-uk-political-donations, δημιουργήθηκε για τα πλαίσια της εργασίας εξαμήνου του μαθήματος Τεχνολογία Λογισμικού, του Ιόνιου Πανεπιστημίου, του έκτου εξαμήνου.

### Σύνοψη
  Η εργασία βάση του [αρχικού κώδικα](https://github.com/ioniodi/D3js-uk-political-donations 'αρχικού κώδικα') που μας δώθηκε, τηρεί τις προϋποθέσεις για τα παραδοτέα του μαθήματος. Επιπλέον, την επέκτεινα με τη προσθήκη ενός νέου γραφήματος στη d3 και συγκεκριμένα ενός ραβδογράμματος που μετρά συγχνότητες εμφάνησης, για το πρώτο αρχείο δεδομένων (7500up.csv), σχετικά με τους δότες σε κάθε κατηγορία.

### Επιλογή εργαλείων
* Λογισμικό ολοκληρωμένου περιβάλλοντος προγραμματισμού: [Visual Studio Code](https://code.visualstudio.com/ 'Visual Studio Code')
* Λογισμικό επεξεργασίας εικόνων: [Paint.Net](https://www.getpaint.net/ 'Paint.Net')
* Λογισμικό για τη επεξεργασία αρχείων τύπου csv και xls: [Apache OpenOffice Calc](https://www.openoffice.org/product/calc.html 'Apache OpenOffice Calc')

### Διαδικασία ανάπτυξης
Αρχικά, μετά από την επιλογή του θέματος χρησιμοποίησα ένα περιβάλλον προγραμματισμού της επιλογής μου και συγκεκριμένα το Visual Studio Code. Ο λόγος για αυτό είναι το ότι, έχω τη δυνατότητα να τρέξω τον κώδικα εκτός διαδυκτίου και με σαφως μεγαλύτερη απόδοση και ταχύτητα τοπικά στο σύστημα που χρησιμοποιώ. Για την εκμάθηση της βιβλιοθήκης [d3](https://d3js.org/ 'd3') της javascript χρησιμοποίησα τον ακόλουθο σύνδεσμο. Επιπλέον, χρησιμοποίησα το [Github](https://github.com/ 'Github') και το [Stack Overflow](https://d3js.org/ 'Stack Overflow') για απορείες καθώς και το [W3Schools](https://www.w3schools.com/ 'W3Schools')

## Παραδοτέο 1

#### Αποθετήριο κώδικα παραδοτέου 1: https://github.com/DimitrisTria/D3js-uk-political-donations/tree/Παραδοτέο1

### Εκπλήρωση ζητούμενων πρώτου παραδοτέου

* Αλλαγή χρωμάτων στις μπάλες με τα δεδομένα, καθώς και στα αντίστοιχα 3 πεδία της ομαδοποίησης Split by party.

1. Αλλαγή χρωμμάτων των κύκλων (πριν και μετά).

![circle-colors](https://user-images.githubusercontent.com/22676085/36543380-4b4c302c-17ec-11e8-9ec7-4a9ebfe6dea5.png)

2. Αλλαγή χρωμμάτων για τα 3 πεδία της ομαδοποίησης Split by party (πριν και μετά).

![split-by-party-colors](https://user-images.githubusercontent.com/22676085/36543619-ee86c9a0-17ec-11e8-9843-47ea6a3ccc15.png)

* Ήχος κάθε φορά που ο χρήστης της εφαρμογής κάνει κλικ σε μία από τις επιλογές/κουμπιά ομαδοποίησης των δεδομένων.

Xρήση ήχου από το: https://freesound.org/people/farpro/sounds/264763/

* Το κλικ σε κάποια μπάλα ανοίγει ένα νέο παράθυρο με τα αποτελέσματα της αναζήτησης στο google για τον αντίστοιχο δωρητή.

![google-search](https://user-images.githubusercontent.com/22676085/36545535-cc9fdf20-17f1-11e8-8146-69ee8dbb3ecc.gif)

* Μεγένθυση όταν ο δείκτης βρίσκεται πάνω από τις λέξεις του κειμένου.

![zooming](https://user-images.githubusercontent.com/22676085/36545107-d9c56b80-17f0-11e8-9ba8-e6b023ca151e.gif)

* Όταν το ποντίκι βρίσκεται μέσα στον κύκλο κάποιου δωρητή ακούγεται η ονομασία και το ποσό της δωρεάς του δωρητή, με τη χρήση της βιβλιοθήκης responsivevoice στη javscipt.

* Νέο κουμπί για νέα ομαδοποίηση δεδομένων: Split by amount of donation.

![split-by-amount-of-donation](https://user-images.githubusercontent.com/22676085/36545828-7e91eed0-17f2-11e8-9ad4-85ce54efb298.png)

## Παραδοτέο 2

### Ενδεικτικές οθόνες


### Πηγές πολυμεσικού υλικού που χρησιμοποιήθηκε στην εργασία
* Ήχος διαφορετικής οπτικοποίησης: [Hover 2](https://freesound.org/people/plasterbrain/sounds/237421/ 'Hover 2')
* Ήχος διαφορετικής ομαδοποίησης: [guiclick2.ogg](https://freesound.org/people/farpro/sounds/264763/ 'guiclick2.ogg')
