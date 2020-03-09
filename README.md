# atelier1-j2ee: Créer et déployer une première Servlet
1.	Modifier le code de la Servlet "BonjourServlet" pour permettre de compter et d'afficher le nombre de fois qu'elle a été appelée ( Afficher par exemple un message <<Cette Servlet a été accédée " + compteur + " fois.>>) 
2.	Créez une nouvelle classe Servlet "BonsoirServlet" et Configurer cette Servlet via les annotations pour qu’il soit accessible en GET via le fragment /bonsoir.
3.	Créez une nouvelle classe Servlet "RediregeServlet" qui redirige l’utilisateur vers le site Internet externe http://www.isetjb.rnu.tn/ en implémentant la méthode doGet(). Configurer cette Servlet soit par annotations, soit dans le descripteur de déploiement pour être accessible via /redirect.
4.	Créer une nouvelle classe Servlet "ParamServlet" qui permet de lire et d’afficher les paramètres de requête de l'URL http://localhost:8080/param?prenom=maysem&age=9. 

Vérifier l’affichage des résultats avec les URL suivantes :
 a. http://localhost:8080/param?age=9&prenom=maysem
 
 b. http://localhost:8080/param?age=9
 
 c. http://localhost:8080/param?prenom=maysem
 
 d. http://localhost:8080/param

