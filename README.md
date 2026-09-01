# Bastien Ladra

**Ingénieur DevSecOps & Cybersécurité**  
Je sécurise la livraison logicielle et les infrastructures cloud en intégrant des contrôles de sécurité directement dans les pratiques d'ingénierie.

[Portfolio](https://bastien-ladra.github.io/portfolio-bastien-ladra/) · [CV public](https://bastien-ladra.github.io/portfolio-bastien-ladra/resume.html) · [LinkedIn](https://www.linkedin.com/in/bastienladra) · [Email](mailto:ladra.bastien@gmail.com)

## Ce que j'apporte à une équipe

- **CI/CD sécurisée** — quality gates, SAST, DAST, secret scanning et dependency review.
- **Software supply chain** — dépendances verrouillées, SBOM CycloneDX, provenance et attestations d'artefacts.
- **Cloud & IaC security** — Terraform, GCP/AWS, durcissement conteneur et contrôles de configuration.
- **DevSecOps pragmatique** — des contrôles vérifiables qui restent compatibles avec le rythme des équipes d'ingénierie.

## Expérience professionnelle

- **NEHS Digital — DRIM-M (2023–2024)** : migrations GitLab/Bitbucket, CI/CD, gestion d'incidents, Docker, Ansible et Red Hat.
- **GSOI (2022–2023)** : sécurité GCP avec Security Command Center et Cloud Armor, Terraform, PKI et Pentera.
- **ASTEK — Digital Cloud Factory (2022)** : AWS, Python, Vuls/Trivy, Docker et développement d'outillage.

**Actuellement :** POEI Consultant DevSecOps — programme de 300 h, LUPISE / France Travail, août–octobre 2026.

## Projet phare — Secure API DevSecOps

[`bastien-ladra/secure-api-devsecops`](https://github.com/bastien-ladra/secure-api-devsecops) est mon projet public de référence pour montrer comment des contrôles de sécurité s'enchaînent de la pull request jusqu'à l'artefact publiable.

**Preuves inspectables :** tests Python, Gitleaks, Dependency Review, CodeQL, Trivy, OWASP ZAP, Terraform, image distroless non-root, SBOM CycloneDX, provenance de build et attestation SBOM, avec une cible GCP Artifact Registry / Cloud Run.

[Étude de cas FR](https://bastien-ladra.github.io/portfolio-bastien-ladra/case-study-secure-api-fr.html) · [Case study EN](https://bastien-ladra.github.io/portfolio-bastien-ladra/case-study-secure-api.html) · [Voir le code](https://github.com/bastien-ladra/secure-api-devsecops)

## Projet complémentaire — CyberSOC-AI-Lab

[`bastien-ladra/CyberSOC-AI-Lab`](https://github.com/bastien-ladra/CyberSOC-AI-Lab) explore une question différente : **comment une IA peut-elle assister un analyste SOC sans remplacer sa décision ?**

Le laboratoire combine trois scénarios contrôlés (`SSH_BRUTE_FORCE`, `WEB_RECONNAISSANCE`, `PROMPT_INJECTION_ATTEMPT`), détection explicable basée sur règles, assistance IA locale optionnelle via Ollama, validation humaine et journalisation d'audit. Les logs publics sont synthétiques et le projet n'est pas présenté comme un SIEM, un EDR ou un SOC de production.

**Preuves inspectables :** CI avec Black/Ruff/mypy/Bandit/pytest, seuil de couverture ≥ 90 %, Gitleaks plein historique, dépendances verrouillées par hash et auditées, conteneur non-root épinglé par digest, scan Trivy HIGH/CRITICAL et SBOM CycloneDX.

[Voir le code et l'étude de cas](https://github.com/bastien-ladra/CyberSOC-AI-Lab)

## Formation & repères

- **Epitech — Expert en technologies de l'information**, 2022.
- **Google Cybersecurity Certificate**, 2023.
- **EBIOS Risk Manager — introduction**, Club EBIOS, 2025.
- **ANSSI SecNumAcademie — 4 modules**, 2021.

## Axe de progression

Je m'intéresse à l'extension des garanties de la **software supply chain** vers les systèmes IA : provenance des modèles et datasets, pipelines ML vérifiables et Secure MLOps. CyberSOC-AI-Lab ajoute désormais une première preuve publique sur le volet IA/cybersécurité, dans un périmètre expérimental explicitement borné.

---

## English snapshot

**DevSecOps & Cybersecurity Engineer** focused on secure software delivery, cloud infrastructure and software-supply-chain assurance.

My background spans **NEHS Digital, GSOI and ASTEK**, with hands-on work across CI/CD, GCP/AWS, Terraform, container security and security tooling. My public flagship project, [`secure-api-devsecops`](https://github.com/bastien-ladra/secure-api-devsecops), demonstrates inspectable controls from pull request to published artifact, including SAST/DAST, container and IaC scanning, SBOMs and provenance.

My second public project, [`CyberSOC-AI-Lab`](https://github.com/bastien-ladra/CyberSOC-AI-Lab), explores explainable AI-assisted SOC workflows with synthetic data, local optional LLM assistance, human validation, auditability, hash-locked dependencies, container scanning and a CycloneDX SBOM. It is explicitly scoped as an experimental lab rather than a production SOC platform.

[Portfolio](https://bastien-ladra.github.io/portfolio-bastien-ladra/?lang=en) · [Public resume](https://bastien-ladra.github.io/portfolio-bastien-ladra/resume.html?lang=en) · [LinkedIn](https://www.linkedin.com/in/bastienladra) · [Email](mailto:ladra.bastien@gmail.com)
