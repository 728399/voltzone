# VoltZone — Magazin Online de Electronice
> Proiect realizat pentru materia Comert Electronic

Un magazin online mobile-first de electronice si gadgeturi, construit cu HTML, CSS si JavaScript vanilla, fara framework-uri sau librarii externe.

## Pagini (6 pagini)

- **Acasa (Home)** — hero section cu gradient, produse featured, categorii, banner promotie cu timer countdown, newsletter
- **Produse (Products)** — catalog complet cu 24 de produse, filtrare pe categorii (telefoane, audio, laptopuri, gaming, wearables, camere)
- **Despre noi (About)** — povestea magazinului, valorile companiei, echipa
- **Blog** — articole si ghiduri despre tehnologie
- **Contact** — formular de contact, date de contact
- **Termeni si Conditii** — politica de plata, retur, livrare, GDPR

## Functionalitati

- Design mobile-first, responsive pe toate dispozitivele
- Cos de cumparaturi functional (adaugare, stergere, modificare cantitate)
- Filtrare produse pe categorii
- Timer countdown pentru flash sale
- Wishlist (adaugare la favorite)
- Formular de newsletter si contact
- Imagini reale preluate si prelucrate (Unsplash)

## Simulare gateway de plata

La finalizarea comenzii, utilizatorul trece printr-un flux complet de plata simulat:

1. **Fereastra de checkout** — afiseaza totalul comenzii si produsele selectate
2. **Selectare metoda de plata** — Card bancar, PayPal, Apple Pay, Google Pay
3. **Formular card** — introducere date card cu formatare automata (numar card, data expirare, CVV)
4. **Procesare** — animatie de incarcare (2.5 secunde) care simuleaza comunicarea cu procesatorul de plati
5. **Confirmare** — ecran de succes cu numar de comanda unic generat (ex: #VZ-483921)

> Nota: Platile sunt simulate. Nu se proceseaza bani reali si nu se stocheaza date bancare.

## Monetizare

**One-time payments** — modelul de monetizare ales este plata unica per comanda, similar cu orice magazin online clasic (WooCommerce, Shopify etc.). Fiecare produs are un pret fix, clientul plateste o singura data si primeste produsul.

## Imagini prelucrate

Site-ul utilizeaza minim 5 imagini prelucrate din surse libere de drepturi (Unsplash), integrate in:
- Carduri de produs (24 produse cu imagini individuale)
- Sectiunea hero (imagine principala + miniaturi)
- Sectiunea About (grid de imagini)
- Articolele de blog

## Stiva tehnologica

HTML5 · CSS3 · JavaScript (vanilla, fara framework-uri)

## Cum se ruleaza

Deschide fisierul `index.html` in orice browser modern. Nu necesita instalare, server sau conexiune speciala.

## Structura fisiere

```
index.html   — intregul site (single-file application)
README.md    — documentatia proiectului
```
