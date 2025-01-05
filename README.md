# Job Description Generator Using OpenAI API  

## **Overview**  
This Python-based application generates professional job descriptions by expanding minimal input details using OpenAI's API. The application provides a structured template with AI-enhanced content and allows users to download the generated job descriptions as PDF or Word files.  

## **Features**  
- Generate complete job descriptions from minimal user input.  
- Utilizes OpenAI's API for sentence refinement and content expansion.  
- Output job descriptions in a structured, easy-to-read template.  
- Supports downloading the output in PDF or Word format.  

## **Technologies Used**  
- Python  
- OpenAI API  
- Flask (or your chosen framework for the interface)  
- ReportLab / FPDF / python-docx (for PDF or Word generation)

## **Setup Instructions**

### **1. Clone the Repository**  
```bash  
git clone https://github.com/JanaviN7/job-description-generator-using-openAPI.git  
cd job-description-generator-using-open API  
```  

### **2. Install Dependencies**  
Install required Python dependencies using `pip`.  
```bash  
pip install -r requirements.txt  
```  

### **3. Add OpenAI API Key**  
- Create a `.env` file in the project root directory.  
- Add your OpenAI API key to the file:  
  ```
  OPENAI_API_KEY=your_openai_api_key_here  
  ```  

### **4. Run the Application**  
```bash  
python app.py  
```  
(This will start the application using Flask or your preferred framework.)  

### **5. Access the Application**  
Open your browser and navigate to `http://localhost:5000` (or another URL if hosted).  

## **Usage**  
1. Input the job title, key responsibilities, and required skills in the provided fields.  
2. Click "Generate" to create a structured job description with AI-generated content.  
3. Download the generated job description in PDF or Word format.

## **Future Enhancements**  
- Add a feature to customize templates for different industries.  
- Enable saving and editing previously generated job descriptions.  
- Implement multilingual support for global job postings.

## **License**  
No license applied.  

## **Contributing**  
Contributions are welcome! Feel free to open issues or submit pull requests.  
