# IntEEGBoard

This is a simple board with an implementation of Texas Instruments's ADS1299 chip, designed to be used in conjunction with an arduino or a similar microcontroller polling the board. 

# Disclaimer

This EEG board design is provided for educational purposes only. By using this hardware, you acknowledge that you understand the risks involved, and you agree that the author(s) of this project are not responsible for any damages, injuries, or adverse effects that may result from its use. 

This hardware has been designed with safety measures, but it is your responsibility to ensure proper usage. The author(s) make no guarantees regarding the safety, functionality, or results obtained from using this device. USE AT YOUR OWN RISK.

# Features
- 8 channels + reference electrode
- Low noise sensing
- First order analog filtering for anti-aliasing designed for EEG signals
- Seperate Analog Ground and Digital Ground, with resistor connected to both to stop reflectance and to balance voltage between grounds
- Clean, analog power supply in the form of a battery connector (plug in 9V battery) (no more noise from normal power supplies!)
- Pin connectors for easy and reliable connection to EEG electrodes and an arduino board

# License

The files within this repository are under the MIT License.
