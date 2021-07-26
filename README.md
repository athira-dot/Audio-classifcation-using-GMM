
<h2>Speech Spectrogram </h2>

<p align="justify">
In this project, whitening transform on speech spectrogram of audio files are studied to analyse the speech data.A speech spectrogram shows the Fourier Transform of a signal as it varies with time. A whitening transformation or sphering transformation is a linear transformation that transforms a vector of random variables with a known covariance matrix into a set of new variables whose covariance is the identity matrix, meaning that they are uncorrelated and each have variance .

  
</p>
<p align="center">
	
<figure>
	<img src='covaraianne_before_whitening.png'>
    <figcaption>The covariance matrix of spectrogram of data before whitening </figcaption>
</figure>

<figure>
	<img src='covarince_after_whitening.png'>
    <figcaption>The covariance matrix of spectrogram of data after whitening
 </figcaption>
</figure>


<p align="justify">
The above two plots represent the covariance matrices of the noisy audio and its whitening transformation. We can see the differences between the above two covariance matrix plottings. After whitening, the covariance matrix of noisy audio is the identity matrix, and all the non-diagonal entries are almost zero.

The average absolute value of the non-diagonal entry for noisy audio is: 9.285590908753007e-17

</p>
	
<figure>
<img src='spactogram_of_noisy_audio.png'>
<figcaption>The spectogram of the noisy audio before whitening.
</figure>

<figure>
<img src='Spectorgram_of_noisy_audio_after_whiening.png'>
<figcaption>The spectogram of the noisy audio after whitening.
</figure>

	
	

</p>
