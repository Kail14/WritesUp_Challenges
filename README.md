# WritesUp_Challenges
jeu de hacking

1-ETHERNET-Trame:
on a des hexadecimal 
On entre dans le site "Convert hexadecimal" to text et on a un: Y29u....
On entre ensuite dans le site "base64 decode and encode" et on décode puis on obtient le mot de passe donc il suffit juste de le coller dans le challenge

2-Authentification twitter:
on télécharge le fichier wireshark ch3.pcap puis on l'ouvre et on suit le protocol http 
on va ensuite dans le site "base64 decode and encode" puis on decode le : dXNl.... du coup on obtient le mot de passe et on le colle dans le site

3-Bluetooth-Fichier inconnu:
On a le ch18.pcap puis on l'ouvre avec wireshark et on suit le protocol HCI_EVT et on a 0c:b3:19:b9:4f:c6 SamsungE GT-S7390G
On entre  dans le site SHA1: Cryptez avec sha1 en ligne on colle 0c:b3:19:b9:4f:c6GT-S7390G puis le mot de passe s'affiche et enfin on le colle dans le challenge
