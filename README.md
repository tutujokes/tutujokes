## Hello, Friend!

<?php

class Me 
    {
    public $name = "Arthur Henrique";
    public $age = "22";
    public $skills = "Java Developer, SQL Database Management, Backend Developer";
    public $tech = "Linux, Git, Docker, Python, C, Java, SQL, PHP";
    public $extra = "x86_64 assembly, BrainFuck";
    private $secret = "Nothing Here I Swear...";

    public function __construct() {}

    public function sayHello() {
        echo "Welcome to my world.\n";
    }
}

$arthur = new Me();
$arthur->sayHello();
