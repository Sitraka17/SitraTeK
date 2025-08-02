Voici une **fiche de synthèse** mise à jour,  avec des **notions techniques approfondies** pour chaque UE nécessaire pour devenir Ingénieur Logiciel. 
Elle est structurée selon les blocs, pour faciliter la compréhension du parcours et de ses compétences associées.
Merci et bravo au CNAM. 

---

## 🔧 **Bloc UTC – Unités Transverses de Base (Obligatoires – 15 ECTS)**

| **Code**   | **Intitulé**                                       | **Notions techniques approfondies**                                                                                                                                                                                                                                                                                                           |
| ---------- | -------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **UTC501** | Outils mathématiques pour l'informatique           | Logique propositionnelle et du premier ordre ; calcul booléen ; ensembles, relations et applications ; matrices et calcul matriciel ; graphes orientés et non orientés ; récurrence, preuves par induction ; combinatoire ; notions de complexité asymptotique (O, Ω, Θ).                                                                     |
| **UTC502** | Principes fondamentaux des systèmes d'exploitation | Architecture de système (noyau, espace utilisateur) ; gestion des processus et ordonnancement (FIFO, SJF, Round Robin) ; synchronisation (sémaphores, mutex, moniteurs) ; gestion mémoire (pagination, segmentation, swapping) ; systèmes de fichiers (FAT, ext4, journaling) ; appels système (fork, exec, wait) ; structure du noyau Linux. |
| **UTC503** | Paradigmes de programmation                        | Paradigmes impératif, orienté objet, fonctionnel, logique ; différences sémantiques et syntaxiques ; typage dynamique vs statique ; récursivité et itération ; interpréteurs vs compilateurs ; langage support : Python, Java, Scheme/Haskell, Prolog.                                                                                        |
| **UTC504** | Systèmes d'information et bases de données         | Modèle relationnel ; algèbre relationnelle ; conception de schéma en 3NF/BCNF ; dépendances fonctionnelles ; langage SQL (DDL, DML, DCL) ; vues, index, triggers, procédures stockées ; gestion de la concurrence (verrouillage, contrôle d’accès, ACID) ; introduction à NoSQL (clé-valeur, document, colonne, graphe).                      |
| **UTC505** | Réseaux et sécurité – Introduction                 | Modèle OSI & TCP/IP ; Ethernet, IP, TCP, UDP, ARP, DNS, DHCP ; sous-réseautage (CIDR, masques, NAT) ; routage statique/dynamique ; sécurité réseau : chiffrement symétrique/asymétrique (AES, RSA), hachage (SHA-2), TLS/SSL, VPN ; attaques réseaux (DoS, spoofing, sniffing) ; pare-feux, IDS/IPS.                                          |

---

## 📐 **Bloc IMO – Informatique Mathématique et Optimisation (6 ECTS – 1 UE à choisir)**

| **Code**   | **Intitulé**                                          | **Notions techniques approfondies**                                                                                                                                                                                                                                      |
| ---------- | ----------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **RCP105** | Modélisation, optimisation, complexité et algorithmes | Programmation linéaire (PL) ; modélisation sous contraintes ; dualité forte et faible ; complexité algorithmique (P, NP, NP-complet, NP-difficile) ; techniques de preuve de NP-complétude ; introduction aux algorithmes de résolution (Branch and Bound, SAT solvers). |
| **RCP101** | Recherche opérationnelle et aide à la décision        | Méthodes de résolution de problèmes de transport et d'affectation ; programmation linéaire et simplexe ; files d’attente ; arbres de décision ; planification sous contraintes ; analyse multicritère ; modélisation des choix dans les systèmes d’aide à la décision.   |
| **RCP104** | Optimisation en informatique                          | Programmation dynamique (memoization, récursivité optimisée) ; algorithmes gloutons (preuve de correction) ; méthodes heuristiques (tabou, recuit simulé) ; contraintes combinatoires ; graphe de flot, flot maximum ; coloration de graphes ; SAT/SMT.                  |
| **RCP110** | Programmation linéaire avancée                        | Formulations PLM (Mixed-Integer Programming) ; dualité et théorèmes fondamentaux ; analyse de sensibilité ; méthodes de décomposition (Benders, Dantzig-Wolfe) ; solveurs avancés (CPLEX, Gurobi).                                                                       |

---

## 🖥️ **Bloc AISL – Approfondissement Informatique Systèmes Logiciels (6 ECTS – 1 UE à choisir)**

| **Code**   | **Intitulé**                               | **Notions techniques approfondies**                                                                                                                                                                              |
| ---------- | ------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **NSY103** | Linux : principes et programmation         | Structure de Linux : noyau, processus, inodes, fichiers spéciaux ; compilation de noyau ; scripts Bash avancés ; utilisation d’`strace`, `lsof`, `top` ; makefiles ; débogage système (`gdb`) ; appels systèmes. |
| **NSY104** | Architectures des systèmes informatiques   | Architecture Von Neumann ; pipeline d’instruction ; ISA (RISC vs CISC) ; hiérarchie mémoire (cache L1/L2, TLB) ; jeux d’instructions x86/ARM ; mémoire virtuelle ; interfaces d'E/S ; bus système.               |
| **NFP119** | Programmation fonctionnelle                | Lambda-calcul, fonctions pures, récursivité terminale ; évaluations paresseuse/stricte ; typage fort et inférence de types ; monades ; programmation concurrente en mode fonctionnel.                            |
| **NFP121** | Programmation avancée                      | Méta-programmation, réflexion, patrons de conception (factory, singleton, observer) ; gestion fine de la mémoire ; introspection ; POO avancée en Java/C++.                                                      |
| **NSY115** | Conduite de projet informatique            | Cycle de vie logiciel (V, agile, Scrum, Kanban) ; outils de gestion (Jira, Git, GitLab CI/CD) ; gestion des risques ; indicateurs (burndown chart, vélocité).                                                    |
| **GLG105** | Génie logiciel                             | Ingénierie des exigences ; UML (cas d’utilisation, diagrammes de classes/séquence) ; intégration continue ; tests (unitaires, intégration, système) ; documentation, qualité logicielle.                         |
| **SEC102** | Menaces informatiques & codes malveillants | Types de malwares (virus, ransomware, rootkit) ; reverse engineering avec IDA/Ghidra ; techniques d’obfuscation ; sandboxing ; détection de signatures ; exploitation de failles (buffer overflow, ROP).         |
| **NSY014** | Applications réparties                     | RPC, RMI, sockets, gRPC ; modèles de communication synchrone/asynchrone ; tolérance aux pannes ; gestion de la cohérence ; frameworks (Spring, Akka).                                                            |

---

## 💽 **Bloc ISI – Systèmes d’Information (6 ECTS – 1 UE à choisir)**

| **Code**   | **Intitulé**                                | **Notions techniques approfondies**                                                                                                         |
| ---------- | ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| **NFE108** | Méthodologies des SI                        | Merise, UML, cycle en V ; modélisation des processus métier ; urbanisation des SI ; alignement stratégique.                                 |
| **NFP107** | Systèmes de gestion de BDD                  | Transactions, isolation (ACID, MVCC) ; réplication, partitionnement ; tuning SQL ; sécurité base de données ; triggers/procédures stockées. |
| **NFE115** | Gestion de données à large échelle          | Hadoop, Spark, MapReduce ; bases NoSQL (MongoDB, Cassandra) ; Data Lake vs Data Warehouse ; ingestion de flux (Kafka, Flink).               |
| **NFE113** | Conception et administration de BDD         | Étapes d’analyse et de déploiement ; outils d’administration (pgAdmin, SQL Server Management Studio) ; stratégie de sauvegarde.             |
| **NFE114** | Systèmes d’information web                  | Frameworks web (Django, Laravel) ; REST API, OAuth2 ; MVC ; tests d’intégration, CI/CD web.                                                 |
| **SEC101** | Cybersécurité : référentiels et déploiement | ISO 27001, NIST, RGPD ; politiques de sécurité ; audit de sécurité ; chiffrement, gestion des identités, logging sécurisé.                  |

---

## 🌐 **Bloc IRSM – Réseaux, Sécurité, IHM (6 ECTS – 1 UE à choisir)**

| **Code**   | **Intitulé**                             | **Notions techniques approfondies**                                                                                               |
| ---------- | ---------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| **RSX101** | Réseaux et protocoles                    | Routage (OSPF, BGP), VLAN, NAT, DNS, DHCP, IP v4/v6 ; outils (Wireshark, tcpdump) ; configuration de routeurs (Cisco, Juniper).   |
| **RSX102** | Tech. réseau – NetDevOps                 | Automatisation réseau (Ansible, NetBox) ; SDN ; supervision (Prometheus, Zabbix) ; pipelines CI/CD réseau ; dockerisation réseau. |
| **RSX103** | Urbanisation des services réseau         | Architecture orientée service (SOA) ; microservices ; sécurité inter-services ; orchestrateurs (Kubernetes).                      |
| **MUX101** | Multimédia & IHM                         | Codage audio/vidéo (H.264, MP3) ; WebRTC ; streaming ; interaction multimodale ; eye tracking.                                    |
| **MUX102** | IHM : UX et UI                           | Design centré utilisateur ; heuristiques de Nielsen ; A/B testing ; accessibilité ; outils (Figma, Axure).                        |
| **SMB101** | SE : programmation & virtualisation      | Modules noyau ; VFS ; chroot, containers (LXC, Docker), hyperviseurs (KVM, VirtualBox), cgroups, namespaces.                      |
| **SEC105** | Contrôle d'accès & gestion des identités | LDAP, Active Directory ; SSO, Kerberos ; OpenID Connect, SAML ; RBAC, ABAC ; Zero Trust.                                          |

---

Bon courage à toi qui lit ceci ;) 
