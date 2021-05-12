# Face-Recognition-using-One-class-classification
Used one class method ( training sampes of only one class) to acheive face recognition . In the new digital/covid era face biometrics will be the most sold . I personally used ORL, FEI database for training and evaluation. Feel free to use it my fellow researchers  .  If you can develop it more neatly please do so , all rights given . 


FEI Face Database: ( Download at : https://fei.edu.br/~cet/facedatabase.html )
     
     Disclaimer

    The FEI face database is available for research purposes only. Permission to use but not distribute or reproduce this database is granted to all researchers.

      Description and Download

    The FEI face database is a Brazilian face database that contains a set of face images taken between June 2005 and March 2006 at the Artificial Intelligence Laboratory of FEI in São Bernardo do Campo, São Paulo, Brazil. There are 14 images for each of 200 individuals, a total of 2800 images. All images are colourful and taken against a white homogenous background in an upright frontal position with profile rotation of up to about 180 degrees. Scale might vary about 10% and the original size of each image is 640x480 pixels. All faces are mainly represented by students and staff at FEI, between 19 and 40 years old with distinct appearance, hairstyle, and adorns.  The number of male and female subjects are exactly the same and equal to 100. 
    
    For more details on the FEI face database, its acquisition protocol, annotation, and the image processing steps to automatically normalize frontal face images, please read and reference the following article (in english) or papers (in portuguese):

    C. E. Thomaz and G. A. Giraldi. A new ranking method for Principal Components Analysis and its application to face image analysis, Image and Vision Computing, vol. 28, no. 6, pp. 902-913, June 2010.

    E. Z. Tenorio and C. E. Thomaz. Analise multilinear discriminante de formas frontais de imagens 2D de face. In proceedings of the X Simposio Brasileiro de Automacao Inteligente SBAI 2011, pp. 266-271, Universidade Federal de Sao Joao del Rei, Sao Joao del Rei, Minas Gerais, Brazil, 18th - 21st September 2011.

    V. Amaral, C. Figaro-Garcia, G. J. F. Gattas, C. E. Thomaz. "Normalizacao espacial de imagens frontais de face em ambientes controlados e nao-controlados" (in portuguese), Periodico Cientifico Eletronico da FATEC Sao Caetano do Sul (FaSCi-Tech), vol. 1, no. 1, October 2009.

    V. Amaral and C. E. Thomaz. "Normalizacao Espacial de Imagens Frontais de Face". Technical Report 01/2008 (in portuguese), Department of Electrical Engineering, FEI, São Bernardo do Campo, São Paulo, Brazil, October 2008.

    L. L. de Oliveira Junior and C. E. Thomaz. "Captura e Alinhamento de Imagens: Um Banco de Faces Brasileiro". Undergraduate Technical Report (in portuguese), Department of Electrical Engineering, FEI, São Bernardo do Campo, São Paulo, Brazil, June 2006.

    Inquiries for further information may be made to:

    Dr. Carlos Eduardo Thomaz

    Image Processing Laboratory

    Department of Electrical Engineering

    Centro Universitario da FEI, São Bernardo do Campo, São Paulo, Brazil

    Phone: +55 (0) 11 4353-2910

    e-mail: cet@fei.edu.br
ORL  Face Databases : (Download at : https://git-disl.github.io/GTDLBench/datasets/att_face_dataset/)

      The AT&T face dataset, “(formerly ‘The ORL Database of Faces’), contains a set of face images taken between April 1992 and April 1994 at the lab. The database was used in the context of a face recognition project carried out in collaboration with the Speech, Vision and Robotics Group of the Cambridge University Engineering Department.” “There are 10 different images of each of 40 distinct subjects. For some subjects, the images were taken at different times, varying the lighting, facial expressions (open / closed eyes, smiling / not smiling) and facial details (glasses / no glasses). All the images were taken against a dark homogeneous background with the subjects in an upright, frontal position (with tolerance for some side movement). 

For One-class SVM ,Gaussian-Mixture-Models,Isolation forest ,file structure should be:
                       
                    Main Folder:
      --------->person to be identified(training set)
      --------->test set(usually a single class)
{ Here a lot of keras pretrained CNN was used for feature extraction ,including latest VGGFACE  }

For VAE , file structure should be :

                    Main Folder:
          --------->Train(Normal Images)
          --------->Test(Anomaly and Normal to test)


For One class Neural Networks,file structure should be :

                  Main folder:
                ----------->Train
                             ----->Person to be identified 
                ----------->Test
                             ----->Person to be identified 
                             ----->Anomaly person 

{ For OC-NN , total accuracy is the average of  single accuracy of all person when considering each as single model training set }


Please Contact in case of any queries : snairgopika@cet.ac.in ( Responds within a week )
