# Τελική αναφορά του μαθήματος Επικοινωνία Ανθρώπου-Υπολογιστή
### Ονοματεπώνυμο:Πλιάφας Θεόδωρος
### Αριθμός Μητρώου:Π2017012

#### [Link αποθετηρίου](https://github.com/Thodoros/D3js-US-educational-attainment)
#### [Εκτελέσιμο link](https://thodoros.github.io/D3js-US-educational-attainment/)

## Εισαγωγή
Η εργασία αυτή έχει ως στόχο στην εκμάθηση τριών γλωσσών(html,css,javascript) που χρησιμοποιούνται στο Web μέσω καποιών αλλαγών που πρέπει να γίνουν σε ήδη υπάρχοντα κώδικα.Η αναφορά αυτή περιέχει εικόνες καθώς και gifs από τα αποτελέσματα που που βγαίνουν,έπειτα από τις αλλαγές που ζητούνται στον κώδικα.Εκτός από το τελευταίο ζητούμενο του 1ου παραδοτέου,στο οποίο δε κατάφερα να κάνω τα διαγράμματα responsive, και στο 2ο ζητούμενο του 2ου παραδοτέου τα υπόλοιπα ζητούμενα υλοποιήθηκαν χωρίς κάποιο πρόβλημα ή δυσκολία.

## Σύντομη ανάλυση σχετικών έργων και εργαλείων
Για την υλοποίηση της εργασίας χρησιμοποίηθηκε εκτός από το github και το notepad++ για να υπάρχει η δυνατότητα τα αποτελέσματα να φαίνονται αυτόματα,γιατί αρκετές φορές το github αργεί να φορτώσει τις νέες αλλαγές.Επίσης,χρησιμοποιήθηκαν και εκπαιδετικές ιστοσελίδες όπως [W3Schools](https://www.w3schools.com/),[Stack Overflow](https://stackoverflow.com/) και [Html dog](http://www.htmldog.com/) για την αναζήτηση παραδειγμάτων για το τρόπο λειτουργίας των γλωσσών καθώς και το [CodePen](https://codepen.io/) για την άντληση παραδειγμάτων σχετικά με τα διαγράμματα της [D3.js](https://d3js.org/).

## Mέθοδος και τεχνικές ανάπτυξης

### Πρώτο Παραδοτέο

### 1ο ζητούμενο
Για την αλλαγή χρωμάτων στα διαγράμματα,αλλάχτηκαν τα χρώματα που βρίσκοταν(σε hex μορφή) στα:[script_1.js](https://github.com/Thodoros/D3js-US-educational-attainment/blob/master/assets/scripts/script_1.js) για το πρώτο γράφημα,[script_2.js](https://github.com/Thodoros/D3js-US-educational-attainment/blob/master/assets/scripts/script_2.js) για το δεύτερο γράφη,α,[script_3.js](https://github.com/Thodoros/D3js-US-educational-attainment/blob/master/assets/scripts/script_3.js) για το τρίτο γράφημα.

#### 1ο γράφημα
![colour1](colour1.png)

![1oPar1](/1oPar1.png)

#### 2ο γράφημα
![colour2](colour2.png)

![1oPar1.2](/1oPar1.2.png)

#### 3ο γράφημα
![colour3](colour3.png)

![1oPar1.3](/1oPar1.3.png)


### 2ο ζητούμενο
Για την αλλαγή των διεπαφών στα κούμπια,αλλάχτηκε ο κώδικας στο [style.css](https://github.com/Thodoros/D3js-US-educational-attainment/blob/master/assets/stylesheets/style.css) και άλλαξε το χρώμα τον κουμπιών και το περίγραμμα.
![style](style.png)

![1oPar2](1oPar2.png)

![1oPar2.1](1oPar2.1.png)


### 3ο ζητούμενο
Για να ακούγεται ο ήχος στο μενού ανέβηκαν δύο αρχεία ήχου [mouse-click .ogg](https://github.com/Thodoros/D3js-US-educational-attainment/blob/master/mouse-click%20.ogg) και [mouse-click.mp3](https://github.com/Thodoros/D3js-US-educational-attainment/blob/master/mouse-click.mp3) καθώς και το αρχείο [sound-menu-mouseover.js](https://github.com/Thodoros/D3js-US-educational-attainment/blob/master/sound-menu-mouseover.js).
Έπειτα,εισήχθηκε στο [index.html](https://github.com/Thodoros/D3js-US-educational-attainment/blob/master/index.html) ένα script ,μία συνάρτηση onmouseover="playclip();" και ένα audio tag.

![1oPar3](/1oPar3.png)

![1oPar3.2](/1oPar3.2.png)

![1oPar3.3](/1oPar3.3.png)


### 4ο ζητούμενο
Για την αυτόματη αφήγηση του κειμένου χρησιμοποιήθηκε η βιβλιοθήκη [responsive voice](https://responsivevoice.org/).Προσθέθηκε έπειτα στο [index.html](https://github.com/Thodoros/D3js-US-educational-attainment/blob/master/index.html) ένα script και η συνάρτηση onmouseover="responsiveVoice.speak() στα απαραίτητα σημεία.

![1oPar4](/1oPar4.png)

![1oPar4.2](/1oPar4.2.png)


#### 5ο ζητούμενο
Για το responsive design προστέθηκε στο  [index.html](https://github.com/Thodoros/D3js-US-educational-attainment/blob/master/index.html) ένα script.Ωστόσο δε κατάφερα να κάνω τα γραφήματα responsive.

![1οPar5](/1oPar5.png)

![responsive](/responsive.png)


### Δεύτερο Παραδοτέο

#### 1ο ζητούμενο
Για να εμφανίζεται μόνο ένα από τα γραφήματα της επιλογής μας κάθε φορά,προσθέθηκε η συνάρτηση showhide και έπειτα στο μενού το onclick="showhide();".

![2οPar1.2](/2oPar1.2.png)

![1οPar3.2](/1oPar3.2.png)

![2opar1](/2opar1.png)

#### 2ο ζητούμενο
Δεν κατάφερα να το πραγματοποιήσω.

#### 3ο ζητούμενο
Δημιουργήθηκαν 3 νέα γραφήματα,[script_4](https://github.com/Thodoros/D3js-US-educational-attainment/blob/master/assets/scripts/script_4.js),[script_5](https://github.com/Thodoros/D3js-US-educational-attainment/blob/master/assets/scripts/script_5.js),[script_6](https://github.com/Thodoros/D3js-US-educational-attainment/blob/master/assets/scripts/script_6.js) με στατιστικά δεδομένα της [ΕΛΣΤΑΣΤ](http://www.statistics.gr/) τα οποία τοποθετήθηκαν σε μία νέα σελίδα [examples.html](https://github.com/Thodoros/D3js-US-educational-attainment/blob/master/examples.html).

![2οPar3](/2oPar3.png)


## Συμπεράσματα
Η εργασία αυτή βοηθαεί το φοιτητή να αναπτύξει τις γνώσεις του πάνω στις τρεις πιο διαδεδομένες Web γλώσσες(html,CSS,Javascript) καθώς και να έρθει σε μία πρώτη επαφή με τα γραφήματα της [D3.js](https://d3js.org/) τα οποία είναι ευρέως διαδεδομένα και χρησιμοποιούνται αρκετά.Τέλος,ωθεί το φοιτητή στην αναζήτηση πληροφοριών και παραδειγμάτων ώστε να μπορέσει να προχωρήσει στην επίλυση των ζητουμένων των εργασίων και του καλλιεργεί το σωστό τρόπο αναζήτησης.

## Βιβλιογραφία και συνδέσμους σε σχετικές εργασίες

* https://codepen.io/
* [1ο διάγραμμα](https://codepen.io/borntofrappe/pen/qYWPVg)
* [2o διάγραμμα](https://codepen.io/leoneloliver/pen/LQMxJB)
* [3ο διάγραμμα](https://codepen.io/michaellee/pen/eNodMx)
* https://d3js.org/
* http://www.statistics.gr/
* https://responsivevoice.org/
* https://www.w3schools.com/
* https://stackoverflow.com/
* http://www.htmldog.com/
