# c-domes
Περιγραφή 

Οι δομές που πρέπει να υλοποιηθούν είναι: 
                                          1) απλό δυαδικό δένδρο αναζήτησης, 
                                          
                                          2) δυαδικό δένδρο αναζήτησης τύπου AVL και 
                                          
                                          3) πίνακας κατακερματισμού με ανοικτή διεύθυνση. 
                                          
Οι δομές αυτές θα πρέπει να αποθηκεύουν τις διαφορετικές λέξεις του κειμένου και το πλήθος εμφανίσεων της κάθε λέξης μέσα στο κείμενο. 

Υποθέτουμε ότι μία λέξη λ1 είναι μικρότερη από μία λέξη λ2, όταν η λ1 λεξικογραφικά βρίσκεται πριν από τη λέξη λ2. 

Για παράδειγμα “that” < “this”, “apple” < “cat”, “over” < “under” κλπ. 

Το κείμενο πάνω στο οποίο θα δουλέψετε είναι από το Gutenberg Project (https://www.gutenberg.org/) και περιέχει γνωστά έργα παγκόσμιας λογοτεχνίας. 

Το αρχείο με το οποίο θα εργαστείτε θα αναρτηθεί στο elearning μαζί με την εκφώνηση της εργασίας. 

Ωστόσο, μπορείτε να χρησιμοποιήσετε στις δοκιμές σας και μικρότερα αρχεία ώστε να μπορείτε να ελέγχετε την ορθότητα της υλοποίησή σας.  

Για κάθε δομή, θα πρέπει να υπάρχει ένα αρχείο .h το οποίο θα πρέπει να γίνεται #include από το πρόγραμμα που θέλει να χρησιμοποιήσει την αντίστοιχη δομή. 

Επίσης, για κάθε δομή θα πρέπει να υπάρχει τουλάχιστον ένα .cpp αρχείο το οποίο υλοποιεί την αντίστοιχη δομή. 

Το πρόγραμμά σας δε θα διαβάζει τίποτε από το πληκτρολόγιο. 

Όταν το πρόγραμμα εκτελεστεί θα πρέπει αρχικά να κατασκευάσει τις τρεις δομές δεδομένων εισάγοντας τις λέξεις μία προς μία καθώς διαβάζουμε τις γραμμές του αρχείου. 

Στη συνέχεια, θα πρέπει από το αρχείο κειμένου να επιλεγεί με τυχαίο τρόπο ένα σύνολο Q από π.χ. 1000 λέξεις (όχι κατ’ ανάγκη διαφορετικές) οι οποίες θα χρησιμοποιηθούν για να εκτελέσουμε αναζητήσεις στις δομές που έχουμε υλοποιήσει. 

Στη συνέχεια αναζητούμε όλες τις λέξεις του συνόλου Q σε κάθε δομή και επιστρέφουμε τον αντίστοιχο συνολικό χρόνο εκτέλεσης (πόσο χρόνο χρειάστηκε η δομή να απαντήσει στα ερωτήματα) καθώς και πόσες φορές εμφανίζεται η κάθε λέξη. 

Είναι προφανές ότι για κάθε λέξη που αναζητούμε, οι τρεις δομές θα πρέπει να δώσουν ίδιο αποτέλεσμα ως προς το πλήθος των εμφανίσεων αλλά διαφορετικό χρόνο εκτέλεσης. 

Η κατασκευή των δομών και η αναζήτηση θα γίνεται από τη main() η οποία πρέπει να καλέσει τις κατάλληλες μεθόδους από τις κλάσεις που υλοποιούν τις δομές. 

Επίσης, το πρόγραμμά σας θα πρέπει να υποστηρίζει για τις δομές των δένδρων: εισαγωγή, διαγραφή, αναζήτηση, inorder, preorder, postorder. 

Για τον πίνακα κατακερματισμού απαιτείται μόνο εισαγωγή και αναζήτηση (να μην υλοποιηθεί η διαγραφή).  

Στην αναφορά που θα παραδώσετε θα πρέπει να εξηγήσετε τον τρόπο σχεδιασμού και υλοποίησης της εφαρμογής σας και γενικά να δώσετε τις πληροφορίες που θεωρείτε απαραίτητες. 

Επίσης, ο κώδικάς σας θα πρέπει να περιέχει επαρκή σχόλια (είτε στα ελληνικά είτε στα αγγλικά αλλά όχι σε greeklish!)
