<img src="https://i.ibb.co/4ZH33bY/logo.png" alt="AbacusLogo" height="350" width="350"/>

# Abacus.AI

### Description: Detect and classify basic mathematical elements on an image and evaluate expressions based on the same

#### Project for bachelors thesis at University of Zagreb, Faculty of Electrical Engineering and Computing

---

##### Full thesis name: Detection and classification of text based elements on an image using deep neural networks
##### Module: Computer Science
##### Mentor: prof. dr. sc. Domagoj Jakobović

---

Contents:
 - Pipeline for creating training images and corresponding .csv files
 - Handwritten fonts
 - All symbols generated in 100+ fonts
    - Sorted by difficulty
 - Image examples
 - Heavily documented code
    - Code will be made more efficient after presenting the final thesis
  - `generate_tfrecords.py` for creating *.record files for further `Tensorflow API` usage
  
  Testing:
   - File called `ImagePredictor.py` contains everything neccessary to run the interference graph on an image
     - Output image is saved as `output.png` and the result is printed out in the console
