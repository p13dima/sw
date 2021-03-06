## ΤΕΧΝΟΛΟΓΙΑ ΛΟΓΙΣΜΙΚΟΥ
## Ονοματεπώνυμο: Χρήστος Δήμας
## Α.Μ.: Π2017204
## ΠΡΟΣΩΠΙΚΟ ΑΠΟΘΕΤΗΡΙΟ: [link](https://github.com/chris4dim/sw/tree/2017204/projects/2017204)
# [ΤΕΛΙΚΗ ΑΝΑΦΟΡΑ](https://chris4dim.github.io/sw-Final_Report/)


### Άσκηση 1:
Assignment: try different terminals and shells.

Deliverables: repeat some of the previous exercises with a different terminal-shell and create a custom configuration that fits your needs.

Για να γίνει η διεκπεραίωση της εργασίας αυτής έκανα χρήση 4 διαφορετικών τέρμιναλς (guake, tilda, yuakake και terminology) και έγινε η εγκατάσταση αυτών με τις παρακάτω εντολες:

```
 $ sudo apt-get -f install guake
 $ sudo apt-get -f install tilda
 $ sudo apt-get -f install yakuake
 $ sudo apt-get -f install terminology
```
Για την επίδειξη του κάθε τέρμιναλ χρησιμοποίησα απλές εντολές, οποίες περιγράφονται στο αντίστοιχο βίντεο του aasciinema, δημιουργώντας κάθε φορά ένα φάκελο με το όνομα του κάθε τέρμιναλ και μέσα σε αυτόν ένα αρχείο python με όνομα hello.py και με έξοδο κατα την εκτέλεσή του "hello world!!!". Κατά την καταγραφή της διαδικασίας του εκάστοτε τέρμιναλ χρησιμοποίηθηκε το asciinema και ένα αντίστοιχο στιγμιότυπο "screenshot" για την επίδειξη του αποτελέσματος, καθώς στα βίντεο δεν καταγράφονται τα χρώματα και άλλα χαρακτηριστικά του κάθε τέρμιναλ.

guake: είναι ένα τέρμιναλ, όπου ο χρήστης το μετακινεί στο πάνω ή στο κάτω μέρος της οθόνης, πατώντας το πλήκτρο F12. Τέλος, ο χρήστης μπρεί να αλλάξει την εμφάνισή του καθώς επίσης και να αλλάξει και τα διάφορα πλήκτρα με βάση τις ανάγκες του.

### Asciinema URL: [guake](https://asciinema.org/a/gzz8Ei9dT3bhcdFgyLtzcKjJL)

### Εικόνα του τέρμιναλ "guake".

![guake](https://user-images.githubusercontent.com/44117722/77182803-02c17580-6ad6-11ea-91d3-7c7b98f7de32.png)

tilda: είναι ένα τέρμιναλ, που δεν καταλαμβάνει ολόκληρη την οθόνη, αλλά έχει το χαρακτηριστικό να μετακινείς το τέρμιναλ στο πάνω ή στο κάτω μέρος της οθόνης, χρησιμοποιώντας το F1 πλήκτρο. Επίσης, υπάρχει το χαρακτηριστικό ότι ο χρήστης μπορεί να αλλάξει την εμφάνισή του, αλλάζοντας τον φόντο του τέρμιναλ. Τέλος, υπάρχει η δυνατότητα αλλαγής πλήκτρων με βάση τις ανάγκες μας.

### Asciinema URL: [tilda](https://asciinema.org/a/uvMgNoIrHYh0yVr9nNxMCmAid)

### Εικόνα του τέρμιναλ "tilda".
![tilda](https://user-images.githubusercontent.com/44117722/77183469-09042180-6ad7-11ea-96c0-6284ef2dced0.png)


yakuake: είναι ένα τέρμιναλ, το οποίο μετακινείται στο πάνω και στο κάτω μέρος της οθόνης, πατώντας το πλήκτρο F12. Αποτελεί ένα ελαφρύ τέρμιναλ με πολλά χαρακτηριστικά και γρήγορο ευρετήριο.

### Asciinema URL: [yakuake](https://asciinema.org/a/Aed4S6XajE9Kpk4JY3N7JCLyu)
### Εικόνα του τέρμιναλ "yakuake".
![yakuake](https://user-images.githubusercontent.com/44117722/77183870-a3fcfb80-6ad7-11ea-8182-59f7714f9e1d.png)


terminology: είναι ένα τέρμιναλ, το οποίο δεν καταλαμβάνει όλη την οθόνη, μπορεί να διαμορφωθεί όσον αφορά την εμφάνιση του χρησιμοποιώντας διάφορα χρώματα και εικόνες σαν φόντο. Χαρακτηριστικό του είναι ότι δεν μπορεί να εμφανίσει άλλα αρχεία ή λίνκς και γενικότερα εφαρμογές, οποίες λειτουργούν σε άλλο γραφικό περιβάλλον.  

### Asciinema URL: [terminology](https://asciinema.org/a/FmQ6j8i9HLt1avNbnj608mFON)
### Εικόνα του τέρμιναλ "terminology".
![terminology](https://user-images.githubusercontent.com/44117722/77184148-0d7d0a00-6ad8-11ea-808d-c4abc4beb09b.png)

Στη συγκεκριμένη εργασία έγινε η εγκατάσταση και η χρήση του shell "fish" και η επίδειξη του με βίντεο μέσω του asciinema. Χρησιμοποίηθηκε για την δημιουργία ενός φακέλου με το όνομα "fish" και η δημιουργία σε αυτόν ένα αρχείο hello.py, όπου δίνει το αποτέλεσμα "hello world!!!". Τέλος, για την εγκατάσταση χρησιμοποιήθηκαν κατά σειρα οι παρακάτω εντολές:

```
 1) $ sudo apt-add-repository ppa:fish-shell/release-3
 2) $ sudo apt-get update
 3) $ sudo apt-get install fish
```
### Asciinema URL: [fish](https://asciinema.org/a/IrUR4IkvwMC1hxJRMEXvXD2NM)

Για να χρησιμοποίησει ο χρήστης το shell fish πρέπει να πατήσει την εντολή fish. Έπειτα μπορεί να βρεί αρκετές πληροφορίες όσον αφορά τις εντολές χρήσης πατώντας την ακόλουθη εντολή:

```
~> man set
```
Ένα χαρακτηριστικό του συγκεκριμένου shell είναι ότι εχει ιστορικό εντολών και παράλληλα αυτόματη συμπλήρωση εντολών, που χρησιμοποιήθηκαν στο παρελθόν. Ένα άλλο χαρακτηριστικό είναι ο αυτόματος χρωματισμός των εντολών, που γίνεται κατά την χρήση τους, όπου κόκκινο χρώμα σημαίνει λανθασμένη εντολή και μπλέ σωστή. Επιπλέον ο χρήστης μπορεί να κάνει μαθηματικές πράξεις και τέλος με τη χρήση του πλήκτρου tab και ένα αρχικό γράμμα μιας εντολής εμφανίζει όλες τις εντολές που ξεκινάνε με το ίδιο γράμμα καθώς και το τι κάνει η κάθε εντολή.

### References

[fishshell](https://launchpad.net/~fish-shell/+archive/ubuntu/release-3)
[terminals](https://linuxhint.com/best_terminal_aternatives_ubuntu/)

---

### Άσκηση 2:
Assignment: use the terminal as the IDE.

Deliverables: edit your files (e.g., cv, website, code, etc) in vim or emacs and compile it in a different panel or use a plug-in.

Αρχικά, έκανα εγκατάσταση του vim με την παρακάτω εντολή:

```
sudo apt-get install vim
```
Το επόμενο βήμα ήταν να γράψω την παρακάτω εντολή, ώστε να μπορώ να κάνω plugin μέσα στο vim:

```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim 
```

Αμέσως μέτα έκανα εγκατάσταση στον vim του Python-mode μέσω vim-plugin. Πιο συγκεκριμένα, η διαδικασία που ακολούθησα ήταν να δημιουρήσω ένα αρχείο .vimrc και μέσα σε αυτό να γράψω το εξής:

```
set number
syntax on
call plug#begin()
Plug 'Klen/Python-mode'
call plug#end()
```

Αφού γράψω τα παραπάνω πάω στο vim και εκτελώ τις εντολές PlugInstall και PlugUpdate. Τέλος, έκανα εγκατάσταση του Pylint για να βλέπω αν υπάρχουν σφάλματα και ειδοποιήσεις στον κώδικα που έγραψα. Η εγκατάσταση πραγματοποιήθηκε με την παρακάτω εντολή:

```
sudo apt-get install pylint
```

Για να πραγματοποήσω την εργασία δημιούργησα ένα αρχείο test.py όπου έγραψα "hello world!", όπως φαίνεται αναλύτικα η διαδικασία στο παρακάτω βίντεο.

### Asciinema URL: [vim-python-mode](https://asciinema.org/a/SsS37083fyhvO3iKRHHXzX5f6)


Για τον χειρισμό του vim υπάρχουν παρακάτω κάποιες εντολές:

```
press i = insert mode
press Esc = terminate insert mode
press x = delete character at cursor
press r = replace character
press dd = delete line
press :q = quit without saving
press :wq = save the file and quit
press \+r = run the code in Python-mode

```

### References

[vim-plug](https://github.com/junegunn/vim-plug)
[python-mode](https://github.com/python-mode/python-mode)

---

### Άσκηση 3:
Assignment: set-up continuous integration.

Deliverables: build and deploy your static site and your cv dynamically every time you make a small change in the source files.

Για να πραγματοποιήσω την συγκεκριμένη άσκηση χρησιμοποίησα το Github. Πιο συγκεκριμένα, δημιούργησα ένα καινούργιο repository με όνομα "Mysite", όπου στο αρχείο README.md έγραψα το βιογραφικό μου. Η διαδικασία ήταν αρχικά να κάνω "clone" το repository "Mysite" στον υπολογιστή μου με την παρακάτω εντολή, όπου στη συνέχεια με αυτό τον τρόπο μπορώ να ενημερώνω δυναμικά το σάιτ μου μέσω του τέρμιναλ:

```
 $ git clone hhtps://github.com/chris4dim/Mysite.git
```
Αφού αντέγραψα το repository τοπικά στον υπολογιστή μου, χρησιμοποίησα τις παρακάτω εντολές για να συνδεθώ στον λογαριασμό μου στο Github από το τέρμιναλ:

```
 $ git config --global user.name "username"
 $ git config --global user.email "user@hotmail.com"
```
Αφού, δημιούργησα το README.md και έγραψα το βιογραφικό μου μέσα σε αυτό χρησιμοποίησα τις παρακάτω εντολές για να ανεβάσω το αρχείο αυτό και να το ενημερώνω όταν χρειάζεται:

```
 $ git add README.md
 $ git commit -m "upload new file"
 $ git remote add origin hhtps://github.com/chris4dim/mysite.git
 $ git push origin master
```
Η διαδικασία που ακολούθησα περιγράφεται αναλυτικά παρακάτω στο βίντεο:

### Asciinema URL: [Mysite](https://asciinema.org/a/EvHuFeCiMfxwmdzAs2gAuV5xa)

Το λίνκ του σαιτ είναι το παρακάτω:

### URL: [Mysite](https://chris4dim.github.io/mysite/)

---

### Άσκηση 4:
Assignment: set-up cloud services.

Deliverables: ssh to a remote machine and demonstrate your remote cli user land (e.g., email, editor, cv, code, etc).

Για να γίνει η εγκατάσταση του SSH έγραψα αρχικά την παρακάτω εντολή:
```
 $ sudo apt-get install openssh-server
```
Για να γίνει η επιβεβαίωση ότι η εγκατάσταση ήταν επιτυχής έγραψα την παρακάτω εντολή, όπου είδα στο τέρμιναλ το μήμυμα Active: active (running):

```
 $ sudo systemctl status ssh
```

Τέλος, για την σύνδεση δύο συστημάτων χρησιμοποίησα την παρακάτω εντολή:
```
 $ ssh username@ip_address
```


### Στη συγκεκριμένη εργασία χρησιμοποίησα ένα λάπτοπ με λειτουργικό Ubuntu 16.04 και ένα Raspberry pi 4b με λειτουργικό Raspbian. Αφού  πρώτα ενεργοποίησα το ssh στο raspberry pi 4b με την εντολή sudo raspi-config, χρησιμοποίησα το username του raspberry pi 4b και την διευθυνση ip, όπως φαίνεται παρακάτω στην εικόνα.


![raspberrypi](https://user-images.githubusercontent.com/44117722/80250364-58acae80-867c-11ea-89e6-abded3812622.png)

Για να βρω την ip του raspberry pi 4b, που εμφανίζεται στην παραπάνω εικόνα χρησιμοποίησα την εντολή:
```
 $ ifconfig
```

Στη συνέχεια φαίνεται η εντολή, που χρησιμοποίησα για τη σύνδεση των δύο συστημάτων:
```
 $ ssh pi@192.168.1.13
```
Αφού λοιπόν έγινε η σύνδεση των δύο συστημάτων, από το τέρμιναλ του λειτουργικού συστήματος Ubuntu δημιούργησα το αρχείο cv, το οποίο και αποθήκευσα στο raspberry pi 4b. Όλη η διαδικασία περιγράφεται παρακάτω στο βίντεο:

### Asciinema URL: [SSH](https://asciinema.org/a/JSp6INkklEDeIr0YVYjks97fh)

Με τον ίδιο τρόπο μπορεί να δημιουργηθεί, να διαγραφεί ή και να εκτελεστεί οποιοδήποτε αρχείο επιθυμεί ο χρήστης απομακρυσμένα από άλλο υπολογιστή/laptop.

### References

[ssh](https://linuxize.com/post/how-to-enable-ssh-on-ubuntu-18-04/)

---

### Άσκηση 5:
Assignment: send notifications to your desktop-mobile.

Deliverables: send a notifcation when a big task completes, eg download, compiling, etc.

Για να γίνει η εγκατάσταση του Ntfy έγραψα την παρακάτω εντολή:

```
 $ sudo pip install ntfy
```
Το επόμενο βήμα ήταν να ενεργοποιήσω τα μηνύματα και να στέλνονται μετά την ολοκλήρωση της κάθε εργασίας. Αυτό πραγματοποιήθηκε γράφωντας την παρακάτω εντολή στο .bashrc με nano .bashrc:

```
 eval "$(ntfy shell-integration)"
```
Για να πραγματοποιήσω την εργασία κατέβασα ένα βίντεο από το youtube με τη χρήση του youtube-dl όπως φαίνεται στο παρακάτω βίντεο που έφτιαξα. Με την ολοκλήρωση του κατεβάσματος του βίντεο στάλθηκε μήνυμα ότι ολοκληρώθηκε η διεργασία του κατεβάσματος όπως φαίνεται παρακάτω.

### Ειδοποίηση ότι το βίντεο κατέβηκε επιτυχώς σε 2:26 λεπτά:
![ntfy3](https://user-images.githubusercontent.com/44117722/76169046-5ef2d400-617d-11ea-95f7-e25dab899b56.png)

### Asciinema URL: [ntfy](https://asciinema.org/a/yrLNEWHwtuYB7RuSYbHD79F6Q)

### Όταν κατέβηκε το αρχείο βίντεο εμφανίστηκε το μήνυμα πάνω από το τέρμιναλ.
![Screenshot from 2020-03-08 19-50-25](https://user-images.githubusercontent.com/44117722/76168422-6c598f80-6178-11ea-92da-c9378161fe24.png)

### References

[ntfy](https://github.com/dschep/ntfy)

---
### Άσκηση 6:
Assignment: performance monitoring.

Deliverables: monitor the performance of your python scripts and visualize them with colors and/or spark lines.

Για να γίνει η εγκατάσταση του hyperfine έγραψα τις παρακάτω εντολές στο τέρμιναλ:

```
 1) $ wget https://github.com/sharkdp/hyperfine/releases/download/v1.9.0/hyperfine_1.9.0_amd64.deb
 
 2) $ sudo dpkg -i hyperfine_1.9.0_amd64.deb
```

Για την εκπόνηση της εργασίας αυτής χρησιμοποιήθηκαν δύο python scripts, ώστε να γίνει παρακολούθηση των αρχείων αυτών κατά την εκτέλεσή τους. Πιο συγκεκριμένα, χρησιμοποιήθηκαν τα αρχεία example1.py και example2.py, όπου με την χρήση της παρακάτω εντολής βγήκαν κάποια αποτλέσμαατα όσον αφορά τον χρόνο εκτέλεσής τους (ελάχιστο, μέγιστο, μέσο χρόνο και μαζί με την τυπική απόκλιση).

```
 $ hyperfine 'pyhton3 example1.py' 'python3 example2.py'
```

### Asciinema URL: [hyperfine](https://asciinema.org/a/t3f3iOJkpGHz6ndgB68eXXf4L)

Ακόμη, υπάρχει η δυνατότητα τα αποτελέσματα να εξαχθούν σε εξωτερικό αρχείο, για παράδειγμα σε αρχείο output.csv και αυτό επιτεύχθηκε με την παρακάτω εντολή:

```
 $ hyperfine --export-csv output 'pyhton3 example1.py' 'python3 example2.py'
```
### Τα αποτελέσματα στο αρχείο output.csv
![hyperfine](https://user-images.githubusercontent.com/44117722/80254763-6a924f80-8684-11ea-8047-17bb4a235ac8.png)

### References

[Hyperfine](https://github.com/sharkdp/hyperfine)

---
### Άσκηση 7:
Assignment: create a docker image for your development stack.

Deliverables: demonstrate the custom image for CI of your cv and site.

Για να γίνει η εγκατάσταση του docker ακολούθησα τα παρακάτω βήματα κατά σειρά:

```

1) $ sudo apt-get update

2) $ sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg-agent \
    software-properties-common
    
3) $ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

4) $ sudo apt-key fingerprint 0EBFCD88

5) $ sudo add-apt-repository \
   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   $(lsb_release -cs) \
   stable"
   
6) $ sudo apt-get install docker-ce docker-ce-cli containerd.io
```

### Δημιουργία image Apache σε php με το Docker:

### Πρώτος τρόπος: χωρίς τη δημιουργία dockerfile.

 Αρχικά δημιούργησα ένα αρχείο index.php σε ένα φάκελο που τον ονόμασα docker και χρησιμοποίησα το docker για να δημιουργήσω μία εικόνα "image" του Apache σε php χρησιμοποιώντας την παρακάτω εντολή:
 
```
 
 $ docker run -d -p 80:80 --name my-apache-php-app -v "$PWD":/var/www/html php:7.2-apache
 
```

### Asciinema URL: [docker](https://asciinema.org/a/x04L5lGYnvX9QZI0Jby6ACBl0)

### Με τη δημιουργία "εικόνας" Apache στο docker, μπορούμε να παμε στον browser Mozila Firefox και γράφοντας localhost εμφανίζεται ότι γράψαμε στο αρχείο index.php:

![Screenshot from 2020-03-02 22-22-39](https://user-images.githubusercontent.com/44117722/75714499-81e03c80-5cd4-11ea-988b-7d6d2700c3c3.png)

### Δεύτερος τρόπος: με τη δημιουργία dockerfile.

Αρχικά δημιούργησα έναν φάκελο με όνομα Docker, μέσα στον οποίο δημιούργησα το Dockerfile, που περιείχε τα εξής:

```
FROM php:7.2-apache
COPY index.php /var/www/html/
```
Το επόμενο βήμα ήταν να δημιουργήσω ένα αρχειο index.php, που περιείχε το βιογραφικό μου ακριβώς ίδιο με τον πρώτο τρόπο. Αμέσως μετά εκτέλεσα τις παρακάτω εντολές:

```
$ sudo docker build -t project1 .

$ sudo docker run -d -p 8010:80 project1
```

Με τον τρόπο αυτόν δημιούργησα "εικόνα" Apache στο docker σε php, όπως με τον πρώτο τρόπο αλλά με την μόνη διαφορά η "εικόνα" αυτή τρέχει στο port 8010:80, δηλαδή εμφανίζεται στο localhost:8010 και είναι ακριβώς το ίδιο screenshot με το παραπάνω. Η διαδικασία περιγράφεται στο παρκάτω demo:

### Asciinema URL: [docker2](https://asciinema.org/a/U72NflH9e2nJIgLfpgPXKM3VI)

### Κάποιες χρήσιμες εντολές είναι οι παρακάτω:

Container που τρέχει.
```
 $ docker ps
```
Containers που τρέχουν ή είναι ανενεργά.
```
 $ docker ps -a
```
Τερματίζω ένα conatainer.
```
 $ docker stop "id"
```
Σβήνω ένα container αφού πρώτα το σταματήσω με την παραπάνω εντολή.
```
 $ docker rm "id"
```
Βλέπω όλα τα "images"
```
 $ docker images
```
Σβήνω ένα "image".
```
 $ docker rmi "id"
```

### References

[docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
[dockerhub](https://hub.docker.com/_/php)

---

### Συμμετοχικό Εκπαιδευτικό Υλικό.

### mibook URL: [mibook](https://chris4dim.netlify.com/)

### Αποθετήριο mibook: [link](https://github.com/chris4dim/gr)
### A.

Αρχικά, στα πλαίσια του συμμετοχικού εκπαιδευτικού υλικού ανέβασα μία εικόνα του raspberripi 3b όπως φαίνεται παρακάτω:

### [raspberrypi 3b](https://chris4dim.netlify.com//gallery/raspberry-pi3b-new/)
### Αποθετήριο κώδικα: [link](https://github.com/chris4dim/gr/blob/master/_gallery/raspberry-pi3b-new.md)

H δεύτερη εικόνα που ανέβασα είναι το λειτουργικό σύστημα της apple το macOS X El Capitan όπως φαίνεται και παρακάτω:

### [macOS](https://chris4dim.netlify.app/gallery/macos/)
### Αποθετήριο κώδικα: [link](https://github.com/chris4dim/gr/blob/master/_gallery/macOS.md)

### B.

Στα πλαίσια του Β συμμετοχικού ανέβασα ένα διαδραστικό παράδειγμα που αφορά ένα τέρμιναλ raspberry pi, όπου ο χρήστης προσθέτει εντολές μαζί με τη λειτουργία της κάθε μία στην html και έπειτα μπορεί να κάνει εξάσκηση πάνω σε αυτές τις εντολές, όπως φαίνεται παρακάτω:

### [terminal](https://chris4dim.netlify.com/remix/raspbian-terminal/)
### Αποθετήριο κώδικα: [link](https://github.com/chris4dim/gr/blob/master/_remix/raspbian-terminal.md)

### Γ.

Μελέτη περίπτωσης: raspberry pi 4b

### [raspberrypi4](https://chris4dim.netlify.app//case-study/rasppi4/)
### Αποθετήριο κώδικα: [link](https://github.com/chris4dim/gr/blob/master/_case-study/rasppi4.md)

---

