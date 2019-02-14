1) age50-.txt and age50+.txt files provides the information (photo ID, photographer ID, gender (male - M, female -F), age, aesthetic score) about photographers (whose age is known) in AVA dataset.
For the rest of photographers, the age is not provided or is not valid. 
2) age50-_train.txt and age50+_train.txt files provides the information (photo ID, photographer ID, gender (male - M, female -F), age, aesthetic score) about photographers (whose age is known) in AVA dataset, after excluding 20K test images.
0 - age which is equal or more than 50
1 - age which is more than 50
For the class age50+ the data augmentation technique for random photos are used, so that number of photos will be same as in age50- class 
80% of photos used for training and the rest for testing

3) europe.txt and usa.txt files provides the information (photo ID, photographer ID, gender (male - M, female -F), location (x and y coordinates), age (-1 is asiggned for those whose age is not defined), aesthetic score) about photographers (whose location belongs to either Europe or USA) in AVA dataset.
4) europe_train.txt and usa_train.txt files provides the information (photo ID, photographer ID, gender (male - M, female -F), location (x and y coordinates), age (-1 is asiggned for those whose age is not defined), aesthetic score) about photographers (whose location belongs to either Europe or USA) in AVA dataset, after excluding 20K test images.
0 - Europe
1 - USA
For the class Europe the data augmentation technique for random photos are used, so that number of photos will be same as in USA class 
80% of photos used for training and the rest for testing

5) female.txt and male.txt files provides the information (photo ID, photographer ID, location (-1 is asiggned for those whose location is not defined), age (-1 is asiggned for those whose age is not defined), aesthetic score) about photographers (whose gender is defined) in AVA dataset.
6) female_train.txt and male_train.txt files provides the information (photo ID, photographer ID, age (-1 is asiggned for those whose age is not defined), aesthetic score) about photographers (whose gender is defined) in AVA dataset, after excluding 20K test images.
0 - female
1 - male
For the class female the data augmentation technique for random photos are used, so that number of photos will be same as in male class 
80% of photos used for training and the rest for testing