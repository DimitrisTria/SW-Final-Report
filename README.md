# Τίτλος εργασίας: Οπτικοποίηση δεδομένων χορηγιών (UK)

### Ονοματεπώνυμο: Δημήτριος Τριανταφύλλου
### Αριθμός Μητρώου: Π2015077

* Εκτελέσιμο παράδειγμα: [https://dimitristria.github.io/D3js-uk-political-donations/](https://dimitristria.github.io/D3js-uk-political-donations/ 'Εκτελέσιμο παράδειγμα')
* Αποθετήριο κώδικα: [https://github.com/DimitrisTria/D3js-uk-political-donations](https://github.com/DimitrisTria/D3js-uk-political-donations 'Αποθετήριο κώδικα')

## Εισαγωγή
  Η παρακάτω εργασία, D3js-uk-political-donations, δημιουργήθηκε για τα πλαίσια της εργασίας εξαμήνου του μαθήματος Τεχνολογία Λογισμικού, του Ιόνιου Πανεπιστημίου, του έκτου εξαμήνου.

## Σύνοψη
  Η εργασία βάση του [αρχικού κώδικα](https://github.com/ioniodi/D3js-uk-political-donations 'αρχικού κώδικα') που μας δώθηκε, τηρεί τις προϋποθέσεις για τα παραδοτέα του μαθήματος. Επιπλέον, την επέκτεινα με τη προσθήκη ενός νέου γραφήματος στη d3 και συγκεκριμένα ενός ραβδογράμματος που μετρά συγχνότητες εμφάνησης, για το πρώτο αρχείο δεδομένων (7500up.csv), σχετικά με τους δότες σε κάθε κατηγορία.

## Ανάλυση σχετικών έργων και εργαλείων
* Λογισμικό ολοκληρωμένου περιβάλλοντος προγραμματισμού: [Visual Studio Code](https://code.visualstudio.com/ 'Visual Studio Code')
* Λογισμικό επεξεργασίας εικόνων: [Paint.Net](https://www.getpaint.net/ 'Paint.Net')
* Λογισμικό για τη επεξεργασία αρχείων τύπου csv και xls: [Apache OpenOffice Calc](https://www.openoffice.org/product/calc.html 'Apache OpenOffice Calc')

## Μέθοδος και τεχνικές ανάπτυξης
Αρχικά, μετά από την επιλογή του θέματος χρησιμοποίησα ένα περιβάλλον προγραμματισμού της επιλογής μου και συγκεκριμένα το Visual Studio Code. Ο λόγος για αυτό είναι το ότι, έχω τη δυνατότητα να τρέξω τον κώδικα εκτός διαδυκτίου και με σαφως μεγαλύτερη απόδοση και ταχύτητα τοπικά στο σύστημα που χρησιμοποιώ. Για την εκμάθηση της βιβλιοθήκης d3 της javascript χρησιμοποίησα τον ακόλουθο σύνδεσμο [https://d3js.org/](https://d3js.org/ 'https://d3js.org/'). Επιπλέον, χρησιμοποίησα το [Github](https://github.com/ 'Github') και το [Stack Overflow](https://d3js.org/ 'Stack Overflow') για απορείες καθώς και το [W3Schools](https://www.w3schools.com/ 'W3Schools')

### Παραδοτέο 1

Αποθετήριο κώδικα παραδοτέου 1: [https://github.com/DimitrisTria/D3js-uk-political-donations/tree/Παραδοτέο1](https://github.com/DimitrisTria/D3js-uk-political-donations/tree/Παραδοτέο1 'Παραδοτέο1')

#### Ζητούμενα στα οποία απαιτήθηκαν αλλαγές στο [προσωπικό αποθετήριο](https://github.com/DimitrisTria/D3js-uk-political-donations 'προσωπικό αποθετήριο') μου.

Παραδοτέο 1
* Ο σύνδεσμος της σελίδας μου με την εφαρμογή.
* Ο σύνδεσμος της σελίδας με την εφαρμογή, καθώς και το url της εφαρμογής τροποποιήθηκε ώστε να μην καταλήγει σε 'full-viz.html' και να περιλαμβάνει το αντίστοιχο username. Για να επιτευχθεί αυτό, ενεργοποιήθηκαν τα gh-pages και η ονομασία του αρχείου 'full-viz.html' αλλάχθηκε σε 'index.html'.
* Αλλαγή χρωμάτων στις μπάλες με τα δεδομένα, καθώς και στα αντίστοιχα 3 πεδία της ομαδοποίησης Split by party.
* Ήχος κάθε φορά που ο χρήστης της εφαρμογής κάνει κλικ σε μία από τις επιλογές/κουμπιά ομαδοποίησης των δεδομένων.
* Το κλικ σε κάποια μπάλα ανοίγει ένα νέο παράθυρο με τα αποτελέσματα της αναζήτησης στο google για τον αντίστοιχο δωρητή.
* Μεγένθυση όταν ο δείκτης βρίσκεται πάνω από τις λέξεις του κειμένου.
* Όταν το ποντίκι βρίσκεται μέσα στον κύκλο κάποιου δωρητή ακούγεται η ονομασία και το ποσό της δωρεάς του δωρητή, με τη χρήση της βιβλιοθήκης [responsivevoice](https://responsivevoice.org/ 'responsivevoice') στη javscipt.
* Νέο κουμπί για νέα ομαδοποίηση δεδομένων: Split by amount of donation.

Παραδοτέο 2
*

#### Ζητούμενα στα οποία απαιτήθηκαν αλλαγές στο [κοινό αποθετήριο του κώδικα](https://github.com/ioniodi/D3js-uk-political-donations 'κοινό αποθετήριο του κώδικα').

Παραδοτέο 1
  Αρχικά έγινε δημιουργία ενός αρχείου τύπου .csv με όνομα τον Α.Μ. μου και προσθέθηκε στον φάκελο participants, του κοινού αποθετηρίου.
[παρ1](https://github.com/ioniodi/D3js-uk-political-donations/pull/28)
[παρ2_1](https://github.com/ioniodi/D3js-uk-political-donations/pull/257)
[παρ2_1](https://github.com/ioniodi/D3js-uk-political-donations/pull/261)

### Παραδοτέο 2

## Παρακάτω ακολουθούν ενδεικτικές οθόνες και animated gif

## Συμπεράσματα

## Δικτυογραφία
* Ήχος διαφορετικής οπτικοποίησης: [Hover 2](https://freesound.org/people/plasterbrain/sounds/237421/ 'Hover 2')
* Ήχος διαφορετικής ομαδοποίησης: [guiclick2.ogg](https://freesound.org/people/farpro/sounds/264763/ 'guiclick2.ogg')
