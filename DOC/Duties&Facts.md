## 1 Duties

1) Galvanic isolation between HT2003/2 GSV and the DoorbellUpgrade
2) Trigger the door bell release buzzer from remote (smartphone)
3) Disable the annoying bell noises (street & floor)
4) Get ringing event at smartphone
5) Map ring codes (Morse) to automations (release buzzer)


## 2 Facts
### 2.1 HT2003/2 GSV

0)  Is there UB+ from HT2003/2 GSV at the flat device ?

1)  Doorbell street:
    * U = 6,8 V AC  
2)  Doorbell floor:
    * What kind of Signal ? (it must be a audio one)
    * Sink is a speaker of low impedance
    * U = ?  
3)  Door release buzzer:    
    * The HT2003/2 GSV pull down a pull up Resistor to ground.
      I = 2 mA

### 2.2 ESP32  
 * Pull up resitors spread: 10k-100k https://esp32.com/viewtopic.php?t=5111
 

