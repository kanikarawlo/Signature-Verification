# Signature-Verification

## Overview 
Handwritten signatures serve as a crucial means of authentication. However, forged signatures pose a significant threat, leading to various fraudulent activities. This project focuses on identifying forged signatures using Siamese Neural Networks, aiming to mitigate the risks associated with fraudulent activities, such as random forgery, unskilled forgery, and skilled forgery.

## Requirements 
Before using the system, ensure that you have the following prerequisites:
1. Python (version 3.6 or higher)
2. Other required Python packages specified in 'requirements.txt'.

## Istallation 
To install the necessary Python packages, follow these steps:
1. CLone the repository :
```bash
git clone https://github.com/kanikarawlo/Signature-Verification
```
2. Install the required packages :
```bash
pip install -r requirements.txt
```
## Using the Streamlit App
Once you have installed the required packages, you can use the Signature Forgery Detection System either through the command line interface or by using the Streamlit app.
To use the Signature Forgery Detection System, follow these steps :
1. Ensure you have installed the required Python packages as mentioned in the Installation section.
2. Navigate to the directory where you cloned the Signature Forgery Detection repository or download the signature_verifier.py file and the Signature_Forgery_Detector.joblib file from the project repository on GitHub and navigate to the directory where you downloaded the signature_verifier.py file.
3. Run the Streamlit app by executing the following command:
```bash
streamlit run signature_verifier.py
```
4. Once the Streamlit app is running, you can access it through your web browser by opening the URL provided in the terminal/command prompt.
5. Follow the instructions provided in the app to upload images of the original signature and the signature to be tested, and to obtain the verification results.
   
By following these steps, users can run the Streamlit app (verifier_app.py) on their local machine and utilize the Signature Forgery Detection System.

## Troubleshooting
If you encounter any issues while using the Signature Forgery Detection System, consider the following troubleshooting steps:
1. Check Dependencies: Ensure you have installed all required Python packages specified in the requirements.txt file.
2. Verify Input Images: Make sure the input signature images are in the correct format (RGB/BGR) and accessible from the specified path.
3. Review Error Messages: If you encounter any errors, carefully review the error messages to identify the source of the issue.

## References 
1. Handwritten Signature Forgery Detection using Convolutional Neural Networks. [Link] (https://www.sciencedirect.com/science/article/pii/S1877050918320301)
