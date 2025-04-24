$username = $_POST['username'];
$password = $_POST['password'];

$query = "SELECT * FROM users WHERE username = '1'='1 AND password = '1'='1
SELECT * FROM users WHERE username = '' OR '1'='1' AND password = '' OR '1'='1';