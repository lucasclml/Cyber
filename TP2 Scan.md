# Résumé d'analyse CodeQL

## Problème détecté
- Titre : Clear text storage of sensitive information
- Description : "Sensitive information stored without encryption or hashing can expose it to an attacker."
- Type : erreur (error)

## Détails
- Message : "This stores sensitive data returned by [[access to parameter passwd : String](relative:///VulnerableClass.cs:114:87:114:92)] as clear text."
- Fichier concerné : /VulnerableClass.cs
- Ligne : 114
- Colonne : 48 à 99
