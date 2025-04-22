# Matched Filtering on Performed on Various Pulses Using GNURadio

Matched filtering is a process by which a noisy signal is autocorrelated with a known signal in order to pull the known signal from the noise. The most common applications of this is in fields such as radar detection, where a previously sent signal can be autocorrelated against recieved data to find potential echoes of that signal, indicating a target. This target's distance from the reciever can be determined using the equation d = cT/2, where T is the time delay between sending and recieving the signal and c is the speed of light. Given that the pulse characteristics are known as it is transmitted, applying the matched filter to the return signal can easily locate any repetitions or echoes of this original signal in low noise environments. Increases in noise can negatively affect the performance of this system wholistically.

Notably, certain pulse shapes and properties make the return signal easier to detect even at very low SNR. Within this demonstration, several different pulse shapes will be used to compare and potentially iteratively optimize the best radar pulse for detection at low SNR. There are two primary goals in this endeavor, which are to minimize transmission amplitude and pulse width. Minimizing these parameters will lead to the cheapest possible radar pulse that will still be able to effectively detect aircraft at low SNR.

This code uses GNURadio to apply matched filtering to different types of pulse signals. Any type of signal included in the basic signal generator can be used in this code, but replacing this block with other types of signals is welcome and encouraged.

The number of cycles of the pulse can be controlled by varying the Num_Cycles parameter.\
The frequency of the signal can be controlled by varying the Freq parameter.\
The amplitude of the signal can be controlled by varying the Sig_Amp parameter.\
The real distance of the target from the detector can be controlled by varying the dist parameter (Note: This parameter is measured in meters(m).\

It should be noted that the current codee is not built to fully implement variables, and has many bugs addressed in issues to be solved later.
