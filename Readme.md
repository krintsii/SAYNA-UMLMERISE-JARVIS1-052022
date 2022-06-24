# SAYNA-UMLMERISE-JARVIS1-052022

<h3>Les différents acteurs dans le diagrammes sont :</h3> 

-proprietaires<br> 
-co-proprietaires<br> 
-membres<br> 
-visiteurs<br> 
-Objet connecter<br>


<h3>Les fonctionnalités pour chaque acteur :</h3>
-proprietaires: <li>Creation d'un domicile</li><br>
                <li>Modifications des utilisateurs</li><br>
-co-proprietaires: <li>Creation de nouvellec piece</li><br>
                    <li>Ajout d'un objet connecter</li><br>
                    <li>Mise en place d'un objet dans une piece</li><br>
-membres:<li>Recuperer la liste des pieces</li><br>
            <li>Recuperer de la liste des objets connecter</li><br>

-visiteurs:<li>Authentification</li>
    <h3>Les types de fonctionnalités:</h3>
    <style>
        table,
        th,
        td {
            border: 1px solid black;
        }
        .noborder {
            border: none;
        }
    </style>
    <table style="width:100%">
        <tr>
            <th>Acteurs</th>
            <th>Fonctionnalités</th>
            <th>Types de fonctionnalités</th>
        </tr>
        <tr>
            <td>propriétaires</td>
            <td>Creation d'un domicile,Modifications des utilisateurs</td>
            <td>Obligatoire</td>
        </tr>
        <tr>
            <td>Copropriétaires</td>
            <td>Creation de nouvellec piece,Ajout d'un objet connecter,Mise en place d'un objet dans une piece</td>
            <td>Obligatoire</td>
        </tr>
        <tr>
            <td class="noborder">membres</td>
            <td>Recuperer la liste des pieces,Recuperer de la liste des objets connecter</td>
            <td>Obligatoire</td>
        <tr>
            <td class="noborder"></td>
            <td>Mise en place d'un objet dans une piece,Modification d'un objet connecter</td>
            <td>Facultatifs</td>
        </tr>
        </tr>
        <tr>
            <td>visiteurs</td>
            <td>Authentification</td>
            <td>Obligatoire</td>
        </tr>
    </table>