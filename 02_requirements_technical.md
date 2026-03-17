# Camille Runtime — Technical Requirements

## 1. Architecture

Le système doit être modulaire et déployable localement.

### Composants principaux :

- Modèle de raisonnement
- Modèle de personnalité
- Mémoire court terme (Redis)
- Mémoire long terme (Qdrant / DB)
- Routeur conversationnel

## 2. Pipeline cible

1. Analyse d’intention
2. Récupération mémoire
3. Raisonnement
4. Reformulation par personnalité
5. Génération finale

## 3. Exigences système

- Support de modèles quantifiés
- Remplacement indépendant des composants
- Observabilité complète (logs, décisions, mémoire utilisée)
- Scalabilité horizontale possible

## 4. Contraintes

- Fonctionnement local prioritaire
- Ressources limitées (CPU/GPU modérés)
- Pas de dépendance à un fournisseur unique

## 5. Qualité

- Minimiser hallucinations
- Maintenir cohérence globale
- Favoriser stabilité long terme vs performance ponctuelle
