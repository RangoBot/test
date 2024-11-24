<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Formulation d'étudiants</title>
  <style>
    /* Style for the footer text */
    .footer-text {
      position: fixed;
      bottom: 10px;
      left: 10px;
      font-size: 10px; /* Small font size */
      color: #555; /* Light gray color */
    }
  </style>
</head>
<body>
  <h2>Formulation d'étudiants</h2>
  <form>
    <label for="name">Nom :</label>
    <input type="text" id="name" name="name" required><br><br>
    
    <label for="prenom">Prénom :</label>
    <input type="text" id="prenom" name="prenom" required><br><br>
    
    <label for="date-naissance">Date de naissance :</label>
    <input type="date" id="date-naissance" name="date-naissance" required><br><br>
    
    <label for="email">Email :</label>
    <input type="email" id="email" name="email" required><br><br>
    
    <label for="mot-de-pass">Mot de passe :</label>
    <input type="password" id="mot-de-pass" name="mot-de-pass" required><br><br>
    
    <label for="age">Âge :</label>
    <input type="number" id="age" name="age" required><br><br>
    
    <label>Choisir votre année académique :</label><br>
    <input type="checkbox" id="l1" name="specialist" value="L1">
    <label for="l1">L1</label><br>
    
    <input type="checkbox" id="l2" name="specialist" value="L2">
    <label for="l2">L2</label><br>
    
    <input type="checkbox" id="l3" name="specialist" value="L3">
    <label for="l3">L3</label><br>
    
    <input type="checkbox" id="m1" name="specialist" value="M1">
    <label for="m1">M1</label><br>
    
    <input type="checkbox" id="m2" name="specialist" value="M2">
    <label for="m2">M2</label><br><br>
    
    <label>Langages de programmation (choisir un ou plusieurs) :</label><br>
    <input type="checkbox" id="c" name="language" value="C">
    <label for="c">C</label><br>
    
    <input type="checkbox" id="javascript" name="language" value="JavaScript">
    <label for="javascript">JavaScript</label><br>
    
    <input type="checkbox" id="cpp" name="language" value="C++">
    <label for="cpp">C++</label><br>
    
    <input type="checkbox" id="python" name="language" value="Python">
    <label for="python">Python</label><br><br>
    
    <button type="reset">Réinitialiser</button>
    <button type="submit">Envoyer</button>
  </form>

  <!-- Footer text -->
  <div class="footer-text"># created by soundous</div>
</body>
</html>
