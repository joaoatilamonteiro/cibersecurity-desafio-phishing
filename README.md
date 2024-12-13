# Tutorial: Usando o SET (Social-Engineering Toolkit) no Kali Linux

Este tutorial ensina como usar o **SET (Social-Engineering Toolkit)** no Kali Linux para realizar um ataque de clonagem de site, útil para fins educacionais e de teste em ambientes controlados.

## Passos

### 1. Abrir o terminal

Abra o terminal do Kali Linux e entre como administrador utilizando o comando:

sudo su

### 2. Iniciar o SET
No terminal, digite o comando abaixo para iniciar o Social-Engineering Toolkit:
setoolkit

### 3. Selecionar o tipo de ataque

No menu do SET, siga as instruções abaixo:

    Selecione 1 para Social-Engineering Attacks.
    Selecione 2 para Website Attack Vectors.
    Selecione 3 para Credential Harvester Attack Method.
    Selecione 2 para Site Cloner


### 4. Configurar o IP e o site a ser clonado

O SET perguntará em qual IP você deseja hospedar o site clonado. Como estamos testando em uma rede fechada e privada, basta pressionar Enter para usar o IP local.

Em seguida, insira o endereço do site que você deseja clonar.


### 5. Testar o ataque

A partir deste ponto, quando alguém acessar o seu IP privado, o site clonado será exibido. Os campos de texto do site clonado irão registrar as informações inseridas e exibi-las no terminal.

Aviso: Este tutorial é destinado apenas para testes em redes privadas e controladas. O uso não autorizado de ataques de engenharia social e clonagem de sites é ilegal e antiético.
