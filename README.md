# DeepIC50
DeepIC50: Deep learning for predicting drug responsiveness based on the integration of genomic and drug features

# Code description
- DeepIC50.py, DeepIC50.ipynb : the files predict drug responsiveness. 
- DeepIC50_construct_code.py, DeepIC50_construct_code.ipynb : the files describe construct of our model
- Test_toysets.npz: the file is a toy example file that allows you to test.
- DeepIC50.h5 : the file is the CNN model, and was used in DeepIC50.py or DeepIC50.ipynb
- Mutation_position_example.xlsx: the file contained the genomics information (mutation statuses) for the cancer cell lines.
- Drug_chemical_descriptors.xlsx: the file contained the drug chemical properties generated by PaDEL, and the columns were converted to binary digits. To make the list easier to see, we've transversed it. The original row should be set to be drug.
- Padel_Descriptors_detatiled_information.xls : This file contains a detailed description of each column used as drug features.
- GDSC_CCLE_druglist_smile_added.xlsx : This file describes the SMILE strings of the drugs used in the GDSC and CCLE datasets.
- Computer specification with model generation  : Windows 10, Keras 2.3.0, tensorflow-gpu 1.14.0, Geforce GTX 1080 Ti, RAM 64GB

# Usage
### please refer to the annotations in DeepIC50.py or DeepIC50.ipynb in detail.

# Contact
### If you have any questions, please contact below.
- Mr. Minjae Joo (chan7844@naver.com)
- Prof. Seungyoon Nam (nams@gachon.ac.kr)
