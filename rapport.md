## Nom et prénom: 
KHADIRA Oumaima

## l'adresse du dépôt github
https://github.com/oumakdr/Chasse_au_tresor-Khadira

## les commandes tapées pour répondre aux questions:

### indice 1
ls
cd tresor_shell
ls
./generer_probleme.py 45537
cd indices/12345
ls
cat indice

### indice 2
pwd
cd /
ls


### indice 3 
cd /usr
ls -1A | wc -l
./indice_suivant.py 3 9 
cd indices/44265
cat indice


### indice 4 
cat hostname
./indice_suivant.py 4 LAPTOP-K50HC1SL
cd indices/79024
cat indice


### indice 5 
cd ~tresor_shell
mkdir indices-sauvés
cp indices/12345/indice indices-sauvés/indice2
cp indices/44265/indice indices-sauvés/indice3
cp indices/79024/indice indices-sauvés/indice4
ls -lahS
mv indices-sauvés indices-trouvés
ls
./indice_suivant.py 5 -u
cd indices/39055
cat indice
cp indices/39055/indice indices-trouvés/indice5


### indice6
echo coucou
echo "Ça fait 14 jours que je suis enfermé, j'suis seul" > cuisine.txt
ls > mon_répertoire.txt
echo $HOME
echo $PATH
./indice_suivant.py 6 /mnt/c/MinGW/bin
cd indices/27350
cat indice
cp indices/27350/indice indices-trouvés/indice6


### indice 7
tail -f /var/adm/messages
tail -n5 pingouin.jpg
./indice_suivant.py 7 détruitsécroulésennuinom
cd indices/64206
cat indice
cp indices/64206/indice indices-trouvés/indice7

### indice 8
sudo apt install ispell
vi toutpuissant.txt
(j'ai écrit "je veux utiliser sudo. OK"dans la commande vi)
sudo mv toutpuissant.txt/usr/local
./indice_suivant.py 8 OK
cd indices/46859
cat indice
cp indices/46859/indice indices-trouvés/indice8

### indice 9
cd /usr/share/dict/
ls
wc -w words
./indice_suivant.py 9 102401
cd indices/102401
cat indice
cp indices/102401/indice indices-trouvés/indice9

### indice 10
grep secret README.md
grep m.n README.md
grep -B1 'tomcat' words
cd ~/tresor_shell/
./indice_suivant.py 10 tombstones
cd indices/89201
cat indice
cp indices/89201/indice indices-trouvés/indice10

### indice 11
ls | wc -w
grep ^sand /usr/share/dict/words | wc -l
sort -R /usr/share/dict/words > random_words
ls -la/bin > random_ls
sort -k5 -rn random_ls
./indice_suivant.py 11 -k5 -nr
cd indices/56880
cat indice
cp indices/56880/indice indices-trouvés/indice11
