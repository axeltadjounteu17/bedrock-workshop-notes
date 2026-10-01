# Atelier AWS : Amazon Bedrock avec Claude Code, Kiro, AgentCore et Strands Agents

> Notes personnelles de l'atelier suivi dans le sandbox gratuit AWS Builder Center.
> **Rappel : ne jamais commiter de clés, jetons ou identifiants (même temporaires).**

## Infos générales

- **Date :** ____
- **Heure de notification du sandbox :** ____ (fin = +8 h)
- **Durée réelle de l'atelier :** ____
- **Région AWS utilisée :** ____
- **Modèles Bedrock utilisés :** ____
- **Lien de l'atelier :** https://catalog.us-east-1.prod.workshops.aws/workshops/cdbce152-b193-43df-8099-908ee2d1a6e4

---

## Modèle à copier pour chaque lab

### Lab X : Titre
- **Objectif du lab :** (1 phrase, avec mes mots)
- **Services / outils utilisés :**
- **Ce que j'ai construit :**
- **Commandes ou code clés :**
- **Difficultés rencontrées et solution :**
- **Ce que j'ai compris (pas juste fait) :**
- **Capture(s) :** `captures/labX-...png`
- **Idée de réutilisation dans mes projets :**
- **Temps passé :**

---

## 1. Principes fondamentaux agentic
- **Boucle d'un agent (raisonnement, outil, résultat), en mes mots :**
- **Différence entre un simple appel LLM et un agent :**
- **Capture :** `captures/01-agentic-...png`

## 2. Sécurité et garde-fous (priorité pour mon profil)
- **Garde-fous configurés (filtres de contenu, sujets refusés, informations sensibles) :**
- **Prompt testé AVANT le garde-fou / réponse :**
- **Prompt testé APRÈS le garde-fou / réponse :**
- **Attaques testées (injection de prompt, contournement) :**
- **Limites observées :**
- **Lien avec la sécurité cloud (IAM, moindre privilège, journalisation) :**
- **Capture :** `captures/02-guardrails-...png`

## 3. Chatbots
- **Architecture :**
- **Gestion de la mémoire / historique :**
- **Réutilisable pour mes chatbots bilingues FR/EN :**
- **Capture :** `captures/03-chatbot-...png`

## 4. RAG (génération augmentée par extraction)
- **Pipeline : documents, découpage, embeddings, base vectorielle, réponse :**
- **Choix de découpage (taille des chunks) :**
- **Qualité des réponses (bonnes / mauvaises, pourquoi) :**
- **Variante à refaire sur mes propres notes de cours :**
- **Capture :** `captures/04-rag-...png`

## 5. MCP (Model Context Protocol)
- **Serveur MCP créé ou utilisé :**
- **Outils exposés :**
- **Un appel réussi (entrée / sortie) :**
- **Risques de sécurité d'un serveur MCP (permissions, entrées non fiables) :**
- **Capture :** `captures/05-mcp-...png`

## 6. Compétences des agents (skills)
- **Skill créée / utilisée :**
- **Effet sur le comportement de l'agent :**
- **Comparaison avec mes skills existantes :**
- **Capture :** `captures/06-skills-...png`

## 7. Streamlit
- **Interface construite :**
- **Branchement sur l'agent ou le RAG :**
- **Capture :** `captures/07-streamlit-...png`

## 8. Amazon Bedrock AgentCore
- **Composants vus (runtime, mémoire, identité, passerelle…) :**
- **Ce qu'AgentCore apporte par rapport à un agent « maison » :**
- **Capture :** `captures/08-agentcore-...png`

## 9. Kiro et Claude Code sur Bedrock
- **Comment chaque outil se connecte à Bedrock :**
- **Points forts / limites de chacun :**
- **Lequel je garderais pour quel usage :**
- **Capture :** `captures/09-outils-...png`

---

## Variante personnelle (après l'atelier, dans le temps restant du sandbox)
- **Ce que j'ai refait seul :** (ex. RAG sur mes cours de réseau / sécurité)
- **Différences par rapport au lab :**
- **Résultat :**

## Bilan
- **3 choses que j'ai apprises :**
  1.
  2.
  3.
- **Ce qui m'a surpris :**
- **Ce que je veux approfondir :**
- **Projet existant où je peux appliquer ça :**

## Checklist de sortie du sandbox (avant la fin des 8 h)
- [ ] Tout le code exporté vers GitHub
- [ ] Toutes les captures enregistrées dans `captures/`
- [ ] Aucune clé, jeton ou identifiant dans le dépôt (relire avant de pousser)
- [ ] Notes complétées pour chaque lab
- [ ] README du dépôt rédigé (objectif, architecture, apprentissages)
- [ ] Idée de post ou d'article notée (angle : garde-fous et sécurité)
