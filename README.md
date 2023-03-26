<!DOCTYPE html>
<html>
    <head>
        <title>Laurennetagam.com</title>
        <meta charset='utf-8'>
        <link rel="stylesheet" type="text/css" href="style.css">
    </head>
    <body>
        <header>
            <h1>Bienvenu dans mon site perso "centre de vaccances"</h1>
            <h1>By Tagam Laurenne Lafortune</h1>
            <nav>
                <ul>
                    <li><a href="#">Accueil</a></li>
                    <li><a href="#">A propos de nous</a></li>
                    <li><a href="#">Activités</a></li>
                    <li><a href="#">Servives</a></li>
                    <li><a href="#">Evènements</a></li>
                    <li><a href="#">biographie</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </header>
        <main>
            <section class="A propos de nous">
                <h2>A propos de nous</h2>
                <p>J'ai toujours voulu creer un site qui met à la dispossition des visiteurs un centre de vaccances qui offre de nombreuses activités et services. Dans ce site j'ai ajouté le language de style CSS.</p>
            </section>
            <section class="Activités">
                <h2>Nos activités</h2>
                <p>Nous proposons des activités assez varier selons tous les goûts et tous les âges pour permettre a nos visiteurs de passer des excellents vaccances en famille ou entre amis.</p>
                <ul>
                    <li>piscine party</li>
                    <li>Randonnée</li>
                    <li>Match de football</li>
                    <li>Visite au musées</li>
                    <li>Balade</li>
                </ul>
            </section>
            <section class="Services">
                <h2>Nos services</h2>
                <p>Nous offrons une gamme complète de services pour que vous puissiez profiter pleinement de votre temps libre;</p>
                <ol>
                    <li>Location d'equipement sprotif</li>
                    <li>Responsable securité</li>
                    <li>Guide professionnels</li>
                    <li>Service de restauration</li>
                </ol>
            </section>
            <section class="evènements">
                <h2>Evènement à venir</h2>
                <p>Ne manquez pas nos evènements à venir. Restez à jour en consultant nos agenda:</p>
                <a href="#">Calendrier des evènements</a>
            </section>
             <section class="Biographie">
                <h2>Ma biographie</h2>
                <p>Laurenne Lafortune Tagam est une étudiante de l'université de Yaoundé 1 né le 16 février. passionné par l'entrepreunariat et par l'informatique depuis son jeûne enfance, elle à toujours eu un esprit créatif qui l'a poussé à crer son premier site internet a l'occation d'un TP0 alors qu'elle est encore étudiante en filière ICT4D.</p>
            </section>
            <section class="contact">
                <h2>Contact</h2>
                <p><a href="mailto:Laurennefortune@gmail.com"> Laurennefortune@gmail.com</a></p>
                <p>Melen - Yaoundé</p>
                <p>(+237) 658505224</p>
            </section>
        </main>
        <footer>
            <p>&copy 2023 Copyritht Mon site perso tout droits reservés</p>
        </footer>
    </body>
</html>
header{
	background: #66b3ff;
}
h1{
	color: #fff;
	text-align: center;
	padding: 20px;
}
nav ul {
	list-style: none;
	margin: o;
	padding: 0;
	display: plex;
	justify-content: center;
}
nav li{
	margin: 0 20px;
}
nav a{
	color: #fff;
	text-decoration: none;
	font-zise: 18px;
}
nav a:hover{
	color: #ff9933;
}
/*style pour les sections*/
section{
	padding: 40px;
	margin: $0px 0;
	background: #fff;
	box-shadow: 0px 2px 10px #ccc;
}
h2{
	font-size: 36px;
	margin-top: 0;
}
p{
	font-size: 18px;
	line-height: 1.6;
	margin-bottom: 20px;
}
ol{
	liste-style: decimal;
}
a{
	color: #ff9933;
	text-decoration: none;
}
a:hoder{
	text-decoration: underline;
}
/*style pour le footer*/
footer{
	background: #ccc;
	padding: 20px;
	text-align: center;
}


