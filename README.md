# PLANTY

![Image1](app/public/wp-content/uploads/2023/03/Planty6-1-188x300.png)

## Projet OpenClassrooms no 6 : Personnalisez un thème WordPress pour une startup avec HTML, CSS et PHP

### Objectif et ressources
Pour ce projet, l'objectif est de développer le site vitrine de la société Planty, marque de boissons énergisantes à base de plantes.  
Il faut développer le site sur WordPress et utiliser de préférence l'éditeur de page Gutenberg pour la gestion des pages.
Le site doit comporter 4 pages : la page d'Accueil, la page Nous rencontrer, la page Commander et la page Mentions légales qui sera complétée ultérieurement par le client.

Les ressources :
<ul>
    <li><a href="https://www.figma.com/file/P19mvyz8EbozI4zlHJB7fy/Maquette-Planty-P6-Wordpress?node-id=0-1&t=iNwwNBiCNke2wMyD-0" target="_blank">la maquette Figma</a></li>
    <li><a href="https://www.figma.com/proto/P19mvyz8EbozI4zlHJB7fy/Maquette-Planty-P6-Wordpress?node-id=2%3A40&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=2%3A40" target="_blank">un prototype sur Figma</a></li>
    <li><a href="https://course.oc-static.com/projects/D%C3%A9veloppeur+Web/DWP_P6+WordPress+PHP+Planty/DW+P6+Wordpress+-+Sp%C3%A9cifications+fonctionnelles.pdf" target="_blank">un guide avec les spécifications techniques</a></li>
</ul>
    
### Spécifications additionnelles
<ul>
    <li>Dans le header, un lien Admin doit pointer vers la gestion WordPress. Il ne doit être présent que si l'utilisateur est connecté à WordPress. Il est donc conseillé d’utiliser un hook pour faire l’ajout de ce lien.</li>
    <li>Le site doit s’afficher correctement sur toutes les tailles d’écran (à partie de 320px).</li>
    <li>Les lignes écrites en HTML et CSS doivent passer au validateur du W3C.</li>
    <li>Le projet devra être versionné avec Git et GitHub.</li>
    <li>Les formulaires doivent être fonctionnels : un mail doit être envoyé à “planty.drinks@gmail.com”.</li>
    <li>Toutes les données (textes et images) doivent être modifiables par le client sans utilisation de code.</li>
</ul>

### Mes choix
<ul>
    <li>Installation de WordPress via Local car problèmes avec MAMP <a href="https://localwp.com/" target="_blank">Local</a>.</li>
    <li>Utilisation du thème <a href="https://fr.wordpress.org/themes/twentytwentyone/" target="_blank">Twenty Twenty One</a>.</li>
    <li>Mise en place du plugin <a href="https://wordpress.org/plugins/duplicate-page/" target="_blank">Duplicate Page</a> pour dupliquer facilement les pages.</li>
    <li>Mise en place du plugin <a href="https://wordpress.org/plugins/contact-form-7/" target="_blank">Contact Form 7</a> pour la gestion des 2 formulaires.</li>
</ul>

### Configuration
<ul>
  <li>Serveur Web : nginx</li>
  <li>Version PHP : 8.1.9</li>
  <li>Base de données : mySQL 8.0.16</li>
   <li>Version WordPress : 6.1.1</li>
</ul>

### Le site
![Image2](/app/public/wp-content/themes/twentytwentyone-child/images/Home_screenshot_Planty.png)
