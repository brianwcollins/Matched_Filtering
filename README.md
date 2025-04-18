# Matched Filtering on Performed on Various Pulses Using GNURadio

Matched filtering is a process by which (DEFINE MATCHED FILTERING). The general application of matched filtering is to find a known signal in noise, with the most common applications of this being in fields such as radar detection. Given that the pulse characteristics are known as it is transmitted, (applying the matched filter to the return signal can locate any repetitions or echoes of this original signal.) In radar detection, this can be used to find a return pulse from an aircraft even in very noisy radio environments.

Notably, certain pulse shapes and properties make the return signal easier to detect even at very low SNR. Within this demonstration, several different pulse shapes will be used to compare and potentially iteratively optimize the best radar pulse for detection at low SNR. There are two primary goals in this endeavor, which are to minimize transmission amplitude and pulse width. Minimizing these parameters will lead to the cheapest possible radar pulse that will still be able to effectively detect aircraft at low SNR.

(DISTANCE CALCULATION IF I HAVE TIME)
d = ct

This code uses GNURadio to apply matched filtering to different types of pulse signals. The following types of signals are included within the code

1. Cosine Wave
2. (Add more, check out GNURadio signal catalog)

The width of the pulse can be controlled by varying the (VARIABLENAME) parameter./n
The frequency of the signal can be controlled by varying the (VARIABLENAME) parameter./n
The amplitude of the signal can be controlled by varying the (VARIABLENAME) parameter./n
(POTENTIALLY ADD DISTANCE OF THE PLANE PARAMETER IF I HAVE TIME?)
