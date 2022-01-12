# configEnviroment
//- Instalar NodeJs

sudo apt-get install curl -y
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
source ~/.bashrc
nvm list-remote
nvm install v16.13.2
node --version

--------------------
--------------------
--------------------
--------------------
--------------------

//- Instalar NPM

sudo apt-get install npm -y
npm --version

--------------------
--------------------
--------------------
--------------------
--------------------

//- Instalar Git

sudo apt-get install git -y

--------------------
--------------------
--------------------
--------------------
--------------------

//- Instalar LAMP

1. Linux
2. Apache{
	sudo -i
	apt-get update
	apt-get install apache2 -y
	service apache2 status
	apache2 -v
}
3. MySQL{
	apt-get update
	apt-get install mysql-server mysql-client -y
	service mysql status
	mysql --version
	mysql -u root -p
	SELECT user,authentication_string, plugin, host FROM mysql.user;
	ALTER USER  'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '1234';
	FLUSH PRIVILEGES;
}
4. PHP{
	apt-get update
	apt-get install php libapache2-mod-php php-mysql
	php -v
}

//- Instalar PHPMyAdmin

1. PHPMyAdmin{
	apt-get update
	apt-get install phpmyadmin -y
}
