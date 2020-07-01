<!Doctype html>
<html lang='zh-tw'>

<head>
    <meta charset="utf-8" />
    <title>Yshua's Web</title>
</head>

<body>
    <form method="post" action="index.php">
        <div id="insert_comm" class="insert_comm" style="text-align:center;">
            <p>Username :
                <input type="text" name="user" id="user" required />
            </p>
            <p>Email :
                <input type="text" name="email" id="email" required />
            </p>
            <p>Phone :
                <input type="text" name="phone" id="phone" required />
            </p>
            <p>Comment :
                <textarea name="comment" id="comment" row="10" cols="30" required></textarea>
            </p>
            <input type="submit" name="submit" value="Submit" />
            <input type="reset" name="send" value="Reset" />
            
        </div>

        <br />
        <br />

        <div id="comm_all">

        </div>
    </form>
    </hr>
</body>

<?php
class DBO{
    public $DBC;
    
    public function __construct()
    {    
        $DB_dsn = "mysql:host = localhost; dbname = test; charset = utf8mb4; port = 3306";
        $DB_usr = "yshua80144";
        $DB_psw = "";

        try {
        //資料庫連線+開啟
        
        $DBC = new PDO($DB_dsn, $DB_usr, $DB_psw);
        //PDO錯誤處理
        $DBC->setAttribute(
            PDO::ATTR_ERRMODE,
            PDO::ERRMODE_EXCEPTION);

        // $sql_show = "SELECT * FROM `comments`";
        // $result = $this->DBC->exec($sql_show);
        // echo "successful". $result->fetchAll();
        
        return $this->DBC = $DBC;
    } catch (PDOException $e) {
        echo "connection fail : " . $e->getMessage();
    }
    }

    public function __destruct()
    {
        $this->DBC = null;
        echo "DB closed";
    }
    


    public function execute($sql){
        //echo $sql;
        try {
            $stmt = $this->DBC->prepare($sql);
            $stmt->execute();
            
            //$this->DBC ->exec($sql);
            echo "Insert successful!";
		} catch(PDOException $e) {
		    echo $this->error_message = $e->getMessage();
		}
    }
    
    public function insert($user, $email, $phone, $comment){
        //echo $user . "<br/>" . $email . "<br/>" . $phone . "<br/>" . $comment . "<br/>";

        $sql = "INSERT INTO test.comments (username, email, phone, comment) VALUES ('$user', '$email', '$phone', '$comment')";
        $this->execute($sql);



    
    }
}
    

    if(isset($_POST["submit"])){
        $user = $_POST["user"];
        $email = $_POST["email"];
        $phone = $_POST["phone"];
        $comment = $_POST["comment"];

        $DBO = new DBO();
        $DBO -> insert($user, $email, $phone, $comment);

        $user = "";
        $email = "";
        $phone = "";
        $comment = "";

    }else {
       
        $user = "";
        $email = "";
        $phone = "";
        $comment = "";
    }
?>

</html>