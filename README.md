# Convolutional Autoencoder

This repo is just a uni project. A convolutional autoencoder is implemented on a dataset of various images. First a basic use is shown i.e. simply as a compression tool with the goal of reconstructing the original image from the latent space representation with minimum error. 
Then a 10-Fold Cross validation is performed to find the best combination of the parameters of interest.
Finally, a further use of convolutional autoencoders is shown i.e., to remove noise from images, so-called "Denoising autoencoders."
All operations are done in the `main.ipynb` notebook.

## Notes
The `requirements.txt` file should list all Python libraries that your notebooks
depend on, and they will be installed using:

```
pip install -r requirements.txt
```
