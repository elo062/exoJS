```javascript
//REVISIONS
// Declarez une variable nommée "boucler" contenant true
var boucler = true

// Declarez un tableau members contenant Aida67, lapie002, anneserrano, Jennysmille, nunkabuk, RCosson, kaonb-ax, FerEmilie, crazychouwi, KiluaZoldyc, patatobeur, Sam11360, elo062, hermeline, Biciclet,

var members = ["Aida67", "lapie002", "anneserrano", "Jennysmille", "nunkabuk", "RCosson", "kaonb-ax", "FerEmilie", "crazychouwi", "KiluaZoldyc", "patatobeur", "Sam11360", "elo062", "hermeline", "Biciclet"];
document.getElementById("check").addEventListener("click",function(){
    // SI la variable boucler vaut true ALORS
    if (boucler){
      // Bouclez sur le tableau que vous avez déclaré ci-dessus
      for (var i = 0; i < members.length; i++) {
      //console.log(i);
      // Mettre un switch pour qu'au moment où la boucle se trouve sur votre pseudo cela ajoute "Affiche " devant votre pseudo dans la console et sur l'écran et par defaut seulement le pseudo des autres

        var pseudo = members[i];
        switch (pseudo) {
            case "elo062":


                //créer un élément div qu'on met dans une variable

                //chercher la div avec l'id check à mettre aussi dans une variable

                //prendre la div et rajouter du contenu inner.html
                var divcheck = document.getElementById("check");
                var newdiv = document.createElement("div");
                newdiv.innerHTML = "<p>Affiche " + pseudo + "</p>"
                divcheck.appendChild(newdiv);
                console.log("Affiche "+ pseudo);
    //prendre cette div et appendchild(nouvellediv)

            break;
            default:
                //console.log(pseudo);
                //alert(pseudo);
                var divcheck = document.getElementById("check");
                var newdiv = document.createElement("div");
                newdiv.innerHTML = "<p>" + pseudo + "</p>"
                divcheck.appendChild(newdiv);
                console.log(pseudo);
        }
      }
    }

    // FIN REVISIONS
});


// COURS AJAX
  // AJAX Jquery .ajax() ou .get()
  // Faites une requete vers l'API REST de Github pour récupérer les informations de votre compte


// FIN COURS AJAX


```
