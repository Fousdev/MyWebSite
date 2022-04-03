<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Traducteur Franco-Lokpa</title>
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="téléchargement.jpeg">
    <link rel="stylesheet" href="page.acceuil.css">
</head>

<body>
    <style>

    </style>

    <div class="entete">
        <div class="menu" id="menu" onclick="changer(this)">
            <div class="tiret1"></div>
            <div class="tiret2"></div>
            <div class="tiret3"></div>
        </div>
        <div class="span" id="span"> <span> Traducteur Franco-Lokpa</span></div>

    </div>
    <div id="interne" onclick="changer(this)">
        <div id="sous_entete">
            <div class="text-dark" style="font-size:40px ;" id="acceuil"><i class="fa fa-home"></i>Acceuil</div>
            <div class="apk"><button><a href="apk_info.html">A propos</a></button></div><br>
        </div>
        <div class="zone_traduction" id="traduc_zone">
            <span>Zone de traduction des mots</span>
        </div>
        <form class="zone_saisie" id="saisie" name="saisie" onsubmit="return traduire()">
            <input type="text" placeholder="Saisissez le mot à traduire" id="input" name="input">
            <button id="boutton">Traduire</button>
        </form>
        <div class="changement" id="changement">
            <div class="lokpa" style="color: yellowgreen; width: 13%;margin-left: 25%">LOKPA</div>
            <div class="roteur" id="roteur" style="font-size:25px; width: 10%;margin-left: 5%;" onclick="rotation()">
                <button class="roter" id="roter" style="background-color: rgb(14, 14, 51);color: white; ">
                    =>
                </button>
            </div>
            <div class="francais" style="color: yellowgreen; margin-right: 5%;">FRANCAIS</div>
        </div>
        <!--<form action="" id="form" name="form"><input id="input" name="input" type="search"
                placeholder="Pèèki lopka taa"></form>-->
    </div>
    </div>
    <div class="contenu" id="contenu">
        <ul id="ul">
            <li><a class="text-dark" style="font-size:40px ;"><i class="fa fa-home"></i></a><a href="page_Acceuil.html">
                    <span>Acceuil</span>
                </a></li>
            <li><a class="text-dark" style="font-size:40px ;"><i class="fa fa-cog"></i></a><a href="paramètres.html">
                    <span>Paramètres</span>
                </a></li>
            <li><a class="text-dark" style="font-size:40px ;"><i class="fa fa-question-circle"></i></a><a
                    href="aide.html"> <span>Aides</span>
                </a></li>
            <li><a class="text-dark" style="font-size:40px ;"><i class="fa fa-history"></i></a><a
                    href="contenu.html"><span>Historique</span></a></li>
            <li><a class="text-dark" style="font-size:40px ;"><i class="fa fa-book"></i></a><a
                    href=""><span>Apprendre</span></a></li>
            <li> <a class="text-dark" style="font-size:40px ;"><i class="fa fa-heart"></i></a><a
                    href=""><span>Favoris</span></a></li>
            <li><a class="text-dark" style="font-size:40px ;"><i class="fa fa-user"></i></a><a href=""><span>Se
                        Connecter</span></a></li>
            <li><a class="text-dark" style="font-size:35px ;"><i class="fa fa-times"></i></a><a
                    href=""><span>Quitter</span></a></li>
            <span class="oi" data-glyph="battery-full"></span>
        </ul>

    </div>
    <script src="page_acceuil.js"> </script>
    <script src="js/jquery-3.3.1.slim.min.js"></script>
    <script src="js/fontawesome-all.min.js"></script>
    <script src="js/bootstrap.bundle.min.js"></script>
    <script src="code_traduc.js"></script>
    <div id="recuperer" style="font-size: 0px;opacity: 0;"></div>
</body>

</html>
