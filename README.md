# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux
mudando placa para de rede para modo  bridge

1 Acesso root: ``` sudo su ```
log senha do adm
2 Iniciando o setoolkit: ``` setoolkit ```
3 Tipo de ataque: ``` Social-Engineering Attacks opcao 1 ```
4 Vetor de ataque: ``` Web Site Attack Vectors opcao 2```
5 Método de ataque: ```Credential Harvester Attack Method opcao 3```
6 Método de ataque: ``` Site Cloner opcao2 ```
7 entre e fornecer site clonado https://www.facebook.com/
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados

![Imagem 1](https://github.com/maxhumberto/simulacao_Phishing/blob/1deb7ea09eca04fe9298a3c0910abe96413ba2fa/WhatsApp%20Image%202025-05-22%20at%2016.53.26%20(1).jpeg)
![Imagem 2](https://github.com/maxhumberto/simulacao_Phishing/blob/1deb7ea09eca04fe9298a3c0910abe96413ba2fa/WhatsApp%20Image%202025-05-22%20at%2016.53.26.jpeg)
