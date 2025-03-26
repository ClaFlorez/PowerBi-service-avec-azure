# 🚀 Connexion à Power BI Service avec un Environnement Virtuel Azure

## 📝 Introduction
Ce guide explique comment configurer un environnement virtuel sur Azure et optimiser l'utilisation des ressources pour se connecter à **Power BI Service**, tout en évitant des coûts inutiles.

---

## 🛠️ Prérequis
✔️ Un compte Azure avec un **crédit d'essai** actif.  
✔️ Un environnement virtuel disponible sur **Azure Machine Learning** ou **Microsoft Fabric**.  
✔️ Un abonnement Power BI avec accès à **Power BI Service**.

---

## 🔗 Étapes de Connexion

### 1️⃣ Vérifier les Ressources Actives
1. Se connecter à [Azure Portal](https://portal.azure.com).
2. Aller dans **Cost Management + Facturation**.
3. Vérifier que **aucun service** (VM, stockage, IP publique) ne consomme du crédit.

### 2️⃣ Mettre en Pause Microsoft Fabric (si utilisé)
1. Aller à **Microsoft Fabric Capacity**.
2. Cliquer sur **Pause** pour éviter la consommation de ressources.
3. Vérifier que l’état est bien **« Paused »**.

### 3️⃣ Vérifier l’Environnement Virtuel
1. Dans le portail Azure, rechercher **Environnements Virtuels**.
2. Vérifier s'il y a des instances actives.
3. Si nécessaire, arrêter ou supprimer les ressources inutiles.

### 4️⃣ Configurer une Alerte de Consommation 💰
1. Aller dans **Cost Management + Billing**.
2. Sélectionner **Alertes budgétaires**.
3. Définir une alerte à **80% du crédit disponible**.
4. Recevoir une notification avant d’atteindre la limite.

### 5️⃣ Vérifier la Facturation 📊
1. Accéder à **Cost Management > Analyse des coûts**.
2. Sélectionner la période actuelle.
3. Confirmer que l’usage reste à **0 €** si aucune ressource n’est utilisée.

---

## ✅ Résultats
✔️ Connexion réussie à Power BI Service via l’environnement Azure.  
✔️ Aucune consommation inutile de crédit.  
✔️ Surveillance active des coûts avec alerte configurée.  

📌 **Astuce** : Toujours vérifier les ressources actives avant de quitter Azure pour éviter des frais inattendus.

---

## 📌 Conclusion
En suivant ces étapes, nous avons réussi à optimiser notre utilisation d’Azure tout en établissant une connexion efficace avec **Power BI Service**.

Si vous avez des questions, n’hésitez pas à les poser en commentaire ! 💬

