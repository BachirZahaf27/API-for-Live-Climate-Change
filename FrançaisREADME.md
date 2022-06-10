# ALOS_act4.

##  I- Lien pour télécharger Code de API:

      https://github.com/BachirZahaf27/api1

## II-Structure des dossiers

```
├─── base de données
| ├─── utilisateurs.json
│ └─── journaux.json
└─── source
     ├─── API
     │ ├─── v1
     | | ├─── News.js
     │ │ └─── Journaux.js
     │ └─── v2
     | ├─── News.js
     │ ├─── Journaux.js
     │ └─── Utilisateurs.js
     ├─── vues
     | ├─── Contact.ejs
     │ ├─── index.ejs
     │ ├─── login.ejs
     | └─── registre.ejs
     ├─── essai
     | └─── test.js
     ├─── utilitaires
     | └─── validation.js
     ├─── .env
     ├─── serveur.js
     ├─── package.json
     ├─── package-lock.json
     ├─── demande de repos
     └─── node_models

```

## III-Comment lancer le projet :

1. Accédez au fichier src :

      `cd C:\\...\api1-master\src`

2. lancez l'application :

    `npm exécuter devStart`

5. Accès à l'application dans le navigateur :

    `localhost:3000`
    
  
 ## IV- Login :
 
 1. Cette page est créée avec `Bluma` pour l'utilisateur afin qu'il puisse se connecter au site Web de l'API, comme indiqué ci-dessous :
 
 ![image](https://user-images.githubusercontent.com/61596276/173075814-de2a4849-7aca-4604-abb3-af06d309657e.png)

2. Cette page est réactive, donc s'il y a une erreur, elle l'affichera comme ci-dessous :

![image](https://user-images.githubusercontent.com/61596276/173076332-83bca775-e19b-4cac-bace-932d0dab2471.png)
![image](https://user-images.githubusercontent.com/61596276/173076516-bbc14ec1-db21-47b3-820a-da922d1cc39b.png)

3. il inclut également un bouton pour créer un "nouveau compte si l'utilisateur n'en a pas", comme indiqué ci-dessous :

![image](https://user-images.githubusercontent.com/61596276/173076918-b3f9810a-9dc5-4799-b929-35fa9dfb70d1.png)



 ## V- SignUp :
 
 1. Cette page est créée avec `Bluma` pour l'utilisateur afin qu'il puisse créer un compte pour se connecter au site Web de l'API, comme indiqué ci-dessous :
 
![image](https://user-images.githubusercontent.com/61596276/173077299-55bc4f25-389a-417e-8e90-2878fc17fa94.png)

2. Cette page est réactive, donc s'il y a une erreur, elle l'affichera comme ci-dessous :

![image](https://user-images.githubusercontent.com/61596276/173077510-75f10a67-bd7f-4449-b0a0-71c95415140b.png)

3. il inclut également un bouton pour créer "Avez-vous déjà un compte", comme indiqué ci-dessous :

![image](https://user-images.githubusercontent.com/61596276/173077792-6434d48c-be78-4d49-bf83-4a8e402c0be6.png)



## VI- Index :

1. Cette page est faite avec `Bluma` pour l'utilisateur afin qu'il puisse accéder à tous les serveurs et aux informations sur cette API, comme indiqué ci-dessous :

![image](https://user-images.githubusercontent.com/61596276/173078319-cb8b6307-234a-4850-b36a-6d010214d6ec.png)
![image](https://user-images.githubusercontent.com/61596276/173078415-458fa55e-031a-421e-87ed-3496c0a56dad.png)

2. Comme vous pouvez le voir dans la page d'accueil il y a 2 services `newspapers` & `news` qui parlent du changement climatique, ainsi qu'une documentation faite avec `gitbook`.

3. Cette page `Contact` a été créée pour que l'utilisateur puisse contacter l'auteur afin qu'il puisse lui demander des autorisations, de l'aide...etc, comme ci-dessous :

![image](https://user-images.githubusercontent.com/61596276/173079165-7f1273e0-3413-4db4-8699-02041a6dd673.png)


 ## VII- Documentation :

       https://bachir-zahaf.gitbook.io/live-climate-change-api/
