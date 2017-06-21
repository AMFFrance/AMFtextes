# ANNEXE

## Tableau 1

Tableau des symboles du tableau 2

SYMBOLE TYPE DE DONNÉES DÉFINITION {ALPHANUM-n} Jusqu'à n caractères alphanumériques Champ permettant d'introduire un texte à contenu libre. {DECIMAL-n/m} Nombre décimal de maximum n chiffres au total dont m chiffres maximum peuvent être des chiffres de fractions Champ numérique pouvant contenir des valeurs positives ou négatives. — utiliser le signe «.» (point) comme séparateur décimal — le nombre peut être précédé de «-» (signe moins) pour indiquer une valeur négative. Le cas échéant, les valeurs sont arrondies et non tronquées. {CURRENCYCODE_3} 3 caractères alphanumériques Code monnaie à 3 lettres (code monnaie ISO 4217). {DATEFORMAT} Format de date ISO 8601 Les dates doivent respecter le format AAAA-MM-JJ. {ISIN} 12 caractères alphanumériques Code ISIN au sens de la norme ISO 6166. {MIC} 4 caractères alphanumériques Identifiant de marché au sens de la norme ISO 10383.



Tableau 2

Format de déclaration aux fins du mécanisme de plafonnement des volumes

Nom du champ de données Format Période de déclaration {DATEFORMAT}/{DATEFORMAT} la première date étant le début de la période de déclaration et la deuxième sa fin. Identification de l'entité déclarante Lorsque l'entité déclarante est une plate-forme de négociation: {MIC} (MIC du segment ou, le cas échéant, MIC opérationnel) ou {ALPHANUM-50} si l'entité déclarante est un CTP Identifiant de la plate-forme de négociation {MIC} (MIC du segment s'il est disponible, sinon MIC opérationnel) Identifiant de l'instrument {ISIN} Monnaie des transactions {CURRENCYCODE_3} Volume total des transactions (par monnaie) {DECIMAL-18/5} Volume total des transactions bénéficiant de la dérogation au titre des prix de référence au sens de l'article 4, paragraphe 1, point a), du MIFIR (par monnaie) {DECIMAL-18/5} Volume total des transactions bénéficiant de la dérogation au titre des transactions négociées au sens de l'article 4, paragraphe 1, point b) i), du MIFIR (par monnaie) {DECIMAL-18/5}

