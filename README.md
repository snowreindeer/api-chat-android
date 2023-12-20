# Uvod
Sprva je bila glavna ideja integracija novega modela LLM iz Googla **"Gemini"**. To je sicer uspelo, a dejstvo je, da so vsi Googlovi produkti s področja strojnega učenja trenutno na voljo samo v ZDA in niso na voljo v Evropski uniji. Prednost so širše zmožnosti modela (vizualna obdelava) in tudi dejstvo, da je (zaenkrat) brezplačen. Slaba stran je nedostopnost v Evropski uniji (samo s pomočjo VPN-ja).

## Kako izgleda studio:
![photo_2023-12-20_02-20-50.jpg](images%2Fphoto_2023-12-20_02-20-50.jpg)
Za povezavo modela morate dodati:

`gradle
dependencies {
implementation("com.google.ai.client.generativeai:generativeai:0.1.1")
}`

Za prikaz uporabe chatbota je smiselno ustvariti simulacijo chat-a z uporabo API-ja podjetja OPEN AI. Prednosti vključujejo:
- Enostavnejša koda
- Hitrejše generiranje odziva
- Uporabniška pogodba vsebuje manj klavzul o prenosu informacij
- Stabilnost modela (ni nov)
- Na voljo v Sloveniji

Slabosti pa so:
- Plačljivo (približno 15 $ na mesec)
- Informacije so omejene do leta 2022
- Ni tako širokega vizualnega vmesnika
- Ni "ekosistema", kot je Google

Po zadnjih razpoložljivih podatkih ima ChatGPT trenutno približno 180,5 milijona uporabnikov.

## Repozitorij
Repozitorij nudi primer uporabe chatbota v projektu Android Studio.
![Screenshot 2023-12-20 020941.png](images%2FScreenshot%202023-12-20%20020941.png) ![Screenshot 2023-12-20 101401.png](images%2FScreenshot%202023-12-20%20101401.png)

## Malo o podjetju
OpenAI je velika organizacija z ekipo razvijalcev in raziskovalcev. Redno objavljajo posodobitve in izboljšave za svoje modele. Najnovejši popravki in posodobitve so običajno dokumentirani na uradnih blogih in repozitorijih OpenAI na platformah, kot je GitHub. To tehnologijo je mogoče uporabiti v številnih aplikacijah, lahko odgovarja na vprašanja, pomaga uporabnikom pri ustvarjanju življenjepisov, odgovarja na vprašanja o vremenu in še veliko več. ChatGBT ponuja tudi orodje, ki bo pomagalo ustvariti nekakšen "forum", ki bo omejil uporabnike in jim omogočil samo postavljanje vprašanj, ki se nanašajo na aplikacijo.

# Zaključek
Tako so chatboti zelo uporabna tehnologija, ki jo je vsekakor treba upoštevati in jo po možnosti vgraditi v aplikacijo.
