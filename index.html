<!DOCTYPE html>
<html>
<head>
  <title>Formulaire d'inscription</title>
  <style>
    .container {
      max-width: 400px;
      margin: 0 auto;
      padding: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .form-group {
      margin-bottom: 10px;
    }
    .form-group label {
      display: block;
      font-weight: bold;
    }
    .form-group input {
      width: 100%;
      padding: 5px;
      border-radius: 3px;
      border: 1px solid #ccc;
    }
    .btn-submit {
      display: block;
      width: 100%;
      padding: 10px;
      background-color: #4CAF50;
      color: #fff;
      border: none;
      cursor: pointer;
      border-radius: 3px;
    }
    .table-container {
      margin-top: 20px;
    }
    .table-container table {
      width: 100%;
      border-collapse: collapse;
    }
    .table-container th, .table-container td {
      padding: 5px;
      border: 1px solid #ccc;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Formulaire d'inscription</h2>
    <form action="enregistrer.php" method="POST">
      <div class="form-group">
        <label for="nom">Nom:</label>
        <input type="text" name="nom" id="nom" required>
      </div>
      <div class="form-group">
        <label for="ville">Ville:</label>
        <input type="text" name="ville" id="ville" required>
      </div>
      <button type="submit" class="btn-submit">Enregistrer</button>
    </form>
  </div>

  <div class="table-container">
    <h2>Enregistrements</h2>
	<?php
if (isset($_POST['nom']) && isset($_POST['ville'])) {
  $nom = $_POST['nom'];
  $ville = $_POST['ville'];

  // Connexion à la base de données
  $servername = "localhost";
  $username = "votre_nom_d_utilisateur";
  $password = "votre_mot_de_passe";
  $dbname = "user";

  $conn = new mysqli($servername, $username, $password, $dbname);
  if ($conn->connect_error) {
    die("La connexion à la base de données a échoué : " . $conn->connect_error);
  }

  // Insertion des données dans la table "personne"
  $sql = "INSERT INTO personne (nom, ville) VALUES ('$nom', '$ville')";
  if ($conn->query($sql) === TRUE) {
    echo "Enregistrement effectué avec succès.";
  } else {
    echo "Erreur lors de l'enregistrement : " . $conn->error;
  }

  $conn->close();
} else {
  echo "Veuillez remplir tous les champs du formulaire.";
}
?>

  </div>
</body>
</html>
