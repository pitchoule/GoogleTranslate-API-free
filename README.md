GoogleTranslate-API-free
========================

GoogleTranslate-API-free est un projet PHP capable d'utiliser l'API Google Traduction sans compte et sans restriction.

Requirements
===

  - PHP 4.0.2
 
Author
===
Pitchoule - Novice Developper PHP

License
===
Code is [Public Domain](UNLICENSE).


Technical notes
===

Afin de pouvoir utiliser cette API :
 * Il faut copier le fichier sur votre serveur.
 * Il faut integrer le fichier à l'endroit où vous desirez l'utiliser : require(...PATH.../GoogleTranslateAPI.php);
 * Pour appeler la fonction : Translate(#Mot/phrase à traduire,#langue d'origine,#langue de traduction);
 * exemple : Translate("Привет",'ru','fr'); Result=> "Salut"
 * pour les codes pays se référer à : http://www.iso.org/iso/fr/french_country_names_and_code_elements.htm
 * On peut aussi appeler la fonction sans langue d'origine, si on ne la connait pas par exmple.
 * exemple : Translate("Sveiki",'','fr'); Result=> "Bonjour"
 * Google traduction vous retrouvera la langue grâce à sa fonction "détection de langue".


GoogleTranslate API free
