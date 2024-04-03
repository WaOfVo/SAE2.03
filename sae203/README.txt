Ce rapport est rédigé en Markdown, langage de balisage destiné à être converti en un autre format.

Pour compiler le fichier en format HTML ou PDF:
    0. Prérequis: Un terminal linux BASH, avec pandoc installé
    1. Créez un dossier fichier_final et placez y les fichiers de l'archive (images et rapport.md)
    2. Ouvrez un terminal (alt+T)
    3. Executez la commande suivante: pandoc -s --toc -f markdown -t <format> rapport.md -o fichier_final.<format>
       Cette commande va créer un fichier rapport.<format>, où <format> est le format de fichier que vous souhaitez (HTML, PDF, etc..).
    4. Ouvrez rapport.<format> dans un navigateur web.

Auteurs: Raphaël TAFANI, Hadrien MILO, Kellian SORY
Le: 14/03/2024

