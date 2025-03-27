# CEFP M3 EAC2 Selenium Tester
## Exercici personalitzat de test per a l'EAC2
per Enric Mieza Sánchez - dimarts, 25 de març 2025, 11:47
Benvolgudes,

us enviaré tot seguit un exercici personalitzat per a resoldre amb Selenium i Django dins l'EAC2.
Si llegiu l'enunciat de l'EAC2 veureu que, en aquest, ja posem la creació d'un superusuari "isard". L'exercici que se us proposa cal resoldre'l amb instruccions de Selenium, és a dir, automatitzant cada pas que feu per tal que el faci la màquina amb el browser de forma automàtica a l'engegar el test.

Per tant, si l'enunciat diu "crea un usuari de staff sense cap permís", aquest usuari NO el podeu fer amb instruccions pròpies de Django, com "User.objects.create" o similars. S'ha de fer amb instruccions Selenium amb uns passos que serien quelcom com:
1. Logar-vos com a superadmin (usuari isard, ja el tindrem creat)
2. Clicar l'enllaç o botó per crear usuari.
3. Introduir les dades del nom d'usuari i contrasenya.
4. Passar de pàgina.
5. Activar la casella "staff".
6. Acabar la creació de l'usuari.

Si teniu cap dubte, podeu preguntar en aquest mateix fil del fòrum.
Salutacions cordials,
Enric
