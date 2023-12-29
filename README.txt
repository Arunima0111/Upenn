To run the feature extraction code:

1. Make an excel sheet containing the PID, image file location, and mask file location of all the images and masks. 
2. Make 4 list files. Name them as id_, input_, mask_, and output_ followed by the dataset description. 
3. In the processing "a" code, change the sheet_file name to the excel sheet created in step 1. Modify the listdir, listlab according to the 
names and locations of step 2. Modify the outdir to change the directory where the excel sheets of features for different cases should be saved.
4. Run processing code a
5. In code b, change the names of listdir, different lists, paramdir, param_file. Make sure that the location of param_file is correct. 
6. Modify the files and folder names and run processing c and d. 
