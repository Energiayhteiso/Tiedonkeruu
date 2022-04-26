# Tiedonkeruu
Energiayhteisön käyttöön tiedonkeruun menetelmät Kamstrup omnia mittareilta sekä Fronius symo ja Kostal piko inverttereiltä. 

Tiedot lähetetään InfluxDB tietokantaan, sekä tallennetaan paikallisesti.

Käytetään Node-Red ympäristöä ja hyödynnetään seuraavia nodeja:
https://nodered.org (2.14)
https://flows.nodered.org/node/node-red-contrib-influxdb (0.6.1)
https://flows.nodered.org/node/node-red-contrib-smartmeter (0.6.3)
https://flows.nodered.org/node/node-red-contrib-string (1.0.0)
https://flows.nodered.org/node/node-red-contrib-exec-queue (1.0.19)
