# Εγκατάσταση προσαρμοσμένου και εξατομικευμένου λειτουργικού συστήματος

* Για την πλήρη βαθμολόγηση του σετ ασκήσεων γραμμής εντολών θα πρέπει να γίνει εγκατάσταση του κατάλληλου λειτουργικού συστήματος. Η εκτέλεση των ασκήσεων σε έτοιμα περιβάλλοντα με γραμμή εντολών (π.χ., MacOSX, Ubuntu, Windows 10 WSL) είναι μερικώς αποδεκτή με μειωμένη βαθμολόγηση. Για πλήρη βαθμολόγηση θα πρέπει να γίνει εγκατάσταση ενός νέου καθαρού συστήματος και προσαρμογή του στους στόχους και στις προτιμήσεις σας, όπως αυτά περιγράφονται στην εισαγωγή της εργασίας σας.
* Ο πιο ασφαλής τρόπος εγκατάστασης είναι η χρήση ενός εξωτερικού αποθηκευτικού μέσου (USB3, 16GB), έτσι ώστε να μην επηρεάσετε το καθημερινό σας σύστημα με dual boot. 
* Η εγκατάσταση και η εξοικείωση με ένα νέο λειτουργικό σύστημα είναι μια μακροχρόνια άσκηση με (πολλά) ενδιάμεσα βήματα και ανάλογα με την κατανόηση που έχετε για την μέγιστη ασφάλεια του βασικού καθημερινού συστήματος μπορεί να γίνει αρχικά σε μια εικονική μηχανή και σταδιακά σε εξωτερικό αποθηκευτικό μέσο παράλληλα με την εκτέλεση των άλλων ασκήσεων στο βασικό σας σύστημα ή σε μια εικονική μηχανή, για μειωμένη βαθμολόγηση.

* HCI, CSCW, IV: Το [ArchLinux](https://wiki.archlinux.org/title/Installation_guide) είναι η 2η πιο δημοφιλής διανομή του συστήματος linux μετά το debian καθώς [βρίσκεται στην βάση πολλών άλλων συστημάτων](https://distrowatch.com). Ο βασικός λόγος που πολλοί χρήστες και διανομείς το επιλέγουν είναι η [απλή φιλοσοφία του](https://wiki.archlinux.org/title/Arch_Linux#Principles) που επιτρέπει την καλύτερη κατανόηση κάθε προσθήκης, η οποία θα πρέπει να γίνει χειροκίνητα και όχι  αυτόματα. Επομένως, για την πλήρη βαθμολόγηση δεν γίνονται δεκτές εκδοχές του Arch, όπως το δημοφιλές Manjaro που βασίζονται σε αυτόματη εγκατάσταση, ούτε και εγκατάσταση σε εικονικές μηχανές, παρά μόνο εγκατάσταση σε αληθινό υλικό. Η εγκατάσταση σε εικονική μηχανή είναι δεκτή, αλλά θα βαθμολογηθεί στην βάση, αφού χάνονται σημαντικές γνώσεις και δεξιότητες διάδρασης με το υλικό.
* SW: Το [Linux from Scratch](https://www.linuxfromscratch.org/lfs/view/11.0/) επιτρέπει πολύ μεγάλη προσαρμογή του συστήματος στις ανάγκες μιας δραστηριότητας. Επίσης, γίνονται δεκτά παρόμοια συστήματα που δεν έχουν systemd και βασίζονται στον πηγαίο κώδικα (ports) όπως τα [kiss linux](https://kisslinux.org), [plan9](http://9legacy.org/index.html), [funtoo](https://www.funtoo.org/Install/Introduction). Σκοπός της άσκησης είναι η εγκατάσταση και χρήση εναλλακτικών συστημάτων και κυρίως η κατανόηση της πρόσφατης προσθήκης του systemd και αυτό μπορεί να γίνει μόνο με ένα σύστημα που δεν το έχει. Η εγκατάσταση μπορεί να γίνει σε εικονική μηχανή ή σε κανονικό υλικό, και για μειωμένο βαθμό σε BSD.
* [Λίστα με διαθέσιμες ασκήσεις γραμμής εντολών](https://github.com/epidrome/dokey)

Αν και σε πρώτη ανάγνωση η χειροκίνητη εγκατάσταση ενός λειτουργικού συστήματος δεν φαίνεται εύχρηστη, τελικά, για κάποιον συχνό χρήστη, όπως είναι ένας ειδικός της πληροφορικής, η χειροκίνητη εγκατάσταση παρέχει μια αναγνωσιμότητα των διαδικασιών και των μηχανισμών που διευκολύνουν την μακροπρόθεση συντήρηση αυτού του συστήματος, ανεξάρτητα από τα (συνήθως κερδοσκοπικά) συμφέροντα εταιρειών που πουλάνε έτοιμη την ευχρηστία.

# Γραφικό περιβάλλον, IV

| assignments | deliverables | references |
| -- | -- | -- |
| add a status bar to your shell/editor and configure a color-theme | edit the configuration files for your status line and for your color theme | [status bar](https://github.com/powerline/powerline) [solarized](https://github.com/altercation/solarized) [redshift](https://github.com/jonls/redshift) [pywall](https://github.com/dylanaraps/pywal) |
| configure a custom desktop enviroment | customize the wallpaper, menu, bar, notifications, windows, screensaver and demonstrate them with a GIF | [polybar](https://github.com/polybar/polybar) [rofi](https://github.com/davatorium/rofi) [dunst](https://github.com/dunst-project/dunst) [awesome](https://github.com/awesomeWM/awesome) [pipes](https://github.com/pipeseroni/pipes.sh) [flashfocus](https://github.com/fennerm/flashfocus) |
| configure a custom window manager | try different wm and configure one to fit your needs| [sowm](https://github.com/dylanaraps/sowm) [dwm](https://dwm.suckless.org/) |


# Οδηγίες για την παράδοση και τα κριτήρια της βαθμολόγησης, HCI, IV, SW

* HCI: Οι πρώτες εβδομάδες και τα πρώτα παραδοτέα αυτής της εργασίας μέχρι την 6η εβδομάδα είναι αναφορές με τις ενέργειες που έγιναν για την εγκατάσταση και προσαρμογή του νέου λειτουργικού συστήματος, π.χ., την 1η εβδομάδα θα πρέπει να εντοπίσετε τα χαρακτηριστικά που έχει το υλικό σας (δίσκος, μνήμη, επεξεργαστής, δίκτυο, γραφικά, κτλ)
* IV: Θεωρείται δεδομένο ότι έχετε μια λειτουργική εγκατάσταση και το ζητούμενο είναι να δοκιμάσετε διαφορετικά γραφικά περιβάλλοντα και εναλλακτικές προσαρμογές στις παραμέτρους τους καθώς και στο υποσύστημα της γραμμής εντολών για την οπτικοποίηση πληροφορίας και δεδομένων που είναι σημαντικά για εσάς.
* Για την βαθμολόγηση του λειτουργικού συστήματος θα πρέπει να γίνει ένα  asciinema με boot log, system info (π.χ, journalctl -b, neofetch)
* Για την βαθμολόγηση του γραφικού περιβάλλοντος θα πρέπει να γίνει ένα gif, με ένα εργαλείο όπως το [peek](https://github.com/phw/peek), που θα αποθηκευτεί σε εξωτερικό χώρο από το αποθετήριο της αναφοράς σας. Η καταγραφή της εικόνας θα πρέπει να δίνει έμφαση μόνο στα σημεία όπου έχετε κάνει μια διαφορετική ρύθμιση-χρήση και όχι στην απλή εγκατάσταση των έτοιμων εργαλείων, οπότε η διάρκεια μπορεί να είναι πολύ μικρή.
* Το κάθε μάθημα έχει διαφορετικό σετ ασκήσεων τις οποίες θα βρείτε κάτω από τον αντίστοιχο τίτλο.
* Μερικές ασκήσεις σε προχωρημένα μαθήματα (CSCW, IV, SW) βασίζονται σε ασκήσεις από τo βασικό μάθημα (HCI).
* Τα κριτηρια βαθμολόγησης είναι διαφορετικά ανάλογα με το μάθημα, π.χ., στο HCI αξιολογούμε την διάδραση με τον χρήση για καθημερινές εφαρμογές, ενώ στο SW, αξιολογούμε την οργάνωση και τις τεχνικές για την ανάπτυξη και συντήρηση λογισμικού.
* Το κάθε σετ έχει περισσότερες από δέκα ασκήσεις οι οποίες εμφανίζονται με σειρά δυσκολίας από την πιο εύκολη στην πιο δύσκολη.
* Αν γίνουν περισσότερες από όσες ορίζει ένα μάθημα τότε θα κρατήσουμε αυτόματα για εσάς τους καλύτερους βαθμούς, επομένως σας συμφέρει να κάνετε όσες περισσότερες μπορείτε, αν και είναι πιο σημαντικό να τις κάνετε σε βάθος.
* Για να κατοχυρώσετε τις προθεσμίες αρκεί να έχουν γίνει commit τα asciinema link μέσα στην αναφορά σας στο αντίγραφο του κεντρικού αποθετηρίου. Αρχικά, δεν χρειάζεται να κάνετε αίτημα ενσωμάτωσης, έτσι ώστε να βελτιώσετε το παραδοτέο μετά από σχολιασμό στο μάθημα, και να το παραδώσετε ενημερωμένο με το αίτημα ενσωμάτωσης της τελικής αναφοράς.
* Μόνο για την προθεσμία της τελικής αναφορά θα πρέπει να στείλετε αίτημα ενσωμάτωσης στο αντίστοιχο αποθετήριο του μαθήματος.
* Μετά την προθεσμία για κομίτ κάθε παραδοτέου, η κάθε άσκηση βαθμολογείται με άριστα την βάση, εκτός και αν γίνει πολύ σημαντική προσπάθεια και συνεισφορά πέρα από τα ζητούμενα.
* **Για να βαθμολογηθεί μια άσκηση θα πρέπει [το command prompt να είναι ο ΑΜ σας](https://unix.stackexchange.com/questions/35777/how-to-change-the-prompt-in-linux), να έχετε λινκ στο asciinema, και option `idle-time < 0.2-0.5 sec`, έτσι ώστε η διάρκεια να είναι σχετικά μικρή, μεγάλες διάρκειες, χωρίς σημαντικό περιεχόμενο βαθμολογούνται αρνητικά.** 
* Η βαθμολογική βάση (5) αντιστοιχεί σε μια καλογραμμένη τελική αναφορά με λινκ στο asciinema όπου κάνετε ντέμο στις βασικές δυνατότητες του αντίστοιχου εργαλείου. 
* Ο βαθμός βελτιώνεται (6) για κάθε πρόσθετη λειτουργία-ρύθμιση που κάνετε, γίνεται πολύ καλός (7) αν κάνετε απλές διασυνδέσεις με άλλα εργαλεία του συστήματος (π.χ., [pipelining](https://youtu.be/tc4ROCJYbm0?t=296), shell scripting), και άριστος (8-10) αν κάνετε σημαντικές διασυνδέσεις με άλλα εργαλεία με σκοπό την καθημερινή χρήση για πολύ ειδικές ανάγκες που έχετε και τις έχετε περιγράψει στην εισαγωγή. 
* Σε όλες τις περιπτώσεις για βαθμό πάνω από την βάση θα εκτιμηθεί η ενσωμάτωση και χρήση των εργαλείων για τις δικές σας ανάγκες όπως αυτές καταγράφονται κατά την έναρξη του μαθήματος και όχι απλά η υιοθέτηση τους για ντέμο.
* Ειδικά για τα μαθήματα HCI, IV, θα εκτιμηθεί η παραμετροποίηση ενός προσωπικού γραφικού περιβάλλοντος εργασίας πέρα από τα έτοιμα πακέτα (gnome, kde), όπως αυτά που μοιράζονται οι χρήστες στο [σχετικό φόρουμ στο ρεντιτ](https://www.reddit.com/r/unixporn/).
* Ειδικά για το μάθημα IV θα πρέπει να γίνει σημαντική προσαρμογή ενός πολύ βασικού γραφικού περιβάλλοντος όπως είναι το [dwm](https://dwm.suckless.org)
* Η ανάπτυξη pipelining, shell scripting μπορεί να διευκολυνθεί με τεκμηρίωση και εργαλεία όπως τα [pipr](https://github.com/elkowar/pipr), [pure bash bible](https://github.com/dylanaraps/pure-bash-bible).
* H βιβλιοθήκη συνδυασμού μενού με γραμμή εντολών [Ncurses](https://en.wikipedia.org/wiki/Ncurses) εμφανίζεται σε κάποια εργαλεία αλλά θεωρείται υβριδικό, οπότε η χρήση του δεν ενθαρρύνεται, καθώς είναι δύσκολο με αυτό να πετύχουμε τα ζητούμενα (pipelining, scripting) για έναν άριστο βαθμό.

---
# Διάδραση με την γραμμή εντολών

Οι εργασίες γραμμής εντολών ενθαρρύνουν μια εναλλακτική διάδραση με τον υπολογιστή, η οποία ήταν κάποτε (1970-1990) ο βασικός τρόπος διάδρασης, αλλά πλέον χρησιμοποιείται κυρίως από τους ειδικούς της κατασκευής λογισμικού. Αν και αυτός ο τρόπος διάδρασης δεν είναι ο πιο προσβάσιμος και φιλικός για τον αρχάριο και τον περιστασιακό χρήστη, είναι όμως ο πιο αποδοτικός τρόπος διάδρασης για τον ειδικό χρήστη (π.χ., προγραμματιστής εφαρμογών, web developer, network admin), αλλά και για όλους τους έμπειρους χρήστες που δουλεύουν κυρίως με κείμενο.

Για τον σκοπό αυτό θα κάνουμε τις παρακάτω δραστηριότητες: 

1. Κατανόηση και ανάπτυξη δεξιοτήτων στην διεπαφή γραμμής εντολών
2. Καθημερινή χρήση της γραμμής εντολών ως εναλλακτική διεπαφή της γραφικής για τις δικές σας καθημερινές ανάγκες πληροφορικής
3. Κατασκευή νέων σύνθετων διεπαφών γραμμής εντολών που εξυπηρετούν τις δικές σας ανάγκες και βασίζονται σε υπάρχουσες εντολές που συνδυάζονται με τις τεχνικές pipelines-scripts
4. Σύνθεση και κατασκευή νέων εναλλακτικών συστημάτων διάδρασης ή οργάνωσης της ανάπτυξης λογισμικού, που βασίζονται σε ευέλικτα λειτουργικά συστήματα όπως τα archlinux, funtoo, LFS.

Επιλέγουμε να δουλέψουμε με την γραμμή εντολών και όχι με κάποιο άλλο δημοφιλές σύστημα διάδρασης (π.χ., γραφική επιφάνεια εργασίας, κινητός υπολογισμός), γιατί αυτό είναι το πιο απλό, διαχρονικό, και εύκολο να αλλάξει σύστημα.