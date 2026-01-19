🔐 Cryptography Lab — Java, BouncyCastle, ASN.1, AES, PBKDF2, DPAPI
Ce projet est un laboratoire pédagogique en cryptographie appliquée, développé en Java.
Il explore plusieurs mécanismes cryptographiques utilisés dans les systèmes modernes, notamment :

les structures ASN.1 / DER

la dérivation de clés (PBKDF2‑HMAC‑SHA256)

le chiffrement symétrique (AES, 3DES, CBC, GCM)

la gestion d’IV, de padding et de formats binaires

l’utilisation de BouncyCastle et JNA

l’interaction avec DPAPI (Windows Data Protection API)

la manipulation de bases SQLite

la création d’une interface graphique Java Swing

L’objectif du projet est d’apprendre, d’expérimenter et de comprendre comment les systèmes réels structurent, protègent et manipulent des données chiffrées.

🎯 Objectifs pédagogiques
Comprendre les formats cryptographiques utilisés dans les systèmes modernes (ASN.1, DER).

Manipuler des clés, IV, algorithmes de chiffrement et dérivation.

Explorer les mécanismes de protection locaux (DPAPI).

Lire et analyser des structures binaires complexes.

Développer une interface graphique pour visualiser les résultats.

Approfondir l’utilisation de bibliothèques cryptographiques avancées (BouncyCastle).

🧱 Architecture du projet
Code
📦 cryptography
 ┣ 📂 montest
 ┃ ┣ DATA_BLOB.java
 ┃ ┣ DecryptedData.java
 ┃ ┣ InterfaceAffichage.java
 ┃ ┣ modules cryptographiques (AES, 3DES, PBKDF2, ASN.1)
 ┃ ┗ utilitaires JNA / BouncyCastle
 ┣ README.md
 ┗ ressources
🧰 Technologies utilisées
Java 8+

BouncyCastle (ASN.1, PBKDF2, SHA‑256)

JNA (interopérabilité Windows)

SQLite JDBC

Java Swing

Base64, DER, CBC, GCM

🧠 Concepts cryptographiques étudiés
✔ Dérivation de clés
PBKDF2‑HMAC‑SHA256

SHA‑1 / SHA‑256 digest

Gestion de salt et iteration count

✔ Chiffrement symétrique
AES‑256‑CBC

AES‑GCM

3DES‑CBC

Padding PKCS#5

✔ Structures ASN.1
Lecture

Décodage DER

Parcours récursif

Extraction de champs

✔ DPAPI (Windows)
Utilisation via JNA

Structures DATA_BLOB

Déchiffrement local protégé

✔ SQLite
Lecture de bases locales

Analyse de données structurées

🖥 Interface graphique
Le projet inclut une interface Swing permettant :

de sélectionner un module d’analyse

d’afficher les données traitées

de visualiser les résultats dans une liste déroulante

Cette interface sert de support pédagogique pour comprendre les transformations cryptographiques.

🚀 Améliorations possibles
Ajout d’un module de génération de clés

Visualisation graphique des structures ASN.1

Ajout de tests unitaires JUnit

Migration vers JavaFX

Documentation détaillée des algorithmes

👤 Auteur
Rhodian Japha Ndamen Fomen  
Développeur logiciel — passionné par la cryptographie, les systèmes et la sécurité applicative.
