# Application Android pour CPE — Recherche des besoins, obligations et informations à traiter

> **Note de cadrage** : Les obligations et règles varient selon la juridiction (p. ex. Québec, France, etc.). Cette recherche fournit une **base fonctionnelle et documentaire** à valider localement (ministère, règlements régionaux, conventions collectives, et politiques internes).

## 1) Objectifs de l’application
- Centraliser les opérations d’un CPE (administration, pédagogie, santé/sécurité, RH, communication).  
- Réduire la charge administrative et améliorer la traçabilité (présences, incidents, facturation).  
- Assurer la conformité (dossiers, registres, rapports, consentements).  
- Donner aux parents et au personnel une interface claire et sécurisée.  

## 2) Profils utilisateurs et besoins principaux
### Direction / Administration
- Vue globale : tableaux de bord, conformité, KPI.  
- Gestion des inscriptions, listes d’attente, contrats.  
- Gestion financière : subventions, paiements, reçus, facturation.  
- Registres obligatoires et rapports à produire.  

### Éducatrices / Personnel pédagogique
- Présences quotidiennes (arrivée/départ).  
- Planification pédagogique et activités.  
- Observations et suivis de développement.  
- Journal de bord : sieste, repas, incidents, comportements.  

### Parents / Tuteurs
- Communication bidirectionnelle et avis.  
- Calendrier, événements, horaires.  
- Suivi quotidien (repas, sieste, activités).  
- Facturation et reçus.  

### Personnel santé/sécurité (si applicable)
- Gestion des allergies et médicaments.  
- Protocoles d’urgence et incidents.  
- Registre des accidents/observations.  

## 3) Informations essentielles à traiter
### Dossiers des enfants
- Identité, contacts, langue(s).  
- Autorisations : sorties, photos, transport.  
- Informations médicales : allergies, conditions, médicaments.  
- Contact d’urgence et autorisations de garde.  

### Dossiers des parents/tuteurs
- Coordonnées, consentements, modalités de paiement.  
- Autorisations de communication (email/SMS).  

### Dossiers du personnel
- Coordonnées, qualifications, certifications (premiers soins).  
- Horaires, feuilles de temps, congés.  

### Registres & journaux
- Présences quotidiennes.  
- Accidents/incidents (avec horodatage, signatures).  
- Administration de médicaments.  
- Entretien/sécurité (inspections, tests, maintenance).  

### Finance & facturation
- Tarifs, subventions, aides financières.  
- Factures, paiements, reçus fiscaux.  
- Historique de paiement, soldes.  

### Pédagogie
- Planifications hebdomadaires.  
- Activités par groupe.  
- Observations et notes éducatives.  

## 4) Obligations fréquentes (à valider localement)
> **À confirmer selon la juridiction.**
- Tenue de **registres de présence** exacts (enfants et personnel).  
- **Registre des incidents** et déclarations d’accidents.  
- **Consentements** parents (photos, sorties, soins).  
- **Protocoles d’urgence** et affichage des procédures.  
- **Dossiers médicaux** à jour (allergies, médicaments).  
- **Qualifications/Certifications** du personnel (premiers soins, vérification d’antécédents).  
- **Politiques de confidentialité** et gestion des données personnelles (RGPD/lois locales).  
- **Respect des ratios** éducatrice/enfant et capacité autorisée.  
- Conservation et archivage de documents (durées légales).  

## 5) Conformité et sécurité des données
- **Gestion des accès** par rôle (direction, personnel, parents).  
- **Historique d’audit** (qui a modifié quoi et quand).  
- **Chiffrement** des données sensibles (au repos et en transit).  
- **Sauvegardes** et plan de reprise.  
- **Consentement explicite** pour notifications, photos, communications.  

## 6) Modules clés de l’application (design fonctionnel)
### A) Tableau de bord (direction)
- KPIs : taux d’occupation, incidents, retards de paiement.  
- Alertes : documents expirés, allergies, formations à renouveler.  

### B) Gestion des inscriptions
- Formulaires d’inscription digitalisés.  
- Liste d’attente, priorités, suivi.  
- Contrats numériques (signature).  

### C) Présences & horaires
- Arrivée/départ avec signature parentale.  
- Feuilles de temps du personnel.  
- Rapport de conformité des ratios.  

### D) Santé & sécurité
- Registre des allergies et plans d’intervention.  
- Administration des médicaments (horaires, signatures).  
- Déclaration d’accidents/incidents avec photos.  

### E) Communication
- Messagerie sécurisée.  
- Notifications push (urgent, info, routine).  
- Calendrier partagé.  

### F) Pédagogie
- Planification d’activités.  
- Notes d’observation et suivi du développement.  
- Rapport périodique pour les parents.  

### G) Facturation
- Factures automatiques mensuelles.  
- Paiement en ligne, reçus.  
- Aides/subventions applicables.  

### H) Rapports & conformité
- Export PDF/CSV des registres obligatoires.  
- Archivage automatique.  

## 7) Écrans proposés (design complet de l’app)
1. **Onboarding & choix de rôle** (direction / éducatrice / parent).  
2. **Tableau de bord** adapté au rôle.  
3. **Fiche enfant** (profil + santé + documents).  
4. **Fiche parent/tuteur**.  
5. **Présences quotidiennes** (scan QR / signature).  
6. **Journal de bord** (repas, sieste, humeur, incidents).  
7. **Activités pédagogiques** (planification).  
8. **Incidents & accidents** (formulaire + photos).  
9. **Médicaments & allergies** (rappels).  
10. **Messagerie & avis**.  
11. **Facturation & paiements**.  
12. **Rapports & exports**.  
13. **Paramètres & conformité**.  

## 8) Parcours clés (user flows)
- **Inscription enfant** → validation → contrat → activation dossier.  
- **Arrivée/ départ** → signature parent → mise à jour présence.  
- **Incident** → déclaration → notification parent → archivage.  
- **Facturation** → génération → paiement → reçu.  

## 9) Données (modèle simplifié)
- Enfant (profil, santé, contacts, autorisations).  
- Parent/Tuteur (coordonnées, consentements).  
- Personnel (profils, certificats).  
- Groupe (capacité, éducatrices).  
- Présence (date, heure, signatures).  
- Incident (type, description, preuves).  
- Facture (montant, statut).  

## 10) Priorisation MVP
1. Dossiers enfants/parents.  
2. Présences quotidiennes.  
3. Communication & notifications.  
4. Facturation de base.  
5. Registres incidents et santé.  

## 11) Prochaines étapes
- Valider la juridiction (règlements locaux).  
- Définir charte UX/UI (branding, couleurs, typographie).  
- Prototyper (Figma/Android Studio).  
- Définir architecture technique et sécurité.  

---
**Livrable** : cette recherche sert de base pour concevoir un design complet (UX/UI + fonctionnalités) et une roadmap produit.
