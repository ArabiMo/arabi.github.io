<div class="title" style="text-align: center;">
  <h1>IFT-3150</h1>
  <h2>DyNotate</h2>
  <h3>Student : Mohamed Arabi | Prof : Ian Arawjo</h3>
</div>
<div class="contenu">
  <h2>Description</h2>
  <h3>Ce projet consiste à améliorer le système DyNotate, construit par moi et l'équipe de Ian Arawjo durant l'été. L'objectif est de résoudre toutes les "dettes techniques" et d'approfondir les fonctionnalités possibles, telles que la création de "règles", afin d'atteindre, comme but final, la possibilité de jouer à un jeu de "sketch" avec DyNotate et de voir ce dernier nous battre dans ce même jeu. La plus grande charge de travail consistera à améliorer les fonctionnalités déjà créées pour obtenir un résultat semblant déterministe, malgré le fait que le système soit construit sur des LLM. 
</h3>
  <h3>Mon rôle : Mon rôle sera d'aider mes coéquipiers dans le même projet à comprendre et suivre les directives de M. Ian, d'améliorer la base de code pour une meilleure assimilation par les nouveaux arrivants sur le projet, et d'explorer le concept de "règles" et de "gestures" dans un système de "sketching" intégré avec l'IA. L'objectif final est d'intégrer le concept de "règles" dans la base de code afin qu'il soit prêt à être utilisé par des utilisateurs.</h3>
  <h2>Défis :</h2>
    <h3>1) Les technologies d'IA actuelles ne sont pas adéquates pour le raisonnement spatial dans un canvas. Voir les limitations.</h3>
    <h3>2) Les modèles de langage actuels (LLM) ne sont pas adaptés pour créer des "bounding boxes" afin de connaître les emplacements des figures dans le canvas.</h3>
    <h3>3) Les frameworks de dessin sur canvas utilisent tous la technique des "strokes" pour construire les formes. Regrouper les "strokes" puis les transmettre à l'IA sous forme de formes complètes est très complexe.</h3>
    <h3>4) Le plus grand défi est de transmettre l'information fournie par l'utilisateur via l'API de Tldraw et de la convertir en données compréhensibles par un LLM, permettant au modèle de répondre d'une manière qui puisse être retransmise à Tldraw, créant ainsi une conversation fluide et naturelle entre l'utilisateur et une IA capable d'interagir avec le canvas.</h3>
    <h3>5) Cela n'a jamais été réalisé.</h3>
  <h4>Contexte: Je suis sur ce project depuis mai 2024.</h4>
  <h4>Date de début et de la fin du proje : 30 novembre 2025</h4>
  <h4>Spécification fonctionnelle : Integration d'une fonctionaliter d'adaptation de regle de jeux dans DyNotate. Modification du systeme DyNotate pour permettre l'action de jouer a un jeu avec DyNotate dans le canvas.</h4>
  <h4>Environnement et contraintes techniques : Utilisation de TlDraw, Javascript et flask. Ne pas restraindre la liberter de DyNotate (Ne pas rendre le systeme deterministique au but)</h4>
  <h4>Architecture logicielle : Architecture client-serveur avec microservices</h4>
  <h4>Modules principaux : Module de generation de texte avec/sans format, gestion et creation d'object (TlDraw). </h4>
</div>  

<div class="progess">
  <div class="Progress 1 ">
    <h1>Semaine 1-2 (1 sept - 18 sept)</h1>
    <h3>Ecriture du papier DyNotate: Dynamic Definition of Notations with Interactive AI pour la soumission du CHI2025. Creation et 'Edit' de videos demonstrations de DyNotate pour presentation du system. Amelioration du code base pour meuilleur interpretation du code.</h3>
  </div>
  <div class="Progress 2 ">
    <h1>Semaine 3-4 (19 sept - 26 sept)</h1>
    <h3>Pause sur le project pour ma part sous l'orde de Mr. Ian. (18 semaines de suite sur le projet)</h3>
  </div>
  <div class="Progress 3 ">
    <h1>Semaine 5-6 (27 sept - 11 oct)</h1>
    <h3>Rencontre des coéquipiers du projet avec M. Ian et individuellement avec moi. Le but final du projet nous a été divulgué par M. Ian : nous devons permettre au système existant d'apprendre un jeu en "sketch" et de pouvoir y jouer avec nous. Nous avions commencé par chacun créer un jeu inédit chacun et explorer plusieurs façons de transférer le concept de "règle" à plusieurs modèles de langage (LLM) pour déterminer la meilleure approche pour faire apprendre un jeu inédit à l'IA. Nous devions également créer un rapport de jeu et une analyse à présenter à M. Ian. J'ai aussi fait un design d'architecture pour le systeme afin de pouvoir integrer les 'regles' et je l'ai presenter a l'equipe et M. Ian.</h3>
    <h4>Probleme : L'apect technique pour transmettre une regle qui a des consequences sur le resonement spatial au AI n'a jamais ete faite et semble tres complexe.</h4>
    <h4>Solution : Tentative de creation d'un designe d'architerture pour implementer les 'rules', afin de connaiter les blocus  qu'il faut reglrer.</h4>
    <h4>Blocus techniques : Comment vérifier qu'une entrée utilisateur respecte les règles ?Comment vérifier qu'une entrée IA respecte les règles ?Comment permettre à l'IA de corriger une erreur, de demander une clarification, et de distinguer entre une règle et une directive dans le prompt envoyé par l'utilisateur ?Comment faire en sorte que l'IA sache quand elle peut interagir dans le canvas ?Comment accomplir tout cela sans restreindre la liberté de l'IA ? etc...</h4>
  </div>
  <div class="Progress 4 ">
    <h1>Semaine 7 (12 oct - 18 oct)</h1>
    <h3>M. Ian nous ordonne de faire une etudes avec participants pour comprendre comment l'information est tranmis entre une personne qui explique le jeux et le partcipants. L'information sera utilsier pour simuler l'aspect humain dans le AI et pouvoir comprendre quel type d'information sur les regles sont mal transmises entre humains, et donc faire ne sorte que le system puis poser des questions recurrances sur ce meme type d'information. </h3>
    <h4>Défis : Organisation du projet, Trouver les participants, Obtenir l'approbation du comité d'éthique, Préparer un rapport d'étude à suivre, Obtenir les consentements pour l'enregistrement vidéo</h4>
    <h4>Solution : Communication fréquente au sein de l’équipe pour assurer une bonne organisation. Chaque coéquipier amènera deux de ses amis (participants) pour rejoindre les deux autres coéquipiers dans l’étude. Attendre la confirmation de M. Ian que le comité d'éthique a approuvé notre étude. Création d’un rapport structuré à faire approuver par M. Ian pour suivre une structure appropriée pour l’étude. Impression de formulaires de consentement pour l’enregistrement vidéo, approuvés par l’UdeM.</h4> 
  </div>
  <div class="Progress 5 ">
    <h1>Semaine 8 (19 oct - 27 oct)</h1>
    <h3>Semaine de Lecture - Nous avion conduit l'etude avec success</h3>
    <h4>Défi : terminer l'étude le plus tôt possible pour pouvoir compléter les transcriptions à temps, commencer l'analyse et la présenter à M. Ian.</h4>
    <h4>Solution : réaliser toute l'étude en une seule journée, même si cela implique de rester tard à l'UdeM.</h4>
  </div>
  <div class="Progress 6 ">
    <h1>Semaine 9-10 (28 oct - 8 nov)</h1>
    <h3>Nous avons créé les transcriptions des vidéos prises durant l'étude afin d'effectuer une analyse quantitative futur sur le type de questions posées. Ian nous a fait part que le concept de "règles" est plutôt complexe et qu'il serait préférable de résoudre les problèmes progressivement. Nous devrions donc nous concentrer sur le concept de "gesturing" pour transmettre l'information. Le gesturing consiste à pointer un endroit pour connecter l'information verbale. Nous devons trouver un moyen de transmettre l'information par gesturing, qui est normalement une transmission en temps réel (vidéo), sous une forme itérable, donc par photo.</h3>
    <h4>Défis : transmettre les actions sur le canvas dans la transcription, adapter le projet pour passer de l'implémentation du concept de "règle" à celui de "gesturing" dans le système, et trouver la meilleure façon de transmettre l'information de "gesturing" à une IA.</h4>
    <h4>Solution : utiliser des crochets [] et des images pour indiquer les actions effectuées sur le canvas dans la transcription, modifier la tentative de conception du système pour passer des problèmes liés aux "règles" à ceux liés au "gesturing", et explorer les réponses des LLM selon les types de photos représentant des traces de "gesturing" qui produisent les meilleurs résultats.</h4>
  </div>
  <div class="semaine 7">
    <h1>Semaine 7</h1>
    <h3>Paragraph</h3>
  </div>
  <div class="semaine 8">
    <h1>Semaine 8</h1>
    <h3>Paragraph</h3>
  </div>
  <div class="semaine 9">
    <h1>Semaine 9</h1>
    <h3>Paragraph</h3>
  </div>
</div>


