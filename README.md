#**Neuro Monitor**

Non-contact nocturnal seizure detection using PVDF piezoelectric film under the mattress with BCG signal fusion and TinyML classification.

##Signal Chain

LDT0-028K → LMP7721 → Sallen-Key LPF 40Hz → ESP32 500Hz → FFT → Random Forest → MQTT → Firebase

##Hardware

Sensor: LDT0-028K PVDF film

Foam: HD PU 32 kg/m³, 80mm

MCU: ESP32

##Frequency Targets

Tonic: 10–25 Hz, 
Clonic: 1–8 Hz

