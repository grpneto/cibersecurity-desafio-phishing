# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados

![password and user](https://github.com/grpneto/cibersecurity-desafio-phishing/blob/master/Username%2C%20password.png)


### Observações:

O site clonado que era sugerido no desafio inicialmente era o Facebook, entretanto, erros como restrições e blocks nos navegadores, 
além de algum tipo de complicação com o servidor Apache, me fizeram optar por clonar o Instagram. Provavelmente existe algum nova 
em alguns sites que impede a resolução para páginas clonadas.  
