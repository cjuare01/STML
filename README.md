# Special Topics Machine Learning (STML)
University of Texas at El Paso                                
CS 5390/4390 Special Topics Computer Science: Data-Driven Security and Privacy
## Team Members:
* Stephanie Medina - Graduate Student (Lead)
* Charlie Juarez - Graduate Student
* Elizabeth Rubio - Undergraduate Student

## The Practicality of Open Source Code in Machine Learning

The purpose of this project is to measure the practicality of the open source code that was provided by the authors of the paper:            
[**_Adversarial Examples Are Not Easily Detected: Bypassing Ten Detection Methods_**](https://arxiv.org/pdf/1705.07263.pdf)                
The authors are _Nicholas Carlini_ and _David Wagner_

## Contributions

The code provided in this repository is an edited version of the repository given in the paper mentioned above. 
Before running this code please follow the steps in the section below! After completeting those steps the code
can be executed in the same way that the authors explained, please read the [README](https://github.com/cjuare01/STML/blob/main/Carlini_Code/README.md) file provided in the 
[Carlini_Code](https://github.com/cjuare01/STML/tree/main/Carlini_Code) directory.

## TO DO BEFORE EXECUTING

Due to the file size, GitHub did not allow for the upload of the following documents:

* train-images-idx3-ubyte.gz:  training set images (9912422 bytes)
* train-labels-idx1-ubyte.gz:  training set labels (28881 bytes)
* t10k-images-idx3-ubyte.gz:   test set images (1648877 bytes)
* t10k-labels-idx1-ubyte.gz:   test set labels (4542 bytes) 

We have created a Google Drive Folder which holds the files:
[Google Drive](https://drive.google.com/drive/folders/1ultq_AXRoF1K77DkGbsipeXRrWk7ihlK?usp=sharing)

If you wish to download them from the author's website, you can download them here:
[Author Website](http://yann.lecun.com/exdb/mnist/)         
*NOTE: This website is unstable, it usually gives an error, which is why the files were downloaded and stored in the Google Drive*

**Make sure to add these data files inside the [Carlini_Code](https://github.com/cjuare01/STML/tree/main/Carlini_Code) directory or else it will give an error.**   
These files should be added under a folder named "data" in order for the code to work. If this folder does not exist, the code will try to download from the website (which is unstable)

## Additional Files/Documentation
Please refer to the [SpecialTopics.ipynb](https://github.com/cjuare01/STML/blob/main/SpecialTopics.ipynb) file for the Google Collab implementation that we created for the project.
Details regarding the project will be provided in the document named "The Practicality of Open Source Code in Machine Learning Report"
An Ubuntu Virtual Machine was utilized to execute the code, the VM can be found in the following link: [VM](https://drive.google.com/file/d/1ixHtxkMPR8Ah1oQtLE-tmbrVBoM_N2cj/view?usp=sharing)
