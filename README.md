# CI_pattern
Blog with CMS build with CodeIgniter 2.2.5 (ver. 2)

# I. Powiazanie serwera WWW z GitHub'em
1. Tworzysz nowe repo;
2. W terminalu laczysz utworzone wczesniej repo z serwerem WWW:
```
  $ git init [ENTER]
  $ git remote add origin https://github.com/daru79/CI_pattern.git [ENTER]
```
3. Za pomoca FTP przegrywasz pliki na serwer WWW
4. Przegrane pliki dodajesz do powiazanego repo z pkt. 2:
```
  $ git add -A [ENTER]
  $ git commit -m "tekst komentarza" [ENTER]
  $ git push -u origin master [ENTER]
```
