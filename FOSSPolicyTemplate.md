# Open Source Policy Template

## Objectives

PUBLIC_ADMINISTRATION's goals in releasing this policy are:

Les objectifs de PUBLIC_ADMINISTRATION en publiant cette politique sont :

* Se conformer à la réglementation

* Collaborer entre les administrations publiques nationales et internationales

* S'engager avec les communautés existantes

* Favoriser la croissance économique

L'objectif de cette politique est de permettre à l'ADMINISTRATION_PUBLIQUE d'adopter le développement de logiciels open source sans compromettre ses intérêts fondamentaux et la sécurité de l'information, en suivant les meilleures pratiques des communautés et dans le respect de toutes les parties prenantes.

Globalement cette politique propose de :

1. Permettre aux fonctionnaires et aux sous-traitants de contribuer et de publier des projets open source

2. Partager les meilleures pratiques pour collaborer et interagir avec les communautés

3. Apporter soutien et assistance

## Scope and applicability

This policy should be applied by all civil servants of PUBLIC_ADMINISTRATION and related contractors and subcontractors.

This policy only applies to works for which PUBLIC_ADMINISTRATION owns the copyright according to the applicable law or enough rights provided by relevant licences. The Best Practices document provides clear definitions and examples of what falls within this scope.

Entities belonging to ENTITY_NAME may instantiate an inherited version of this policy.

Open-sourcing existing code is another process and requires additional steps that are out of the scope of this policy. Please refer to the ENTITY_SUPPORT_EMAIL for more information.

Note that FOSS projects may include technical and functional documentation, user, administrator and/or programmer manuals, examples, translations, sample data, artwork, and/or configuration files. 

## Definitions

"FOSS" refers to “Free/Open Source Software” and is used generally to refer to software that either under a license that has been approved by the Free Software Foundation, Open Source Initiative, or a license which grants the four rights: to use the software for any purpose, to study the source code, to share it with others, and improve the software. In places “open source” is also substituted for readability. Free Software and Open Source Software are used as synonyms throughout the document.

"Civil servant": person employed by a public administration, either officially sworn in or on an employment contractual basis.

"OSI approved license:" [https://opensource.org/licenses](https://opensource.org/licenses)

"Free Software Foundation approved license": [https://www.gnu.org/licenses/licenses.en.](https://www.gnu.org/licenses/licenses.en.html)[html](https://www.gnu.org/licenses/licenses.en.html)

"Version control system": software product or service designed to store and retrieve several versions of source code and related assets in a consistent way, can be centralised,  decentralised or distributed.

## Open By Default

From this point forward, code that is developed by or for ENTITY_NAME shall be free/open source by default. Detailed requirements follow but at a high level:

* Entities shall develop in the open wherever possible.

* When releasing code, agencies shall ensure that an appropriate FOSS license is applied.

* When procuring the development of code, entities shall ensure that they secure copyright to and delivery of the code in order to facilitate releasing it as open source. 

### Participate in the Open Source Community.

Wherever possible, contributions should be made to existing projects rather than creating independent efforts and all contributions should be given back to the community. 

### Accounts

Civil servants are permitted to attach their name to their contributions and be recognized individually, while the copyright remains with ENTITY_NAME and under the license selected for the project. 

Civil servants are not prohibited from working on side-projects when off duty, and their professional contributions should be distinguished from personal contributions. Criteria are given in the next section.

This distinction should be made through the email address used to submit code:

* Professional contributions should be submitted :

    * with the government email address for civil servants

    * with the company email address for subcontractors

* Personal contributions should be submitted with the personal email address.

Anonymous / generic email contribution should be avoided: managers with civil servants who do not want to release their code should use their own email address instead. 

In addition, civil servants whose employment is sensitive information are to be given cover identities to enable them to contribute to FOSS projects without endangering their safety; equally, contractor employees who have a legal right to keep the fact of their employment non-public and wish to do so must adopt a pseudonym for contributing to ENTITY_NAME projects. In these cases, the same identity must be used by the contributor for all ENTITY_NAME projects to facilitate communications with external developers.

### Support

ENTITY_NAME will provide a centralized support for cases not covered by this policy or questions others may have to implement the policy through ENTITY_SUPPORT_EMAIL. 

## Contributing to Existing Open Source Projects

ENTITY_NAME’s civil servants and subcontractors are authorized to contribute code and documentation related to FOSS projects that they are using as part of their mission for ENTITY_NAME under the licenses used by these projects, provided that the following conditions are met.

### Evaluate the Project License

ENTITY_NAME’s civil servants and subcontractors can only contribute to projects that have a clearly defined license that is approved by ENTITY_NAME and available at ACCEPTED_LICENSES_URL. 

This consideration should also apply to the dependencies used by the projects:

Shouldn’t one or more of a project’s dependencies fit these criteria, participation in the project may still be appropriate, but further scrutiny and evaluation is needed. Projects falling under this situation should be treated on a case by case basis. Additional support can be obtained through ENTITY_SUPPORT_EMAIL

### Verifying the integrity of the contribution

ENTITY_NAME’s civil servants and subcontractors must be the original authors of the contribution that they submit. If the proposed contribution is in part or entirely derived from a third party work, they must ensure that this party’s work has been licenced in a way that makes it allowed for inclusion in the target project. They must also ensure to follow the required modalities attached to the third party work. 

### Signing Contributor’s License Agreements

ENTITY_NAME’s civil servants and subcontractors may only contribute to projects that require a Contributor’s License Agreement (CLA) that have been agreed upon by ENTITY_NAME and are available at ENTITY_CLA_URL.

Similarly, Individual Contributor’s License Agreements need to be approved by ENTITY_SUPPORT_EMAIL.

## Releasing and Managing Open Source Projects 

### Initial check

Before starting a new project, civil servants shall verify that there is no existing FOSS project that more or less suits the needs (functional requirements, license…) of ENTITY_NAME. 

The proposed project name shall be checked against trademark protection by a third party or whether the name is already used by another Open Source project. 

### Governance

At least two maintainers having full commit rights on a project (preferably from different institutions) should be identified.

### Licenses

Whenever possible, the new project shall use an outbound license ensuring compatibility with corresponding FOSS projects ecosystem.

Any new FOSS project dependency shall be duly checked against its compatibility between the licenses of the various components of the project, including the target licence of the project’s code base.

If the ecosystem is completely new, following licenses are recommended depending on the use cases:

* General use case : a permissive license (default Apache 2.0) to avoid any competition bias and allow private actors to include the software in proprietary code

* Services aimed directly at citizens: a reciprocal license (default GPL v3.0) to ensure contributions will directly benefit the citizens

Creating a new license is very strongly discouraged and explicit approval is required from ENTITY_SUPPORT_EMAIL.

Contributions should be accepted under the same license as the project outbound license. A CLA should not be required for the project. Instead, a process like the [Developer’s Certificate of Origin](http://developercertificate.org/) (DCO), can be used to verify that developers agree with the project’s license, if so desired.

### Version control system

Releasing the source code can be made on any public distributed version control system (git or mercurial) or corresponding hosted platform . A copy of the public repository should be synced with the ENTITY_NAME version control system for backup and integrity checks.

### Security

ENTITY_NAME’s standard security process should be applied.

### Deprecation Policy

Public repositories are archived in a manner accessible to the public when ENTITY_NAME hands over or discontinues a software project.

Modèle de politique open source
Objectifs


Portée et applicabilité
Cette politique doit être appliquée par tous les fonctionnaires de l'ADMINISTRATION_PUBLIQUE et les contractants et sous-traitants associés.

Cette politique s'applique uniquement aux œuvres pour lesquelles PUBLIC_ADMINISTRATION détient le droit d'auteur conformément à la loi applicable ou suffisamment de droits fournis par les licences pertinentes. Le document sur les meilleures pratiques fournit des définitions claires et des exemples de ce qui relève de ce champ d'application.

Les entités appartenant à ENTITY_NAME peuvent instancier une version héritée de cette règle.

L'open source du code existant est un autre processus et nécessite des étapes supplémentaires qui sortent du cadre de cette politique. Veuillez vous référer au ENTITY_SUPPORT_EMAIL pour plus d'informations.

Notez que les projets FOSS peuvent inclure de la documentation technique et fonctionnelle, des manuels d'utilisateur, d'administrateur et/ou de programmeur, des exemples, des traductions, des exemples de données, des illustrations et/ou des fichiers de configuration.

Définitions
« FOSS » fait référence à un « logiciel libre/open source » et est généralement utilisé pour désigner un logiciel qui, soit sous une licence qui a été approuvée par la Free Software Foundation, l'Open Source Initiative, ou une licence qui accorde les quatre droits : d'utiliser le logiciel à quelque fin que ce soit, pour étudier le code source, le partager avec d'autres et améliorer le logiciel. À certains endroits, « l'open source » remplace également la lisibilité. Logiciel libre et logiciel libre sont utilisés comme synonymes dans tout le document.

« Fonctionnaire » : personne employée par une administration publique, soit officiellement assermentée, soit sur la base d'un contrat de travail.

"Licence approuvée par l'OSI :" https://opensource.org/licenses

"Licence approuvée par la Free Software Foundation": https://www.gnu.org/licenses/licenses.en.html

« Système de contrôle de version » : produit ou service logiciel conçu pour stocker et récupérer plusieurs versions du code source et des actifs associés de manière cohérente, pouvant être centralisé, décentralisé ou distribué.

Ouvrir par défaut
À partir de maintenant, le code développé par ou pour ENTITY_NAME sera gratuit/open source par défaut. Les exigences détaillées suivent, mais à un niveau élevé :

Les entités doivent se développer à l'air libre dans la mesure du possible.

Lors de la publication du code, les agences doivent s'assurer qu'une licence FOSS appropriée est appliquée.

Lors de l'achat du développement du code, les entités doivent s'assurer qu'elles garantissent le droit d'auteur et la livraison du code afin de faciliter sa diffusion en tant que source ouverte.

Participez à la communauté Open Source.
Dans la mesure du possible, les contributions doivent être apportées à des projets existants plutôt que de créer des efforts indépendants et toutes les contributions doivent être reversées à la communauté.

Comptes
Les fonctionnaires sont autorisés à associer leur nom à leurs contributions et à être reconnus individuellement, tandis que les droits d'auteur restent la propriété de ENTITY_NAME et sous la licence sélectionnée pour le projet.

Il n'est pas interdit aux fonctionnaires de travailler sur des projets parallèles lorsqu'ils ne sont pas en service, et leurs contributions professionnelles doivent être distinguées des contributions personnelles. Les critères sont donnés dans la section suivante.

Cette distinction doit être faite via l'adresse e-mail utilisée pour soumettre le code :

Les contributions professionnelles doivent être soumises :

avec l'adresse email du gouvernement pour les fonctionnaires

avec l'adresse e-mail de l'entreprise pour les sous-traitants

Les contributions personnelles doivent être soumises avec l'adresse e-mail personnelle.

La contribution par e-mail anonyme / générique doit être évitée : les gestionnaires avec des fonctionnaires qui ne souhaitent pas publier leur code doivent utiliser leur propre adresse e-mail à la place.

En outre, les fonctionnaires dont l'emploi est une information sensible doivent recevoir des identités de couverture pour leur permettre de contribuer aux projets FOSS sans mettre en danger leur sécurité ; De même, les employés des sous-traitants qui ont le droit légal de garder le fait de leur emploi non public et qui souhaitent le faire doivent adopter un pseudonyme pour contribuer aux projets ENTITY_NAME. Dans ces cas, la même identité doit être utilisée par le contributeur pour tous les projets ENTITY_NAME afin de faciliter les communications avec les développeurs externes.

Soutien
ENTITY_NAME fournira une assistance centralisée pour les cas non couverts par cette politique ou les questions que d'autres personnes pourraient avoir pour mettre en œuvre la politique via ENTITY_SUPPORT_EMAIL.

Contribuer à des projets Open Source existants
Fonctionnaires et sous-traitants de ENTITY_NAME
