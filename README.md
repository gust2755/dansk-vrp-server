# bananRP-Filer
 Dette er nogle simple clean server filer med henblik på at optimere måden danske vRP servere køre på


# Optimering
- Hele serverens SQL system er baseret på oxmysql istedet for det tidligere kendte og outdatede system vrp_mysql
- Tilføjet et simpelt webhook system som giver mulighed for at man nemt kan gå ind og configurere sine webhook (vrp>cfg>webhooks)
- Fjernet bugs og fejl som kunne misbruges af moddere herunder (vrp_trucker, vrp_bilskrot, vrp_mysql og andre små ting)
- Fjernet duplikerings fejl med Tag Våben
- Optimeret responsen mellem database og server så såkaldte "vrp fejl" ikke skulle ske for fremtiden
- Tilføjet små ændringer til UI for at forbedrer oplevelse
- Tilføjet advarsel system under admin menuen
- Tilføjet en command til at revive alle, /revivealle
- Tilføjet en command til at unbanne alle (kun id 1 kan) /unbanalle
- Tilføjet impound system, så politiet kan impounde andres køretøjer
- Tilføjet indbrud system hvor man kan modtage våben og andre ting
- Optimeret vrp_lscutoms så den fungere bedre og fylder mindre i database
- Tilføjet anticheat for at stoppe modders
