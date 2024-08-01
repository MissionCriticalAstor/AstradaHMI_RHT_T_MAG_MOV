Program Astraada HMI do wizualizacji danych z czujników firmy ELA Innovation (Blue PUCK RHT, Blue PUCK T, Blue PUCK MAG, Blue PUCK MOV w trybie ANG). Program:
  - odbiera dane wysyłane protokołem MQTT
  - wyświetla dane pomiarowe czujników w zależności od modelu
  - wyświetla moc sygnału (rssi) czujników
  - wyświetla stan połączenia MQTT
  - możliwość przesłania danych innymi protokołami, np. Modbus TCP/IP

Program został opracowany do odbierania wiadomości za pośrednictwem protokołu MQTT z gatewaya Cassia X2000. Po pobraniu, należy w ustawieniach "MQTT Client" zmienić adres IP brokera oraz port, a także określić temat subskrypcji w sekcji „Text Format Table”.

![zmiana_brokera_i_tematu](https://github.com/user-attachments/assets/114be716-f898-4425-abe8-692d7816eca2)
