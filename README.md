# TP3Web
<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dans Poudlard</title>
</head>
<style>
    nav {
        /*Déformation de page*/
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
    }

    nav ul {
        /* barre rouge */
        display: flex;
        list-style-type: none;
        background-color: rgb(145, 22, 22);
        width: 100%;
        height: 25px;
        padding: 30px;
        font-size: 10px;
        margin-top: -8px;
        margin-left: -8px;
        margin-right: -8px;
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
    }

    nav ul a {
        /*écriture menu nav*/
        font-size: 1.2rem;
        text-decoration: none;
        font-family: Arial, Helvetica, sans-serif;
        margin-left: 170px;
    }

    .Accueil {
        font-weight: bold;
        color: rgb(214, 195, 89);
    }

    .VisiterPoudlard {
        font-weight: bold;
        color: rgb(255, 255, 255);
    }

    .SouvenirPoudlard {
        font-weight: bold;
        color: rgb(214, 195, 89);
    }

    .Contact {
        font-weight: bold;
        color: rgb(214, 195, 89);
    }

    .header {
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
    }

    .logo {
        margin-top: -90px;
        margin-left: 10px;
    }
    h1{
        color: rgb(160, 160, 60);
        font-family: 'Courier New', Courier, monospace;
    }
    p{
        color: white;
    }
</style>

<body>
    <!-- Barre du haut  -->
    <table>

        <body>
            <header>
                <nav>
                    <ul>
                        <li><a href="../index.html" class="Accueil">Accueil</a></li>
                        <li><a href="VisiterPoudlard.html" class="VisiterPoudlard">Visiter Poudlard</a></li>
                        <li><a href="SouvenirPoudlard.html" class="SouvenirPoudlard">Souvenir de Poudlard</a></li>
                        <li><a href="Contact.html" class="Contact">Contact</a></li>
                    </ul>
                </nav>
                <div class="logo">
                    <img src="../image/logo.png" alt="logo" width="85px">
                </div>
            </header>
        </body>
    </table>
    <div class = "contenue1">
        <div class = "circle1"></div>
        <h1>LA CHAMBRE DES SECRETS</h1>
        <p>La Chambre des secrets est un lieu mythique de Poudlard car personne ne sait ou elle se trouve. Seules les personnes parlant le Fourchelang peuvent y entrer.</p>
        <h1>DESCRIPTION</h1>
        <p>Il s'agit d'une longue salle humide et faiblement éclairée par une limière verdâtre. 
            D'immenses piliers de pierre autour desquels sont sculptés des serpents s'élevent vers un plafond obscur.
             On découvre au fond de la salle une immense statue représentant Salazar Serpentard, le fondateur de la chambre.</p>
             <h1>LOCALISATION ET ACCÈS</h1>
             <p> La Chambre se cache dans les profondeurs de Poudlard. On y accède par les anciennes toilettes des filles qui se trouvent au deuxième étage de château.
                L'entrée se situe plus précisement derrière un des éviers, celui ou l'on appercoit un serpent gravé sur le robinet.</p>
    </div>
    <div class = "contenue2">
        <div class = "circle2"></div>
        <h1>LA GRANDE SALLE</h1>
        <p>La Grande Salle est la principale pièce commune de l'école. Les étudiants y mangent leurs repas, y recoivent leurs hiboux quotidien...De nombreux évènements s'y déroulent tout au long de l'année.</p>
        <h1>DESCRIPTION</h1>
        <p>Cette salle est l'une des plus grandes du château. En temps normal, les quatre longues tables ou les élèves prennent leurs repas sont installées côte a côte.
            Au fond de la pièce se trouve la Grande Table (celle des professeurs). Mais il arrive qu'elle prenne une autre disposition lors de certains évènements(bals de noel, examens...).
        Le plafond est magique, il reflète le temps qu'il fait a l'extérieur et des bougies colantes éclairent la salle.
    Il y a de longues fenêtres sur les côtés de la Grande Salle et une grande fenêtre derrière la table des professeurs.</p>
             <h1>LOCALISATION ET ACCÈS</h1>
             <p> La Grande Salle se trouve au rez-de-chaussée de Poudlard. On y accède depuis le Hall d'entrée par deux grandes portes en bois.</p>
    </div>
    <div class = "contenue3">
        <div class = "circle3"></div>
        <h1>LA FORET INTERDITE</h1>
        <p>La Forêt interdite est une immense forêt bordant l'intérieur de l'enceinte du château Poudlard. Comme son nom l'indique, il est interdit aux élèves de l'école
            de pénétrer a l'intérieur - excepté dans le cadre de punitions ou bien encore des cours de soins aux créatures magiques. Au vu du nombre impressionnant de créatures s'étant établies
            dans cette forêt, il semble évident que peu d'élèves souhaitent s'y aventurer.
        </p>
        <h1>DESCRIPTION</h1>
        <p>C'est une énorme forêt, bordant une partie de Poudlard, dont les arbres qui en font le contour sont assez espacés et clairs. Mais plus
            loin dans la forêt les arbres deviennent plus sérrés, plus sombres, la lumière du jour a plus de mal a passer et des tas de créatures en plus de buissons et plantes
            épineuses se mettent en travers du chemin des voyageurs lorsqu'ils s'enfoncent trop loin dans la forêt.
        </p>
             <h1>LOCALISATION ET ACCÈS</h1>
             <p> Cette forêt se trouve en partie derrière la cabane de Hagrid. On y accède par le parc de Poudlard.</p>
    </div>
    <style>
        body{
            margin: 0;
            padding: 0;
            font-family: sans-serif;
        }
        .contenue1{
            position: absolute;
            top: 50%;
            left: 83%;
            transform: translate(-50%,-50%);
            width: 600px;
            padding: 30px;
            background:rgb(145, 22, 22);
            box-sizing: border-box;
            border-radius: 10px;
            box-shadow: 0 15px 50px rgba(0,0,0,0.2);
        
        }
        .contenue2{
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            width: 600px;
            padding: 30px;
            background:rgb(145, 22, 22);
            box-sizing: border-box;
            border-radius: 10px;
            box-shadow: 0 15px 50px rgba(0,0,0,0.2);
        
        }
        .contenue3{
            position: absolute;
            top: 50%;
            left: 17%;
            transform: translate(-50%,-50%);
            width: 600px;
            padding: 30px;
            background:rgb(145, 22, 22);
            box-sizing: border-box;
            border-radius: 10px;
            box-shadow: 0 15px 50px rgba(0,0,0,0.2);
        
        }
        

        .circle1{
            width: 200px;
            height: 200px;
            background-image: url("../image/chambre_des_secrets.png");
            background-size: 100% 100%;
            border-radius: 50%;
            float: left;
            shape-outside: circle();
            margin:30px;
        }
        .circle2{
            width: 200px;
            height: 200px;
            background-image: url("../image/grande_salle.jpg");
            background-size: 100% 100%;
            border-radius: 50%;
            float: left;
            shape-outside: circle();
            margin:30px;
        }
        .circle3{
            width: 200px;
            height: 200px;
            background-image: url("../image/foret.jpg");
            background-size: 100% 100%;
            border-radius: 50%;
            float: left;
            shape-outside: circle();
            margin:30px;
        }
    </style>
</body>
</html>
