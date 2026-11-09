# Cycling Calendar – Εκδόσεις Android / Android Releases

Αυτό το repository φιλοξενεί **μόνο τα έτοιμα αρχεία εγκατάστασης (APK)** της εφαρμογής Android του [cyclingcalendar.gr](https://cyclingcalendar.gr), του ελληνικού ημερολογίου αγώνων ποδηλασίας. Δεν περιέχει πηγαίο κώδικα.

This repository hosts **only the ready-to-install Android builds (APK)** of the [cyclingcalendar.gr](https://cyclingcalendar.gr) app, the Greek cycling race calendar. It contains no source code.

---

## 🇬🇷 Ελληνικά

### Τι είναι αυτό το repository

Η εφαρμογή Android του Cycling Calendar δεν είναι ακόμα διαθέσιμη στο Google Play. Μέχρι να ανέβει, κάθε έκδοση δημοσιεύεται εδώ ως **Release**, ώστε να μπορείς να την εγκαταστήσεις απευθείας στο κινητό σου. Ο κώδικας της εφαρμογής και του site διατηρείται σε ξεχωριστά, ιδιωτικά repositories.

### Τι κάνει η εφαρμογή

- Ημερολόγιο αγώνων ποδηλασίας στην Ελλάδα (MTB, δρόμου, CX, gravel, πίστα).
- Πλάνο σεζόν: αποθήκευση αγώνων, προτεραιότητες, καταγραφή αποτελεσμάτων και στατιστικά.
- Σελίδες αγώνων με GPX/υψομετρικό, καιρό και λεπτομέρειες.
- Είναι το cyclingcalendar.gr σε εφαρμογή. Οι σύνδεσμοι του site ανοίγουν απευθείας μέσα της.

**Άδειες:** Διαδίκτυο και τοποθεσία. Η τοποθεσία ζητείται μόνο όταν τη χρειάζεται μια λειτουργία και μπορείς να την αρνηθείς.

### Λήψη και εγκατάσταση

1. Από το κινητό σου άνοιξε το **[cyclingcalendar.gr/android](https://cyclingcalendar.gr/android)** ή πάτα απευθείας στο [`cyclingcalendar.apk` της τελευταίας έκδοσης](../../releases/latest/download/cyclingcalendar.apk).
2. Άνοιξε το αρχείο που κατέβηκε.
3. Αν ο Android ρωτήσει, επίτρεψε **«Εγκατάσταση από αυτή την πηγή»** για τον browser που χρησιμοποιείς.
4. Πάτα **Εγκατάσταση**.

Το Google Play Protect μπορεί να εμφανίσει προειδοποίηση για εφαρμογή εκτός Play Store. Είναι φυσιολογικό για κάθε εγκατάσταση APK εκτός καταστήματος.

**Απαιτήσεις:** Android 8.0 (API 26) ή νεότερο.

### Ενημερώσεις

Η εφαρμογή **δεν ενημερώνεται αυτόματα** όταν εγκαθίσταται με αυτόν τον τρόπο. Για να πάρεις νέα έκδοση, κατέβασε και άνοιξε το νεότερο APK από εδώ. Οι ρυθμίσεις και τα δεδομένα σου διατηρούνται, γιατί όλες οι εκδόσεις υπογράφονται με το ίδιο κλειδί. Οι εκδόσεις δείχνονται στη σελίδα [Releases](../../releases).

### Έλεγχος ακεραιότητας (προαιρετικό)

Κάθε release περιλαμβάνει το SHA-256 του αρχείου στις σημειώσεις του. Για να το ελέγξεις σε υπολογιστή:

```bash
sha256sum cyclingcalendar.apk        # Linux
shasum -a 256 cyclingcalendar.apk    # macOS
Get-FileHash cyclingcalendar.apk     # Windows PowerShell
```

Το αποτέλεσμα πρέπει να ταυτίζεται με αυτό των σημειώσεων της έκδοσης.

Για να ελέγξεις ποιος έχει υπογράψει το APK (με `apksigner` από το Android SDK):

```bash
apksigner verify --print-certs cyclingcalendar.apk
```

Το πιστοποιητικό υπογραφής των επίσημων εκδόσεων έχει SHA-256:

```
97:A2:24:3C:02:E9:F6:BF:8E:42:90:53:EB:E8:70:45:36:4B:74:4C:AA:CA:BE:7F:B6:A7:24:38:57:05:74:30
```

> Αν το αποτύπωμα δεν ταυτίζεται, μην εγκαταστήσεις το αρχείο.

### Προβλήματα και σχόλια

- Επικοινωνία: μέσω της φόρμας στο [cyclingcalendar.gr](https://cyclingcalendar.gr) (Επικοινωνία).
- Για θέματα εγκατάστασης ή σφάλματα της εφαρμογής μπορείς να ανοίξεις ένα [Issue](../../issues) εδώ, με το μοντέλο κινητού και την έκδοση Android.

### Πολιτική απορρήτου και όροι

Ισχύουν οι ίδιοι όροι με το site: [cyclingcalendar.gr](https://cyclingcalendar.gr) (Πολιτική Απορρήτου, Όροι Χρήσης).

---

## 🇬🇧 English

### What this repository is

The Cycling Calendar Android app is not yet on Google Play. Until it is, each version is published here as a **Release** so you can install it directly on your phone. The app and website source code live in separate private repositories.

### What the app does

- Calendar of cycling races in Greece (MTB, road, CX, gravel, track).
- Season planning: save races, set priorities, log results, view statistics.
- Race pages with GPX/elevation, weather and details.
- It is cyclingcalendar.gr as an app, and the site's links open inside it.

**Permissions:** Internet and location. Location is requested only when a feature needs it and you can deny it.

### Download and install

1. On your phone, open **[cyclingcalendar.gr/android](https://cyclingcalendar.gr/android)** or tap [`cyclingcalendar.apk` from the latest release](../../releases/latest/download/cyclingcalendar.apk).
2. Open the downloaded file.
3. If Android asks, allow **“Install from this source”** for the browser you used.
4. Tap **Install**.

Google Play Protect may warn about an app from outside the Play Store. That is expected for any sideloaded APK.

**Requires:** Android 8.0 (API 26) or newer.

### Updates

An app installed this way **does not update itself**. To upgrade, download and open the newest APK from here. Your settings and data are kept because every release is signed with the same key. All versions are listed on the [Releases](../../releases) page.

### Verifying the download (optional)

Each release lists the file's SHA-256 in its notes. On a computer:

```bash
sha256sum cyclingcalendar.apk        # Linux
shasum -a 256 cyclingcalendar.apk    # macOS
Get-FileHash cyclingcalendar.apk     # Windows PowerShell
```

The result must match the release notes. To check who signed the APK (using `apksigner` from the Android SDK):

```bash
apksigner verify --print-certs cyclingcalendar.apk
```

Official releases are signed with a certificate whose SHA-256 fingerprint is:

```
97:A2:24:3C:02:E9:F6:BF:8E:42:90:53:EB:E8:70:45:36:4B:74:4C:AA:CA:BE:7F:B6:A7:24:38:57:05:74:30
```

> If the fingerprint does not match, do not install the file.

### Issues and feedback

- Contact: use the form on [cyclingcalendar.gr](https://cyclingcalendar.gr) (Contact).
- For installation problems or app bugs, open an [Issue](../../issues) here with your phone model and Android version.

### Privacy and terms

The same terms as the website apply: [cyclingcalendar.gr](https://cyclingcalendar.gr) (Privacy Policy, Terms of Service).

---

## Για τον maintainer / Maintainer notes

Κάθε release πρέπει να:

- Έχει tag `vX.Y.Z` (ίδιο με το `versionName` της εφαρμογής).
- Περιέχει **ένα** asset με το σταθερό όνομα **`cyclingcalendar.apk`**. Από αυτό το όνομα εξαρτάται ο σύνδεσμος `/releases/latest/download/cyclingcalendar.apk` και το redirect `cyclingcalendar.gr/download/android`.
- Έχει στις σημειώσεις το SHA-256 του APK και τις αλλαγές.
- Είναι υπογεγραμμένο με το ίδιο release keystore, αλλιώς οι χρήστες δεν θα μπορούν να κάνουν update πάνω στην υπάρχουσα εγκατάσταση.

```bash
gh release create vX.Y.Z cyclingcalendar.apk \
  --repo d3codedvision/cyclingcalendar-releases \
  --title "vX.Y.Z" --notes-file notes.md
```
