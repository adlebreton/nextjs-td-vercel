4: vercel -v  
5: npm init  
6: vercel  
7: vercel list td-vercel-node  
8: vercel logs td-vercel-node-rmp5o5ffl.vercel.app  
9: vercel inspect td-vercel-node-rmp5o5ffl.vercel.app permet d'afficher les informations sur un déploiement  
10: défini un cadre déexecution pour l'appli  
11: vercel env add  
12: vercel env ls  
13: ce sont des variables secrètes, utilisées pour des mot de passe, etc...  
15: vercel secret add second_secret_var thisisanotherpassword  
16: Production, Preview et Development, ils sont utilisé dans les différents stades d'une projet, development pour tester le code en cours de dévelopement, preview pour le code dit en beta, et Production pour le code stable mit a disposition du public  
18: https://nextjs-vercel-omega.vercel.app/  
19: un pull permet de demander une autorisation de merge du code dans la branche principale  
20: vercel détecte le merge et pousse en preview ou en production  
21: master est la branche git qui correspond a l'environement de production, l'interet du pull est de pouvoir travailler a plusieur, sans ecraser le code d'une autre personne  
22: permet d'être héberger sur le cloud  
