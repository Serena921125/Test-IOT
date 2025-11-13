# Test-IOT
Projet test pour montrer l'utilisation
Ce que le projet va permettre :
- récupérer des messages
- les sotcker en
- les afficher
- utiliser Node-RED

![Robot](https://figes.com.tr/wp-content/uploads/2021/01/Robots-Square.jpg)

"""mermaid
flowchart TD
    mosquitto  --> |messages| rpi
    rpi --> BDD
    rpi <--> Github
"""