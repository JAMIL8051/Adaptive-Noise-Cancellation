# Adaptive-Noise-Cancellation: We aim at cancelling the additive noise
in a noisy audio signal, namely noise reduction,
by means of adaptive filtering techniques. Here
we combined the audio samples of a speech that is
original signal with the real noise to generate
noisy signal. We recorded different speech signals
and added noisy signal with different amounts of
signal-to-noise (SNR) ranging from -10dB to
+10dB directly in MATLAB. Finally, we used
LMS based noise cancelling techniques on the
input noisy signal to obtain the de-noised
enhanced signal as the output. The noise signal
generated directly from MATLAB was used as
the reference signal to calculate the LMS filter
weights. The de-noised signal had the same length
as the desired signals.


