// ==UserScript==
// @name        Trancador de Irregular :D
// @namespace   @Gatanjinha
// @include     http://atelier801.com/topic?f=*
// @version     0.0.2
// @author      Gatanjinha
// @grant       none
// @description Usei o script da Racola feito por Mumich como base, só para creditar.
// ==/UserScript==

$(document).ready(function(){
    irregular();
});

function irregular() {
    var element = document.getElementById("outils_message_reponse");
    var racoHTML = element.innerHTML;
    console.log(element.innerHTML);
    element.innerHTML = racoHTML + '<br/>';
    var raContainer = document.createElement('div');
    raContainer.className = "btn-group groupe-boutons-barre-outils";
    var racoButton = document.createElement('button');
    racoButton.className = "btn btn-reduit";
    racoButton.type = "button";
    racoButton.setAttribute("onclick","ajouterBBCode('message_reponse', '[p=center][b][color=#ff7bb0]Tópico trancado. Motivo:[/color][/b] [color=#ffbdd7]Tópico irregular.[/color] [img]http://www.picgifs.com/mini-graphics/mini-graphics/bears/mini-graphics-bears-625378.gif[/img][/p]', '', 6);");
    racoButton.title = "Irregular";
    racoButton.innerHTML = '<font color="#ff7bb0">Irregular</font>';
    raContainer.appendChild(racoButton);
    element.appendChild(raContainer);
}
