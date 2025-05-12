# 🔐 Authentification vs Autorisation en Cybersécurité

En cybersécurité, **l’authentification** et **l’autorisation** sont deux concepts fondamentaux mais bien distincts. Ce dépôt a pour objectif de clarifier leur signification, leurs différences et leurs rôles respectifs.

---

## 🧾 1. Authentification (Authentication)

**Définition :**  
L’authentification est le processus de **vérification de l’identité** d’un utilisateur ou d’un système.

**🎯 Objectif :**  
S’assurer que la personne ou le système est bien **celui qu’il prétend être**.

**🔍 Exemples :**
- Entrer un nom d’utilisateur et un mot de passe
- Utiliser une empreinte digitale ou la reconnaissance faciale
- Recevoir un code par SMS (authentification à deux facteurs)

**❓ Question posée :**  
> **Qui es-tu ?**

---

## 🛂 2. Autorisation (Authorization)

**Définition :**  
L’autorisation est le processus qui détermine **ce qu’un utilisateur peut faire** après avoir été authentifié.

**🎯 Objectif :**  
Définir les **droits d’accès** et les **ressources disponibles** à l’utilisateur.

**🔍 Exemples :**
- Un utilisateur peut lire un fichier, mais pas le modifier
- Un administrateur peut accéder à tous les paramètres du système, un simple utilisateur non

**❓ Question posée :**  
> **Que peux-tu faire ?**

---

## 🧩 Résumé visuel

| **Concept**         | **Authentification**            | **Autorisation**                     |
|---------------------|----------------------------------|--------------------------------------|
| **But**             | Vérifier l'identité              | Donner les droits d'accès            |
| **Moment**          | Avant l’accès                    | Après l’accès                        |
| **Exemples**        | Mot de passe, biométrie          | Lire, écrire, modifier, accéder      |
| **Question posée**  | Qui es-tu ?                      | Que peux-tu faire ?                  |

---

## 📌 Remarque

Ces deux processus sont souvent combinés dans un système sécurisé, mais **ils ne sont pas interchangeables**. Il est crucial de bien comprendre cette distinction pour concevoir des systèmes robustes.

---

