The Images of Groups Dataset
============================

Here is the script that allows you to scan the face images from the Group Images Dataset using the metadata stored in "PersonData.txt" for each group separately.
The faces are captured using Haar Classifier and then the coordinates are match with provided metadata.
Some faces may not be detected, and some non-faces may be detected, which will be verified using metadata information and stored in a directory named "outDir/<ageGroup>"

The images are split among 11 folders, based on the keyword search used to download the images from Flickr. The images are either 
Wedding images, Family images, or Group images. The folders of images are as follows: 

    Wed2a
    Wed3a
    Wed5a
    Fam2a
    Fam4a
    Fam5a
    Fam8a
    Group2a
    Group4a
    Group5a
    Group8a

**It stores the output arranged by the directory named to ageGroup as specified below, and the gender to image title followed by an underscore.**


**Human-Labeled Age:**

Faces were labeled as one of 7 categories, corresponding to 7 age ranges: 

    Label       Age Range
    1       0-2
    5       3-7
    10      8-12
    16      13-19
    28      20-36
    51      37-65
    75      66+

**Human-Labeled Gender:**

    1       Female
    2       Male 
