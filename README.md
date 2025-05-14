# APPLICATION DEMONSTRATION

5.1 System Initialization

The AutoResultGen system starts by initiating the process through enrollment number inputs. These numbers are utilized to activate the automation process. The Selenium-powered system initiates the opening of the result portal, automatically directing itself to the result page. This first step establishes the basis of the whole automation, enabling seamless student data retrieval with minimal intervention from the user.

![image](https://github.com/user-attachments/assets/8e343dee-e8c1-47c6-8a32-a72988db5509)

                                     Fig. 5.1 System Initialization



5.2 Automated Navigation and Input

When the system is started, Selenium automatically navigates through the result portal. It selects the right program and semester from the dropdown and enters the roll number for all students. This saves time since it does not require manual entry of data, and accessing results is quicker. The system offers correct navigation and input to ensure smooth execution without the need for intervention by the user.

![image](https://github.com/user-attachments/assets/0c99709d-5df0-46a6-979c-86be0458a7a8)

                                 Fig. 5.2 Automated Navigation and Data Entry


5.3 CAPTCHA Solving Using Gemini API

Once the CAPTCHA shows up on the result portal, the system captures the CAPTCHA image automatically with Selenium. The image is then passed to the Gemini API, which processes and gives back the CAPTCHA text. The decoded text is filled into the form automatically so that the system can avoid human intervention and go ahead with getting the student's result.

![image](https://github.com/user-attachments/assets/333f2c75-aae6-4ef8-bbdf-5dee14f479e2)

                                 Fig. 5.3 Automated CAPTCHA Solving Using Gemini API


5.4 Generating Output Files

Upon extracting data for all students, the system produces two output files: all_results.xlsx, an Excel file that houses structured tabular data, and all_results.pdf, a formatted and clean report safe for viewing and printing. These reports offer a clean and efficient means of storing, analyzing, and reporting students' outcomes. Automated file generation provides consistency and minimizes the amount of manual work on formatting, thus the overall accuracy and efficiency.

![image](https://github.com/user-attachments/assets/4cc5cb26-b6d6-4b8f-b878-99731913aa6e)

                                  Fig. 5.4 Generated Excel and PDF Reports

5.5 Demonstration Results

The system was tested successfully using different student enrollment numbers. It was capable of accessing the portal, breaking CAPTCHAs, obtaining results, and generating Excel and PDF reports. The automation ran successfully without human interference, a true testament to the efficiency, precision, and utility of AutoResultGen in automating result extraction for schools.


![image](https://github.com/user-attachments/assets/aa8915a9-485c-4041-bb41-d32e71be277f)

                                  Fig. 5.5 Final Output: Excel
