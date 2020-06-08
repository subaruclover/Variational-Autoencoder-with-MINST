# Variational-Autoencoder-with-MINST

Using VAE for MINST data

Loss function in:

<a href="https://www.codecogs.com/eqnedit.php?latex=L(\theta,&space;\phi)&space;=&space;-&space;E_{z&space;~&space;q_{\phi(z|x)}}[p_{\theta}(x|z)]&space;&plus;&space;D_{KL}(q_{\phi}(z|x)||p_{\theta}(z))" target="_blank"><img src="https://latex.codecogs.com/gif.latex?L(\theta,&space;\phi)&space;=&space;-&space;E_{z&space;~&space;q_{\phi(z|x)}}[p_{\theta}(x|z)]&space;&plus;&space;D_{KL}(q_{\phi}(z|x)||p_{\theta}(z))" title="L(\theta, \phi) = - E_{z ~ q_{\phi(z|x)}}[p_{\theta}(x|z)] + D_{KL}(q_{\phi}(z|x)||p_{\theta}(z))" /></a>
