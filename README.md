# ESP32-ADC-Accuracy-Improvement-function
A function that improves the default ADC reading accuracy to within 1%

The ESP32 ADC has two non-linear regions, one just below ~0.5v and the other just above ~2.5v, however by using a poly omitted response can be made accurate to within 1% by adjusting the ADC output to the correct value.
