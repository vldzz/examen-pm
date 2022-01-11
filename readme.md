##### Creați un repozitoriu pe Desktop cu denumirea numele, prenumele și grupa voastră (ex.: Carp Alex P-1641) și poziționați-vă în el.

```
git init 'Vlad Stici B-1842'
cd 'Vlad Stici B-1842'/
```

![](/screens/screen1.png)


##### Definiți un branch cu denumirea Examen si treceți la el. 

```
git checkout -b Examen
```

![](/screens/screen2.png)

###### Definiți un fișier cu denumirea Numele vostru și extensia .txt și unul în word cu denumirea prenumele vostru. Adăugați primul fișier la repozitoriu prin adăugarea fișierelor cu o extensie anumită, iar al doilea prin definirea denumirii.
```
touch Vlad.txt
touch Stici.docx
git add *.txt
git add Stici.docx
```

![](/screens/screen3.png)


##### Arătați statutul repozitoriului
```
git status
```

![](/screens/screen4.png)



##### Faceți un commit cu mesajul Grupa, Nume, prenume, data și unul cu mesajul denumirea disciplinei la care aveți examen
```
git commit -m "B-1842 Stici Vlad 11.01.2022"
git add *
git commit -m "Project Management"
```

![](/screens/screen5.png)


##### Afișați log-urile.
![](/screens/screen6.png)
