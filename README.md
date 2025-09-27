# 🛒 Flutter Groceries

Un'app Flutter per gestire la lista della spesa in modo semplice ed efficace, con persistenza dei dati tramite **Firebase Realtime Database**.  
Permette di **aggiungere**, **visualizzare** e **rimuovere** elementi, organizzati per categoria, con una UI moderna in tema scuro.

---

## Funzionalità
- Visualizzazione della lista della spesa con categorie colorate.
- Aggiunta di nuovi prodotti con **nome**, **quantità** e **categoria**.
- Eliminazione degli elementi tramite **swipe**.
- Salvataggio e recupero dati da **Firebase Realtime Database**.
- Gestione di stati di caricamento ed errori.

---

## 📂 Struttura del progetto

- **main.dart** → Entry point dell'app e configurazione del tema.  
- **widgets/grocery_list.dart** → Lista degli elementi con caricamento e rimozione da Firebase.  
- **widgets/new_item.dart** → Form per aggiungere nuovi prodotti.  
- **data/categories.dart** → Definizione delle categorie predefinite con colori.  
- **models/category.dart** → Modello `Category` e enum `Categories`.  
- **models/grocery_item.dart** → Modello `GroceryItem` per i singoli elementi.  

---

## Tecnologie utilizzate
- **Flutter** (Dart)
- **Material Design**
- **Firebase Realtime Database**
- **HTTP package** per comunicazione REST

---

## Avvio del progetto
1. Clona la repository  
   ```bash
   git clone https://github.com/BrambillaMarco/flutter-shopping-list-app.git

2. Entra nella cartella del progetto
cd flutter-shopping-list-app

3. Installa le dipendenze
flutter pub get

4. Avvia l'app
flutter run

---

## Screenshots

<img width="271" height="593" alt="1" src="https://github.com/user-attachments/assets/87184f0b-3fcb-4cac-8286-8a0258ecd5b1" />

<img width="266" height="588" alt="2" src="https://github.com/user-attachments/assets/fdda4ba1-027b-4218-bd95-51fa48f3d121" />

---

## Cosa ho imparato
Grazie a questo progetto ho approfondito:

La gestione dello stato in Flutter con StatefulWidget.

L'uso delle Future e async/await per chiamate HTTP.

L'integrazione di Firebase Realtime Database in un'app Flutter.

La gestione degli errori e loading state.

L'uso di Form e validazioni con TextFormField e DropdownButtonFormField.

Il concetto di Dismissible widget per eliminare elementi con swipe.
