# Sexism_Twitter_French
French corpus annotated for sexism detection composed of about 2000 tweets.

*** Annotation guidelines ***

Labels:

- Category=0 : 	Tweets non mysogines n'utilisant de pas de langage abusif. On peut néanmoins retrouver certains mots-clés
				abusifs dans des discours rapportés visants à dénoncer d'autres comportements abusif/mysogine.

- Category=1 : 	Tweets non mysogines mais avec du langage abusif. On y retrouve donc des messages insultants, des moqueries,
				et aussi de l'utilisation de smileys insultants.

- Category=2 : 	Tweets à caractère mysogine. On utilise comme définition : discours véhiculant des stéréotypes, essayant de
				montrer une supériorité masculine, porteur de menaces violentes ou de harcèlement sexuel, manquant de respect
				aux femmes de façon général, ou rejetant la responsabilité des hommes.

- Category=? :	Cas à part où le sens du tweet n'est vraiment pas clair, ou où sons sens n'est pas vraiment compréhensible
				sans le contexte où il a été posté.



Exemples de quelques cas un peu difficiles:

"@vpecresse Sale conne" : 	Revient assez souvent ; j'ai choisis de placer ce genre de tweets dans la catégorie 1 bien que 
							selon moi, leur banalité tend à montrer un fond assez mysogine.

"Mais pecresse cette grosse conne de quoi elle se mêle la elle est même pas au pouvoir ferme ta gueule ma soeur" : 
							Ici en revanche on a selon moi une portée bien plus misogyne avec toujours la même insulte 
							"grosse conne" mais accompagnée de "ferme ta gueule ma soeur". J'ai donc mis ce tweet
							dans la catégorie 2.

"Vu ses réponses, je me demande: Anne Hidalgo est une candidate à la présidentielle ou à miss France ?" :
							Beaucoup de tweets comparent les femmes politique à misse France, souvent pour critiquer
							les propos de leurs discourts jugés "niais". Quand la comparaison est aussi directe que
							dans cet exemple, j'ai placé ces tweets dans la catégorie 2.

"'@loichervepublic @YvesPDB @Senat Ce qui serait intéressant à présent c’est d’interroger à nouveau la miss #Pecresse
 sur cette question… elle qui était si pro #PassVacinal" :
 							Là en revanche la comparaison est moins directe. J'ai donc
 							classifié ce tweet dans la catégorie 0.
