Download Link: https://assignmentchef.com/product/solved-cse-473-573-project-3-introduction-to-computer-vision-and-image-processing
<br>



<h1></h1>

<h2>1. K-Means Clustering for Image Segmentation (5 points)</h2>

The goal of this task is to use K-Means Clustering to segment the image “lenna.png”. Specifically, we set <em>K </em>= 2 and the clustering is only based on the Euclidean distance of pixel values. You are required to design your program and output the best clustering result. The desired output is such that the sum of distances between pixel values and their corresponding centers is minimum. You should implement clustering in “kmeans” function and output the <strong>centers </strong>and <strong>sum of distances </strong>of the best clustering in “.json” file. Then use “visualize” function to output the <strong>segmentation map </strong>replacing the pixel values with the corresponding centers. You are also required to output the running time. The specific format of the output has been clearly explained in the code. Below is an example of image and segmentation map using K-Means Clustering with <em>K </em>= 2.

Figure 1: Image                               Figure 2: Segmentation Map

1

CSE 473/573                                                     Project 3

<h2>2. Image Denoising (5 points)</h2>

The goal of this task is to use median filter for image denoising. Specifically the filter size is set as

<ol start="3">

 <li>It is required to do zero-padding first to ensure the output same size as the input. In “median-filter” function you should implement median filter on “lenna-noise.png” and output your denoised image. In “mse” function you should calculate the <strong>Mean Square Error </strong>of your result and the provided image “lenna-denoised.png”, then output the <strong>MSE </strong>in “.json” file.</li>

</ol>

MSE of two images <em>I </em>and <em>I</em><sup>0 </sup>can be indicated as .

Figure 3: lenna-noise                             Figure 4: lenna-denoised

<h2>3. Guidelines</h2>

<ul>

 <li>For <strong>ALL </strong>students whose code raise “RuntimeError”, your grades will be 0.</li>

 <li>Compress the two python files, i.e., “task1.py”, “task2.py”, the three given images and the folder “results” into a zip file, name it as “UBID.zip” (replace “UBID” with your eight-digit UBID, e.g., 51399256) and upload it to UBLearns before the due date. The zip file you upload should not contain files other than the six aforementioned files.</li>

 <li><strong>Do Not </strong>import any library or APIs besides what has been listed in “task1.py” and “task2.py”. You are only allowed to use the functions provided in “utils.py” and package “numpy”, “json” and “time”.</li>

 <li><strong>Do Not </strong>modify the code provided to you. Page 2 of 2</li>

</ul>