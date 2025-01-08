# Bejelentkezés az oldalra

Az oldal adminjaként

szeretném bejelentkeztetni az oldalra a felhasználókat,

hogy csak azok tudják használni a webalkalmazást, akik regisztrálva vannak.

## Elfogadási kritériumok

### Bejelentkezés hiteles adatokkal

**Adott**, hogy van egy regisztrált fiókunk.

**Ha** a bejelentkezésnél megadjuk a helyes felhasználónév-jelszó párost,

és a 'bejelentkezés' gombra kattintunk,

**akkor** elfogadja az alkalmazás a bejelentkezésünket,

és továbbit az alkalmazás a főoldalra,

és amig bejelentkezve maradunk, addig nem tudunk visszalépni a bejelentkező oldalra.

### Bejelentkezés hibás adatokkal

**Adott**, hogy van egy regisztrált fiókunk.

**Ha** a bejelentkezésnél megadjuk a helyes felhasználónevet, és egy hibás jelszót,

vagy a bejelentkezésnél megadunk egy hibás felhasználónevet, és a helyes jelszót,

vagy a bejelentkezésnél hibás felhasználónevet és hibás jelszót adunk meg,

és a 'bejelentkezés' gombra kattintunk,

**akkor** elutasitja az alkalmazás a bejelentkezést, hibaüzenetet kapunk,

és a bejelentkező oldalon maradunk.

### 'Bejelentkezve marad' gomb bepipálása, majd bejelentkezés

**Adott**, hogy van egy regisztrált fiókunk.

**Ha** a bejelentkezésnél megadjuk a helyes felhasználónév-jelszó párost,

és bepipáljuk a 'Bejelentkezve marad' gombot,

és a 'bejelentkezés' gombra kattintunk,

**akkor** sikeres lesz a bejelentkezés,

és addig bejelentkezve maradunk, amig nem használjuk a kijelentkezés gombot.