Dear, tutor
Plesae kindly follow below steps to run the testing phase.
1. Set the testing_data path in configuration file: data_path = "../testing_data_release/testing_data/"
2. Set the model path in configuration file: model_file = 'target_model.h5'
3. Run the python files
   1.If you only have one machine to do test, just set 'validation_1_validate_smaples = 824' and run 'python3 validation_1-200.py'
   2.If you use multi-machine to run test, just set the protein ranges for every machine in the congfiguration file.

Finally, there will be a "v2_final_predictions_24epoch.txt" file generated which contains the top10 ligands for each protein.
