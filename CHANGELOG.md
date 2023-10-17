# Changelog
Tout changement notable de ce projet sera documenté dans ce fichier.

Ce projet suit le [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
Le format de ce fichier est inspiré de [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).


## Release 2.0.0

### Modification
- Modification du préfixe du NRC : sct-ext (http://data.esante.gouv.fr/NRC-France/sct-ext#)

## Release 1.0.0

### Initialisation
- Release basée sur la 3.0.6 du SNOMED OWL Toolkit
- Ajout du préfixe nrc (http://data.esante.gouv.fr/NRC-France/SCT#)
- Ajout de l'identifiant (skos:notation)
- Ajout du statut de définition (nrc:definitionStatus)
- Ajout du suffixe sémantique (dc:type)
- Modification du FSN (rdfs:label --> nrc:fsn)
- Modification du terme préféré (skos:prefLabel --> rdfs:label)
- Suppression des tags de dialectes anglais (en-gb et en-us)