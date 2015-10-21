# CI_pattern `ver 1.0`
*Requires [CodeIgniter](http://www.codeigniter.com/)*

Blog with CMS build with CodeIgniter 2.2.5 (ver. 2)

**1. Powiazanie serwera WWW z GitHub'em**

* Tworzysz nowe repo;
* W terminalu laczysz utworzone wczesniej repo z serwerem WWW:

```
  $ git init [ENTER]
  $ git remote add origin https://github.com/daru79/CI_pattern.git [ENTER]
```

* Za pomoca FTP przegrywasz pliki na serwer WWW
* Przegrane pliki dodajesz do powiazanego repo z pkt. 2:

```
  $ git add -A [ENTER]
  $ git commit -m "tekst komentarza" [ENTER]
  $ git push -u origin master [ENTER]
```
