╔══════════════════════════════════════════════════════╗
║           CARRÉ MAGIQUE — Installation PWA           ║
╚══════════════════════════════════════════════════════╝

CONTENU DU DOSSIER
──────────────────
  index.html        → Application complète
  manifest.json     → Configuration PWA (nom, couleurs, icône)
  sw.js             → Service Worker (mode hors-connexion)
  icons/
    icon-192.svg    → Icône application (écran d'accueil)
    icon-512.svg    → Icône haute résolution (splash screen)
    favicon.svg     → Favicon navigateur
  README.txt        → Ce fichier

INSTALLATION SUR TÉLÉPHONE
────────────────────────────

▶ ANDROID (Chrome / Edge)
  1. Ouvrez index.html dans Chrome
     (ou hébergez le dossier sur un serveur local)
  2. Un bandeau "Installer Carré Magique" apparaît en bas
  3. Appuyez sur "Installer"
  4. L'app s'ajoute sur l'écran d'accueil avec son icône ◆

▶ iPhone / iPad (Safari)
  1. Ouvrez index.html dans Safari
  2. Appuyez sur l'icône Partager (carré avec flèche ↑)
  3. Faites défiler → "Sur l'écran d'accueil"
  4. Appuyez "Ajouter"

▶ OPTION SERVEUR LOCAL (recommandé pour accès hors-ligne complet)
  - Installez Python (déjà présent sur Mac/Linux)
  - Dans le dossier décompressé, lancez :
      python3 -m http.server 8080
  - Ouvrez Chrome → http://localhost:8080
  - Installez via le bandeau

UTILISATION HORS-CONNEXION
───────────────────────────
  Une fois installée, l'application fonctionne
  ENTIÈREMENT sans connexion Internet.
  Toutes les données (120 grilles × 9 boutons)
  sont embarquées dans l'application.

FONCTIONNALITÉS
───────────────
  • 9 boutons Modulo (120 grilles chacun)
  • Saisie du tirage officiel (5 numéros)
  • Témoin rouge clignotant sur les boutons concernés
  • Vérification automatique des gains
  • Cumul des gains par tirage
  • Barème : 5 bons=10 grilles / 4=6 / 3=3 / 2=1
  • Affichage détaillé des 120 grilles avec numéros surlignés
