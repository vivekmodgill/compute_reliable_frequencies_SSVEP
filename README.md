**Computing Reliable Flicker Frequencies**


---
<br>
The flicker frequency of a visual stimulus on a screen is constrained by the screen’s refresh rate ( R ), meaning the stimulus can only update at discrete frame intervals. The only reliable flicker frequencies are those that are exact divisors of the refresh rate.

To compute them, we use the formula:


$$f = \frac{R}{N}$$


where:
*   R  is the screen’s refresh rate (in Hz),

*   N  is the number of frames per flicker cycle (must be an integer).
<br>
---
<br>


By iterating over all possible  N  values from 1 to  R, we generate all valid flicker frequencies that will be frame-locked and free of timing artifacts.

This ensures that the visual stimulus remains synchronized with the screen refresh rate, which is essential for precise control in SSVEP-based experiments.
