# Config Server

[GitHub] (https://github.com/kbrsglm/config_server)
-----
## Config server 
- Mikroservislerim konfigurasyonlarını merkezi bir yerden yönetmek için kullandığımız yapıdır
- Bu config yspısı: merkezi bir alan içinde config serverüzerinden yapılandırmaları dinamik olarak alabilir

# Spring Cloud(Config Client)
-  Spring cloud server dan kanfigurasyonları alamak için kullanılan istemcidir
- Mikroservisleer genellikle  config client olarak yapılandırırlır.
- Config client config server 'a bağlanır ve merkezi olarak yönetilen konfigurasyon dosyalarını alır

# Spring Cloud(Config Server)
- Merkezi bir konfigurasyon yönetim sunuculuğu yapar
- Bir veya daha fazla mikroservislerin konfigurasyon dosyalarını merkezi bir yerde sunar.
