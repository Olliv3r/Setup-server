# Setup server
Configura um servidor web no aplicativo termux de forma automática  
![main](https://github.com/Olliv3r/Setup-server/blob/main/media/Main.jpg)

## Instalação:
```
apt update && apt upgrade -y && apt update && apt install git -y && git clone https://github.com/Olliv3r/Setup-server && cd Setup-server && chmod +x setup-server && ./setup-server --setup
```

#### Atualizar o certificado:
*Obs* Caso deseja atualizar o certificado:
```
bash ./setup-server --update-ssl
```

#### Habilite e desabilite o certificado:
Desabilitar:
```
bash ./setup-server --disable-ssl
```
Habilitar:
```
bash ./setup-server --enable-ssl
```

#### Login do painel phpmyadmin:
Login: `root` & `toor`

phpmyadmin:
![painel](https://github.com/Olliv3r/Setup-server/blob/main/media/painel-admin.jpg)
![dashboard](https://github.com/Olliv3r/Setup-server/blob/main/media/painel-dashboard.jpg)

#### Obs!
Se o certificado estiver desabilitado use: `http://localhost:8080/phpmyadmin` para acessar o phpmyadmin ou `https://localhost:8443/phpmyadmin` caso o certificado estiver habilitado.

Essa alteração tambem vale para a pasta dos projetos: `htdocs`, Se o certificado tiver desabilitado acesse: `http://localhost:8080` ou `https://localhost:8443` se o certificado estiver habilitado.

## Recursos:
- [x] Certificado SSL
- [x] Gerenciador server-web (opcional)
- [x] PhpMyAdmin
- [x] Apache
- [x] MariaDB
- [x] Url amigável ativo (a)
- [x] Hospedagem em /sdcard/htdocs
- [ ] Outros

> [!CAUTION]
> Repo não mais confiável para configurar o servidor, acesse este outro projeto: [Install-Web-Server](https://github.com/Olliv3r/Install-Web-Server)

:) Boa sorte!
