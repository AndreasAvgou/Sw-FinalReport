# Τελική Αναφορά

# Μάθημα: Τεχνολογίες Λογισμικού

### Ονοματεπώνυμο: Αυγούστης Ανδρέας
### Αριθμός Μητρώου: Π2015115
### Email: p15avgo@ionio.gr
### Εξάμηνο: ΣΤ'
### Έτος: 2017-2018

## Εργασία: Οπτικοποίηση δεδομένων χορηγιών (UK)
## Links

#### [Εκτελέσιμο](https://p15avgo.github.io/D3js-uk-political-donations/)
#### [Αποθετήριο κώδικα](https://github.com/p15avgo/D3js-uk-political-donations/tree/Αρχικό-έργο-και-ενδιάμεση-αναφορά-προόδου)
#### [Αποθετήριο Github Pages κώδικα](https://github.com/p15avgo/D3js-uk-political-donations/tree/gh-pages)



### Σύνοψη

Σκοπός της εργασίας είναι η γνωριμία με της γλώσσες προγραμματισμού διαδικτύου(**html**,**css**,**javascript**) και τη βιβλιοθήκη **D3** της **javascript** (οπτικοποίηση δεδομένων), χρησιμοποιώντας παράλληλα τις σελίδες **github pages** και την αξιοποίηση των δυνατοτήτων της γλώσσας **javascript** για λειτουργίες μεγένθυνσης κειμένου και text-to-speech.

### Εισαγωγή

Η εργασία αφορά την οπτικοποίηση των στατιστικών στοιχείων δωρεών που έχουν γίνει σε πολιτικά κομματα της Μεγάλης Βρετανίας.
Σκοπός της εργασίας είναι η γνωριμία με τη βιβλιοθήκη **D3** της **javascript** (οπτικοποίηση δεδομένων), καθώς και η αξιοποίηση των δυνατοτήτων της γλώσσας **javascript** για λειτουργίες μεγένθυνσης κειμένου και text-to-speech.
Επίσης, έχει στόχο την εξοικείωση με το περιβάλλον του **github** αλλά και την χρήση των **github pages**.
Τέλος, εκτός από την **javascript** στοχεύει και στην επαφή και αλληλεπίδραση με άλλες γλώσσες προγραμματισμού διαδικτύου(**html**,**css**).

### Εργαλεία και ανάλυση σχετικών έργων

Στα πλαίσια της εργασίας τα εργαλεία που χρησιμοποιήθηκαν ήταν το **sublime text 3** για τις τροποποήσεις του κώδικα και το **github** ώστε να μπορέσω να δω τις αλλαγές. Επίσης, χρησιμοποίησα διάφορες ιστοσελίδες όπως το W3schools.com,javascript.com και το tutorialspoint.com για εκμάθηση των γλωσσών προγραμματισμού διαδικτύου.

Οι κώδικες που ήταν έτοιμοι και τους τροποποιήσα: 

 a) [d3-uk-political-donations](https://github.com/ioniodi/D3js-uk-political-donations) 
 
 b) [Link κώδικα της κινούμενης εικόνας](https://github.com/ioniodi/D3js-uk-political-donations/blob/master/participants/index.html)
 
Παρακάτω αναγράφονται οι αλλαγές που ζητήθηκαν και υλοποιήθηκαν στα παραδοτέα 1 και 2

### Παραδοτέο 1ο

### 1ο Μέρος

* Αλλαγή του ονόματος **full-viz.html** σε **index.html** στο αποθετήριο **github pages** έτσι ώστε να μην εμφανίζετε στο τέλος το full-viz.

* Αλλαγή χρωμάτων στις μπάλες με τα δεδομένα,καθώς και στα αντίστοιχα 3 πεδία της ομαδοποίησης **Split by party**.
Για την αλλαγή των χρωμάτων χρησιμοποιήθηκαν διαφορετικές μεταβλητές στο rgba και HEX.


![color](https://raw.githubusercontent.com/p15avgo/sw/master/projects/2015115/ColorChange.png)

* Τοποθετήθηκε [ήχος](https://www.soundjay.com/button/sounds/button-17.mp3) κάθε φορά που ο χρήστης κάνει κλικ σε μία από τις επιλογές/κουμπιά ομαδοποίησης των δεδομένων.Δημιουργήθηκε script στο **index.html** αρχείο και χρησιμοποιώντας το ButtonSound.mp3.    

* Δημιουργήθηκε η δυνατότητα όπου ο χρήστης να κλικ σε κάποια μπάλα έτσι ώστε να ανοίγει ένα νέο παράθυρο με τα αποτελέσματα της αναζήτησης στο google για τον αντίστοιχο δωρητή.Στο συγκεκριμένο σημείο προστέθηκε η συνάρτηση **googleSearch()** όπου έχει την εντολή **window.open()** και εκτελεί την λειτουργία που προαναφέρθηκε.

![google](https://raw.githubusercontent.com/p15avgo/sw/master/projects/2015115/google.gif)

* Έγινε προσθήκη της μεγένθυση όταν ο δείκτης βρίσκεται πάνω από τις λέξεις του κειμένου.
Δημιουργήθηκε η κλάση **zoom** στο **style.css** και για να ενσωματώθη στο **index.html** αρχείο χρειάστηκε η δημιουργία ενός script έτσι ώστε να λειτουργεί σωστά σε όλα τα σημεία του κώδικα.

![zoom](https://raw.githubusercontent.com/p15avgo/sw/master/projects/2015115/zoom.gif)

* Όταν το ποντίκι βρίσκεται μέσα στον κύκλο κάποιου δωρητή ακούγεται η ονομασία και το ποσό της δωρεάς του δωρητή.
Χρησιμοποιήθηκε το **responsiveVoice()** που είναι μια από τις λειτουργίες **text-to-speech**.

* Δημιουργία νέας ομαδοποίηση δεδομένων: **Split by amount of donations**.
Για την δημιουργία της νέας ομαδοποίησης χρειάστηκε να γίνουν αλλαγές και στα 3 αρχεία(**index.html,style.css,chart.js**)

![splitbyamount](https://raw.githubusercontent.com/p15avgo/sw/master/projects/2015115/SplitByAmountOfTheDonation.png)

### 2ο Μέρος
[Αποθετήριο Participants](https://github.com/p15avgo/D3js-uk-political-donations/tree/Participants)

[Merged pull-request](https://github.com/ioniodi/D3js-uk-political-donations/pull/25)

### Εικόνες

May Makhzoumi (100)

Lord Fink (101)

Peter Cruddas (102)

Michael Davis (103)

James R Lupton (104)

### Αρχείο CSV
2015115

### Παραδοτέο 2ο

### 1ο Μέρος

* Tροποποιήθηκε o κώδικας ώστε να εμφανίζεται αλλά και να επεκτείνεται δυναμικά η **σειρά** των εικόνων με τους **δωρητές** πάνω από τους οποίους πέρασε ο δείκτης του ποντικιού σας στο γράφημα.
Έγινε προσθήκη στης συνάρτησης **mouseTrackingCrumbs** στο **style.css** για την και ενσωματώθηκε στο **index.html** αλλά και στο **chart.js** αρχείο για να εμφανίζονται οι εικόνες δυναμικά κάθετα κάθε φορά που βλέπουμε δωρητή.

![image](https://raw.githubusercontent.com/p15avgo/sw/master/projects/2015115/icons.gif)

### 2ο Μέρος

* Τροποποιήθηκε ο κώδικας ώστε να εμφανίζονται τα στοιχεία μου στο λογαριασμό του **github** με **κίνηση**.
Η θέση που δέσμευσα είναι "position#004".

![move](https://raw.githubusercontent.com/p15avgo/sw/master/projects/2015115/name.gif)


### Συμπέρασμα

H συγκεκριμένη εργασία δίνει την ευκαιρία στους φοιτητές να μάθουν και να εξοικειωθούν με τις γλώσσες **html**,**css**,**javascript** και πιο συγκεκριμένα με την βιβλιοθήκη **D3** της **javascript**. Επιπλέον, μπορούν να μαθαίνουν να δημιουργούν ιστοσελίδες με τη βοήθεια των **github pages**, καθώς και διαδικασίες του **github** (**fork** και **pull request**).

### Αναφορές
[https://www.tutorialspoint.com](https://www.tutorialspoint.com)

[https://www.w3schools.com](https://www.w3schools.com)

[https://www.javascript.com](https://www.javascript.com)

[https://responsivevoice.org](https://responsivevoice.org)

[http://tobiasahlin.com/moving-letters](http://tobiasahlin.com/moving-letters)
