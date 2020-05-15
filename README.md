# inscription
un programme HTML pour faire une inscription
<!DOCTYPE html>
<html >

<head>
<title>ajouter cheval</title>
<meta charset="UTF-8">
<style>
 
    body{
        background-image: url(aaa.jpg);
    }
    td
        {color:white ;
        }
        b{ color:white;}

    </style>
</html>
</head>

<body >
     
    <form>
        <table>
            <tr>
                <td>ID: <span style="color : red;">*</span></td>
                <td><input type="text" placeholder="ID" name="ID" minlength="3" maxlength="15" required/></td>
              </tr> 
             <tr>   
                <td>Nom:<span style="color : red;">*</span></td>
    <td><input type="text" placeholder="Nom" name="Nom" minlength="3" maxlength="15" required/></td>
    </tr>
    <tr>           
    <td>Date de naissance:<span style="color : red;">*</span></td>
    <td><input type="date" name="Date de naissance"required/></td>  
    </tr>        
    <tr>
                <td>Race:<span style="color : red;">*</span></td>
                <td> <input type="Race" placeholder="Race" name="Race"required/></td>  
            </tr>
            <tr>
                <td>Boxe:<span style="color : red;">*</span></td>
                <td> <input type="Boxe" placeholder="Boxe" name="Boxe"required/></td>  
            </tr>
        </table>
            <button type="reset">annuler</button>
            <button type="submit">enregistrer</button>
        </table><br>

</body>

</html>
