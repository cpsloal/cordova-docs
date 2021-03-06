---
license: >
    Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.
---

# Plugin API

Cordova est livré avec un ensemble minimal d'API, et projets ajoutent quelles API supplémentaire dont ils ont besoin grâce à des plugins.

Vous pouvez rechercher parmi tous les plugins existants en utilisant le [Plugin Registry][1].

 [1]: http://plugins.cordova.io/

L'ensemble traditionnel de Cordova plugins sont comme suit :

*   [État de la batterie][2]
    
    > Surveiller l'état de la batterie de l'appareil.

*   [Appareil photo][3]
    
    > Capturer une photo en utilisant la caméra de l'appareil.

*   [Contacts][4]
    
    > Travailler avec la base de données contacts périphériques.

*   [Dispositif][5]
    
    > Recueillir de l'information spécifique de périphérique.

*   [Mouvement de dispositif (accéléromètre)][6]
    
    > Puiser dans le détecteur de mouvement de l'appareil.

*   [Dispositif Orientation (boussole)][7]
    
    > Obtenir de la direction qui pointe vers l'appareil.

*   [Boîtes de dialogue][8]
    
    > Notifications de l'appareil visuel.

*   [Système de fichiers][9]
    
    > Crochet dans le système de fichier natif via JavaScript.

*   [Transfert de fichiers][10]
    
    > Crochet dans le système de fichier natif via JavaScript.

*   [Géolocalisation][11]
    
    > Sensibilisez votre emplacement de l'application.

*   [Mondialisation][12]
    
    > Permettre la représentation d'objets spécifiques aux paramètres régionaux.

*   [InAppBrowser][13]
    
    > Lancer URL dans une autre instance du navigateur en app.

*   [Media][14]
    
    > Enregistrer et lire des fichiers audio.

*   [Capture de médias][15]
    
    > Capturer les fichiers multimédias à l'aide des applications de capture pour le multimédia de l'appareil.

*   [Informations réseau (connexion)][16]
    
    > Vérifier rapidement l'état du réseau et informations de réseau cellulaire.

*   [SplashScreen][17]
    
    > Afficher et masquer l'écran de démarrage des applications.

*   [Vibration][18]
    
    > Une API à vibrer l'appareil.

 [2]: https://github.com/apache/cordova-plugin-battery-status/blob/master/doc/index.md
 [3]: https://github.com/apache/cordova-plugin-camera/blob/master/doc/index.md
 [4]: https://github.com/apache/cordova-plugin-contacts/blob/master/doc/index.md
 [5]: https://github.com/apache/cordova-plugin-device/blob/master/doc/index.md
 [6]: https://github.com/apache/cordova-plugin-device-motion/blob/master/doc/index.md
 [7]: https://github.com/apache/cordova-plugin-device-orientation/blob/master/doc/index.md
 [8]: https://github.com/apache/cordova-plugin-dialogs/blob/master/doc/index.md
 [9]: https://github.com/apache/cordova-plugin-file/blob/master/doc/index.md
 [10]: https://github.com/apache/cordova-plugin-file-transfer/blob/master/doc/index.md
 [11]: https://github.com/apache/cordova-plugin-geolocation/blob/master/doc/index.md
 [12]: https://github.com/apache/cordova-plugin-globalization/blob/master/doc/index.md
 [13]: https://github.com/apache/cordova-plugin-inappbrowser/blob/master/doc/index.md
 [14]: https://github.com/apache/cordova-plugin-media/blob/master/doc/index.md
 [15]: https://github.com/apache/cordova-plugin-media-capture/blob/master/doc/index.md
 [16]: https://github.com/apache/cordova-plugin-network-information/blob/master/doc/index.md
 [17]: https://github.com/apache/cordova-plugin-splashscreen/blob/master/doc/index.md
 [18]: https://github.com/apache/cordova-plugin-vibration/blob/master/doc/index.md

Non anglais traductions de ces documents plugin se trouvent en regardant les anciennes versions de la documentation de Cordova. Utilisez le menu déroulant en très haut à droite de ce site les versions.
