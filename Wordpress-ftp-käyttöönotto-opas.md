# 📘 FTP ja WordPress – Käyttöönotto-opas

Tämä opas näyttää vaihe vaiheelta, miten otat käyttöön FTP-yhteyden ja asennat WordPressin web-palvelimelle.

---

## ✅ 1. FTP-yhteyden muodostaminen

### Tarvitset:
- FTP-osoitteen (esim. ftp.omadomain.fi)
- Käyttäjätunnuksen ja salasanan
- FTP-ohjelman (esim. FileZilla)

### 🔧 FileZilla – asetukset
1. Avaa FileZilla
2. Siirry kohtaan **File → Site Manager**
3. Lisää uusi sivu:
   - **Host:** ftp.omadomain.fi  
   - **Protocol:** FTP  
   - **Encryption:** Require explicit FTP over TLS  
   - **Logon type:** Normal  
   - **Username:** (palveluntarjoajan antama)  
   - **Password:** (salasana)  
4. Klikkaa **Connect**

![FTP-yhteys](images/ftp-setup.png)

---

## ✅ 2. WordPress-paketin lataaminen

1. Siirry osoitteeseen:  
   https://wordpress.org/download/
2. Lataa viimeisin WordPress‑zip‑paketti
3. Pura zip-tiedosto tietokoneellasi

---

## ✅ 3. WordPress-tiedostojen siirto palvelimelle

1. Yhdistä FTP:llä palvelimeen
2. Avaa palvelimen **public_html** tai **www** -kansio
3. Siirrä kaikki puretut WordPress‑tiedostot palvelimelle

> ⚠️ Siirtäminen voi kestää muutaman minuutin.

---

## ✅ 4. Tietokannan luonti

Useimmat palveluntarjoajat käyttävät cPanelia tai Pleskiä.

### Esimerkki: cPanel
1. Mene **MySQL Databases**
2. Luo uusi tietokanta
3. Luo uusi käyttäjä ja salasana
4. Lisää käyttäjä tietokantaan ja anna **All Privileges**

---

## ✅ 5. WordPress-asennuksen viimeistely

Kun tiedostot ovat palvelimella, avaa selaimessa domain: https://www.omadomain.fi

Sinun pitäisi nähdä WordPressin asennusohjelma.

Täytä:
- tietokannan nimi  
- tietokannan käyttäjä  
- tietokannan salasana  
- tietokantapalvelin (yleensä `localhost`)  

Paina **Install WordPress**.

---

## ✅ 6. Kirjautuminen WordPressiin

WordPressin hallinta löytyy osoitteesta: https://www.omadomain.fi/wp-admin

---

## ✅ 7. Yhteenveto

Tässä opastuksessa teit:
✅ FTP-yhteyden  
✅ WordPressin tiedostojen siirron  
✅ Tietokannan  
✅ WordPressin asennuksen  

---

## 📩 Ota yhteyttä
Jos tarvitset apua asennukseen, optimointiin tai verkkosivujen toteutukseen:

**sipinen@gmail.fi**
