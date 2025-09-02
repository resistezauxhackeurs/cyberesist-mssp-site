CYBERESIST — Site MSSP (HTML + Tailwind CDN)

Comment publier :
1) Déposez tout le dossier sur votre hébergement (Apache/Nginx/S3/…).
2) Le site utilise Tailwind via CDN (aucune build nécessaire).
3) Modifiez l'adresse email dans devenir.html si besoin.
4) Les couleurs d'accent reprennent le vert du logo (modifiable dans le <script> Tailwind).
5) Le logo est référencé en externe : https://cyberesist.com/wp-content/uploads/50333709-copie.png. Remplacez par un fichier local si vous préférez.

PAGES :
- index.html (landing partenaires)
- plateforme.html
- offres.html
- fonctions.html
- tarifs.html
- faq.html
- devenir.html (formulaire mailto)

python -m http.server 8080