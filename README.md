# VehicleClassification

## Execution Instructions for VehicleClassification_TFLearn

<pre>
Source Dataset Link - https://www.kaggle.com/competitions/vehicle/data?select=train
Step 1: Run the resize.py file, after updating the locally donwloaded dataset file, to resize the images.
Step 2: Depending on the label, assign 0 for Bus, 1 for Car, 2 for Motorcycles and 3 for non-vehicles.
Step 3: Run sendtodataset.py, after updating path for each label's folder and send each image with it's label to dataset.txt file
Step 4: Update the path for dataset.txt in MIFinal.ipynb
Step 5: Run the MIFinal.ipynb file
Step 6: After the model trains for 50 epochs, it can be tested on the testing dataset in the same .ipynb file.
</pre>