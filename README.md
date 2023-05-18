# Business Card Information Extraction with EasyOCR
This is a Streamlit application developed using Python that allows users to upload an image of a business card, extract relevant information from it using easyOCR, and manage the extracted information in a database. The application provides a graphical user interface (GUI) for easy interaction and data management.

## Features
1.  Image Upload: Users can upload an image of a business card through the application's GUI.

2.  Information Extraction: The application utilizes easyOCR to extract relevant information from the uploaded business card image. The extracted information includes:

      Company name,Card holder name, Designation, Mobile number, Email, 
      address, Website URL, Area, City, State,Pin code

3.  Display Extracted Information: The extracted information is displayed in a clean and organized manner within the application's GUI. Users can easily view the extracted data.

4.  Database Management: Users can save the extracted information along with the uploaded business card image into a database. 
    The application supports multiple entries, allowing users to store information for multiple business cards.
    
## Skills Required:
    Python, MYSQL, Streamlit, Regular Expressions, OCR 
## Running App:
 * Clone the repository using the following command:
    git clone 
 * Install the required libraries using requirement file:
    command: pip install -r requirements.txt
 * Run the application using the following command:
    streamlit run app.py
## Usage:

Once the application is running, you can use the following steps to extract information from business cards and manage the data:

* Upload an image of a business card using the provided file upload feature in the application's GUI.

* After the image is uploaded, the application will extract relevant information from the business card using OCR.

* The extracted information will be displayed in a clear and organized manner within the application's GUI.

* To save the extracted information and the business card image into the database, click the "Save to Database" button.

* To view the saved data, click the "View Database" button. The application will display all the entries stored in the database, including the business card images and extracted information.

* To update or delete a specific entry, use the corresponding buttons provided next to each entry in the database view.

* To exit the application, stop the running Streamlit server (Ctrl+C).

## Application Architecture:

 The application follows a simple architecture that includes the following components:

* 'final.py': The main application file that
      defines the Streamlit app and GUI components.
      Handles the database operations, including creating tables, inserting data, updating data, deleting data, and retrieving data.
      Uses easyOCR library to extract information from the uploaded business card image.
* 'requirements.txt': List contains the required Python packages and versions.

## Conclusion:

    The application can extract text in English language only and only from business cards.
