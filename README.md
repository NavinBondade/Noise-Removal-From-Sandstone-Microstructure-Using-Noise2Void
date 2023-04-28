# Removing-Noise-From-Sandstone-Microstructure-Images-Using-Noise2Void
<p align="center">
<img src="https://github.com/NavinBondade/Noise-Removal-From-Sandstone-Microstructure-Using-Noise2Void/blob/main/Graph/a.jpg">
</p>
<p>Sometimes tomography images don't come out as expected and they might contain lots of noise. Redoing this process of capturing images can be expensive or physically not possible. To solve this problem, in this project, I have developed a deep learning system that takes the noisy CT images of sandstone as input and produces clean images. </p>
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Sklearn</li>
</ul>
<h2>Dataset Visualization</h2>
<p align="center">
<img src="https://github.com/NavinBondade/Noise-Removal-From-Sandstone-Microstructure-Using-Noise2Void/blob/main/Graph/Dataset.png" width="650" height="500">
</p>
<h2>What is Noise2Void (N2V)?</h2>
<p align="center">
<img src="https://github.com/NavinBondade/Noise-Removal-From-Sandstone-Microstructure-Using-Noise2Void/blob/main/Graph/maxresdefault.jpg" width="900" height="500">
</p>
<p>Training deep-learning models for denoising usually relies on either pairing high-noise input images with low-noise output images or using independent pairs of noisy images in an approach known as Noise2Noise (N2N). These approaches can be limited if the acquisition of low-noise or noisy training targets is not possible, as is often the case for biomedical image studies. As an additional option for training deep-learning models for denoising, an approach known as Noise2Void (N2V), in which training is done directly on the data to be denoised, is available. If you want to read the paper have a visit on this <a href="https://openaccess.thecvf.com/content_CVPR_2019/papers/Krull_Noise2Void_-_Learning_Denoising_From_Single_Noisy_Images_CVPR_2019_paper.pdf" target="_blank">link.</a>
</p>
<h2>Model Details</h2>
<p>The model I use in this project is n2v 2D stars. It was trained for 20 epochs on noisy sandstone ct image datase.</p>
<h2>Model Training & Testing</h2>   
<h4>Loss</h4>   
<p align="center">
<img src="https://github.com/NavinBondade/Noise-Removal-From-Sandstone-Microstructure-Using-Noise2Void/blob/main/Graph/Loss.png" width="1000" height="350">
</p>
<h4>MSE:</h4>  
<p align="center">
<img src="https://github.com/NavinBondade/Noise-Removal-From-Sandstone-Microstructure-Using-Noise2Void/blob/main/Graph/MSE.png" width="1000" height="350">
</p>
<h2>Model Prediction</h2>
<p align="center">
<img src="https://github.com/NavinBondade/Noise-Removal-From-Sandstone-Microstructure-Using-Noise2Void/blob/main/Graph/Output.png" width="800" height="1000">
</p>
