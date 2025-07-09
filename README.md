# 🌧️ Rainfall – Projet d’Exploitation Binaire (École 42)

Projet de groupe réalisé avec [Malo Lefort](https://github.com/Malolfrt)

## 📌 Description

**Rainfall** est un projet de cybersécurité avancé proposé par l’école 42. Il consiste à exploiter une série de binaires vulnérables sur une machine Linux, chaque binaire représentant un niveau. Le but est d'exploiter les failles présentes dans ces exécutables pour obtenir le mot de passe de l'utilisateur suivant, jusqu'au niveau final.

Le projet met en pratique des notions de **reverse engineering**, de **buffer overflow**, de **gestion mémoire** et d’**exploitation de failles système**.

---

## 🎯 Objectifs pédagogiques

- Comprendre et manipuler la mémoire (pile, segments, pointeurs).
- Apprendre les bases du reverse engineering avec des outils comme `gdb`, `objdump`, `ltrace`, etc.
- Identifier et exploiter des failles binaires classiques : buffer overflow, format string, injection de shellcode, etc.
- Renforcer la rigueur et la précision dans l’analyse bas niveau.

---

## 🛠️ Environnement

- Accès SSH à une machine Linux distante
- 14 niveaux à résoudre (niveau0 → bonus3)
- Un binaire vulnérable par niveau
- Aucun accès root
- Utilisation exclusive du terminal

---

## 🔧 Outils utilisés

- `gdb`
- `objdump`, `strings`
- `ltrace`
- `python` pour générer des payloads
- `netcat` pour la communication réseau si besoin

---

---

## 📚 Ressources utiles

- [GDB Cheat Sheet](https://darkdust.net/files/GDB%20Cheat%20Sheet.pdf)
- [Buffer Overflow 101](https://exploit.education/)
- [Ghidra](https://dogbolt.org/)
- [HackTricks – Binary Exploitation](https://book.hacktricks.xyz/)

---

## 👨‍💻 Auteur

Projet réalisé dans le cadre du cursus cybersécurité de l’[École 42](https://42.fr/).
