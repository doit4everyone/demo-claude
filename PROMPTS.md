# 🤖 AI Orchestration — Master Prompts

This document lists the core prompts used to generate the **Pre-Sales SSI Pack**. To maintain technical credibility, the initial prompt is presented exactly as it was written.

## 📝 Prompt #1: Core Architecture & SSI Framework

> "Crée-moi une architecture ms365 avec comme nom de domaine demo.ch pour 15 utilisateurs avec des postes locaux (sur site) et une solution de sauvegarde veeam hébergée en local avec backup complète sur site (sur disque et sur bandes) et une copie immuable dans azure. 
> 
> Esr et Known Folder Move devront être activé. Je dois avoir defender plan 1 configuré et de la compliance pour les dossiers RH et Finances et Direction afin d'être en règle avec la NLPD Suisse. 
> 
> Il aura 3 utilisateurs Directions dans un groupe, 2 utilisateurs RH dans un groupe, 2 utilisateurs Finances dans un groupe et les 8 utilisateurs restant comme utilisateurs standards. Le groupe Direction doit avoir accès aux répertoires RH et Finances. 
> 
> Il faut aussi un site Hub Site sharepoint, un Site de communication, un site pour Direction, un site pour RH, un site pour Finances. J'ai deux imprimantes multifonctions sur site qui doivent pouvoir envoyer des fichiers par mail à tous les utilisateurs. 
> 
> Pour les sauvegardes LTO sur site il faudra un GFS annuel, un GFS mensuel, un GFS hebdomadaire et un incrémentiel le lundi, le mardi, le mercredi et le jeudi. Il faudra aussi une sauvegarde de la configuration du serveur veeam dans azure et sur les bandes. Il faut aussi une stratégie de sauvegarde pour les clés LTO. 
> 
> Il faut intégrer dans l'estimation du cout 3 pc portables pour la direction et 12 pc fixes pour les autres utilisateurs et les deux imprimantes multifonction (HP par exemple) Fait une estimation du cout initial et annuel du projet pour la Suisse, j'ai déjà le nom de domaine et mon DNS est chez Zoneedit."

---

## ⚙️ Iterations & Refinements

Following this initial generation, two additional prompts were used to separate the **Technical Implementation Guide** for technicians and the **User Training Guide** for end-users. 

Approx. 4 technical iterations were performed to refine the **Purview DLP rules** (Swiss AVS/IBAN) and the **LTO GFS rotation schedules**.
