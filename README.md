# Scanned-Network-Dataset
the 
In this repository you can find the collected datasets from scanning by using FiPy microcontroller from Pycom.
In each text file there is the output of the collected data that is organized as follows:


Start Scanning--------------------------------------------------------------------------------------------------------------

while fipy_isconnected:

    1) Wifi: time
      (ssid= ?, bssid= ?, sec=?, channel=?, rssi=?)

    2) Bluetooth : time
       {'name': ?, 'rssi': ?, 'adv_tx_pwr': ?, 'tx_range': ?, 'def_tx_pwr': ?, 'mac': ?, 'scan_tx_pwr': ?, 'conn_tx_pwr': ?}

    3) Others: time 
       {'Acceleration': ?, 'Roll': ?, 'battery_voltage': ?, 'battery_percentage': ?, 'Pitch': ?}

    4) LoRa: time
       {'spreading_factor': ?, 'data': ?, 'frequency': ?, 'bandwidth': ?}
       (rx_timestamp=?, rssi=?, snr=?, sfrx=?, sftx=?, tx_trials=?, tx_power=?, tx_time_on_air=?, tx_counter=?, tx_frequency=?)



The experimentation should be done in different scenarios:
1) Pedestrian
2) Bus
3) Car
4) Train
5) Metro
6) Velo

To be sure of the robustness of the data we should collect it in "Rural" and "Urban" areas.
