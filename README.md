# Setup server
Configura servidor web automaticamente
![main](https://github.com/Olliv3r/Setup-server/blob/m
ain/media/Main.jpg)

# Instalação:
```
apt update && apt upgrade -y && apt update && apt install git -y && git clone https://github.com/Olliv3r/Setup-server && cd Setup-server && chmod +x setup-server && ./setup-server --setup
```

### Atualizar o certificado:
*Obs* Caso deseja atualizar o certificado, basta executar o script `updateCert` dentro do diretório raiz deste projeto, deixe os campos em branco dando ENTER:
```
bash ./updateCert 
```

### Habilite e desabilite o certificado:
Desabilitar:
```
./setup-server --disable-ssl
```
Habilitar:
```
./setup-server --enable-ssl
```

### Login: `root` & `toor`
### phpmyadmin:
![painel](https://github.com/Olliv3r/Setup-server/blob/main/media/painel-admin.jpg)
![dashboard](https://github.com/Olliv3r/Setup-server/blob/main/media/painel-dashboard.jpg)

#### Obs!
Se o certificado estiver desabilitado use o `http://localhost:8080/phpmyadmin` para acessar o phpmyadmin
Ou `https://localhost:8443/phpmyadmin` caso o certificado esta habilitado

## Recursos:
- [x] Certificado SSL
- [x] Gerenciador server-web (opcional)
- [x] PhpMyAdmin
- [x] Apache
- [x] MariaDB
- [x] Url amigável ativo (a)
- [x] Hospedagem em /sdcard/htdocs
- [ ] Outros
