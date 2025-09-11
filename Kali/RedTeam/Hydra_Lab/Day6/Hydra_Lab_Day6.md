#  Hydra Brute Force Lab – Kali Linux

##  Περιγραφή
Αυτός ο φάκελος περιέχει ασκήσεις brute force επιθέσεων σε login φόρμες μέσω του εργαλείου **Hydra**, χρησιμοποιώντας Kali Linux.

Οι επιθέσεις πραγματοποιήθηκαν σε ελεγχόμενο εργαστηριακό περιβάλλον (localhost ή mobile device) και σκοπός είναι η εξάσκηση στις τεχνικές password guessing και form-based enumeration.

---

##  Εργαλεία & Τεχνικές
- Kali Linux (VirtualBox VM)
- Nmap (για service enumeration)
- Hydra (`http-post-form` module)
- Simple HTTP Server (μέσω Android)
- Custom wordlists (`users.txt`, `pass.txt`)
- Wireshark (προαιρετικά για παρακολούθηση traffic)

---

## 🗂 Περιεχόμενα
- `Day6/`  
  ➤ Πλήρης διαδικασία επίθεσης σε login form μέσω HTTP  
  ➤ Includes screenshots, `Hydra` command, reports, wordlists

---

##  Status
- [x] Kali συνδεδεμένο μέσω Ethernet
- [x] Target host reachable (ping successful)
- [x] Nmap scan ολοκληρωμένο
- [x] Hydra επίθεση επιτυχής (`admin : 1234`)
- [x] Αρχεία καταγραφής και αναφορά (`.md`) έτοιμα

---

##  Σκοπός
Η κατανόηση του τρόπου λειτουργίας brute-force επιθέσεων σε web login συστήματα και η ορθή εφαρμογή εργαλείων όπως το Hydra στο πλαίσιο ηθικού hacking / penetration testing.

---

## ⚠Disclaimer
Όλες οι δοκιμές έγιναν σε **εικονικά περιβάλλοντα και προσωπικές συσκευές με άδεια χρήσης**.  
Απαγορεύεται η χρήση των τεχνικών αυτών σε μη εξουσιοδοτημένα συστήματα.
