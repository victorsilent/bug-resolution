#Solução de bugs/problemas que tenho durante a vida

1- instalação do phpmyadmin
Link: https://www.vivaolinux.com.br/dica/Servidor-Apache2-+-MySQL-+-PHP5-+-PHPMyAdmin-%28Ubuntu%29
Depois fazer: cd /etc/apache2/apache2.conf
adicionar no arquivo a linha "Include /etc/phpmyadmin/apache.conf" sem aspas 
sudo service apache2 restart
and gg motherfucker
