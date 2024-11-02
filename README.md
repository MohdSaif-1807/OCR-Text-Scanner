# OCR-Text-Scanner

OCR-Text-Scanner is a powerful application designed to extract and display data from images, specifically tailored for Indian passports and driving licenses from Maharashtra. 

## Features

- **Data Parsing**: Efficiently extracts essential information from images of Indian passports and driving licenses.
- **User-Friendly Interface**: Built with React and Tailwind CSS for a responsive and intuitive user experience.

## Tech Stack

- **Backend**: Flask
  - Utilizes **Tesseract** for Optical Character Recognition (OCR) to parse data from images.
  - Employs **Regex** for precise information extraction from the parsed data.
  
- **Frontend**: React with Tailwind CSS
  - Ensures a clean and modern interface for users.

## Getting Started

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/OCR-Text-Scanner.git
   cd OCR-Text-Scanner
   ```

2. **Install Backend Dependencies**:
   Navigate to the backend directory and install the required packages:
   ```bash
   cd backend
   pip install <package_name>
   ```

3. **Run the Backend**:
   Start the Flask server:
   ```bash
   python server.py
   ```

4. **Install Frontend Dependencies**:
   Navigate to the frontend directory and install the required packages:
   ```bash
   cd frontend
   npm install
   ```

5. **Run the Frontend**:
   Start the React application:
   ```bash
   npm start
   ```

6. **Access the Application**:
   Open your browser and go to `http://localhost:3000` to use the OCR-Text-Scanner.

## Screenshots 

Dashboard page:

![image](https://github.com/user-attachments/assets/a99f6d3b-2fb5-495c-8566-d372d599e97f)


Uploaded driving license image:

![image](https://github.com/user-attachments/assets/acc6664c-38be-4ca8-9d13-b1d694265150)


After parsing of data from the image:

![image](https://github.com/user-attachments/assets/571ca8ae-01ae-409e-82e3-778e9a50b703)


Parsed data:

![image](https://github.com/user-attachments/assets/d30f84a9-13c5-4367-89b9-957af0db800f)











