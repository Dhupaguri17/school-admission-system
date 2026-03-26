# school-admission-system
&lt;?php $conn = new mysqli("localhost", "root", "", "school_admission"); $result = $conn->query("SELECT * FROM students");  while($row = $result->fetch_assoc()){     echo $row['name'] . " - " . $row['class'] . "&lt;br>"; } ?>
