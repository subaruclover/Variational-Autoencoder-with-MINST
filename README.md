# Variational-Autoencoder-with-MINST

Using VAE for MINST data

Loss function in:
$L(\theta, \phi) = - E_{z ~ q_{\phi(z|x)}}[p_{\theta}(x|z)] + D_{KL}(q_{\phi}(z|x)||p_{\theta}(z))$
