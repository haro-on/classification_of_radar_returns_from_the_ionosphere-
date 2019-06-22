# Deep Learning

## Motivation:
The dataset is a data of ionosphere layer recived by a rader were it collected by the Space Physics Group of The Johns Hopkins University Applied Physics Laboratory at 1989. The radar system, located in Goose Bay, Labrador, consists of a phased array of 16 high-frequency antennas, with a total transmitted power on the order of 6.4 kW and an antenna gain of about 30 dBm at frequency ranges of 8 to 20 MHz. The signals returns are used to study the physics of the ionosphere. Good signal returns can show evidence of some structure type in the ionosphere while bad radar returns cannot where their signals pass through the ionosphere. The received signals were processed using an autocorrelation function whose arguments are the time of a pulse and the pulse number. 
According the Goose Bay radar system, there were 17 pulse numbers for the Goose Bay system. Each pulse in this dataset are described by 2 attributes, corresponding to the complex values returned by the function resulting from the complex electromagnetic signal. The target is showing the free electrons in the ionosphere. “Good” radar returns are those showing evidence of some type of structure in the ionosphere. “Bad” (b) returns are those that do not; their signals pass through the ionosphere. The radar dataset having 351 samples with 35 features. All 34 features are represented as continuous numeric values and the last one is the target value and has two possible result either be Good or Bad.

## Project Overview:
On this project, I will use a multi-layers perceptron neural network method (MLP) to classify the return signal from the radar in order to identfy the good and bad rader return from ionosphere layer.


### Features:
34 columns (V0 to V34): represent the 17 pulse values of the radar system with Continuous values between -1,1
### Target Variable: 
Class colum: it Has two values [0,1] 0= bad class  wile 1= good class
