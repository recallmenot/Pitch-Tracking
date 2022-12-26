<h1>Pitch detection algorithms</h1>

<h4>Methods implemented:</h4>
<ul>
<li><b>YIN ESTIMATOR</b> - <i>YIN, a fundamental frequency estimator for speech and music </i> - Alain de Cheveigné, Hideki Kawahara - 
<i>Journal of the Acoustical Society of America, 2002.</i></li>
<p><li><b>CEPSTRUM</b> - <i>Cepstrum Pitch Determination</i> - A.M.Noll - <i>Journal of the Acoustical Society of America, 1967.</i>
</li></p>
<p><li><b>MAXIMUM LIKELIHOOD</b> - <i>Maxmium Likelihood Pitch Estimation</i> - James D.Wise, James R.Caprio, Thomas W.Parks - 
<i>IEEE Transactions on Acoustics, Speech and Signal Processing, 1976.</i></li><p>
<li><b>EXTENDED KALMAN FILTER</b> - 
 <ul> 
  <li><i><a href = "http://www.dafx17.eca.ed.ac.uk/papers/DAFx17_paper_21.pdf">Real-time Pitch Tracking in Audio Signals with the Extended Complex Kalman Filter </a></i> - Orchisama Das, Julius O. Smith, Chris Chafe in Proc. of International Conference on Digital Audio Effects, DAFx 2017.</li>
  <li> <i> <a href = "https://www.aes.org/e-lib/browse.cfm?elib=20719">Improved Real-time Monophonic Pitch Tracking with the Extended Complex Kalman Filter </a></i> -   Orchisama Das, Julius O. Smith, Chris Chafe - in Journal of the Audio Engineering Society, Vol 68, No. 1/2, 2020.</li></ul> 
 </li></p>
</ul>


<h2> Update, Dec 2022 </h2>

<p>In june of 2021, Orchisama Das (orchidas) created an implementation of the ECKF in C++ using JUCE and Eigen.
This repository is a fork of his implementation, de-JUCEd and modified to natively support both float and double data types.
You will need Eigen, pffft and my helper libraries decibelConv and windowHann.
</p>
