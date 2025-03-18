# AI DermoScope

## Overview
AI DermoScope is an advanced healthcare web application designed to detect skin diseases using deep learning techniques. The platform leverages the MobileNet architecture and is trained on the DermNet dataset, along with additional image datasets, to ensure accurate skin disease classification. 

## Features
- **AI-Powered Disease Detection:** Uses deep learning to analyze skin images and provide potential disease predictions.
- **User-Friendly Interface:** A simple and interactive UI for users to upload images and receive diagnostic insights.
- **Fast & Efficient Processing:** Optimized model for quick response times with high accuracy.
- **Secure & Scalable Architecture:** Implements best security practices to protect user data and ensures scalability for future enhancements.
- **Separate Backend & AI Model Repositories:** Maintains clean and modular code for efficient development and deployment.
- **Database Integration:** Stores user diagnosis history and reports for future reference.

## Technologies Used
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js, MongoDB
- **AI Model:** Python, Flask, TensorFlow, Keras, MobileNet
- **Dataset:** DermNet, Additional Image Datasets
- **Deployment:** Docker, AWS/GCP (Planned)

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- Node.js & npm
- Python & pip
- MongoDB (for storing user data and history)
- Virtual environment (optional but recommended for Python dependencies)

### Backend Setup
1. Clone the backend repository:
   ```sh
   git clone https://github.com/MuhammadAsimKundi/AI-DermaScope-Backend.git
   cd AI-DermaScope-Backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the server:
   ```sh
   npm start
   ```

### AI Model Setup
1. Clone the AI model repository:
   ```sh
   git clone https://github.com/MuhammadAsimKundi/AI-DermaScope-AI.git
   cd AI-DermaScope-AI
   ```
2. Create a virtual environment and install dependencies:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use 'venv\Scripts\activate'
   pip install -r requirements.txt
   ```
3. Run the AI model API:
   ```sh
   python app.py
   ```

### Frontend Setup
1. Clone the frontend repository:
   ```sh
   git clone https://github.com/MuhammadAsimKundi/AI-DermaScope-Frontend.git
   cd AI-DermaScope-Frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the frontend application:
   ```sh
   npm start
   ```

## Usage
1. Open the frontend application in your browser.
2. Register/Login to manage past diagnoses.
3. Upload a skin image for analysis.
4. The AI model will process the image and provide a probable disease prediction.
5. Users can view past diagnoses and additional information on detected conditions.

## Future Enhancements
- **Multi-Disease Classification:** Expand the model to detect more skin conditions with higher accuracy.
- **Doctor Consultation Module:** Enable users to consult dermatologists based on AI predictions.
- **Mobile Application:** Develop an Android/iOS version for better accessibility.
- **Cloud-Based Deployment:** Improve scalability using cloud-based services.
- **Real-Time AI Processing:** Enhance prediction speed for real-time results.

## Contribution Guidelines
We welcome contributions! If you’d like to improve the project, follow these steps:
1. Fork the repository.
2. Create a new branch (`feature-branch-name`).
3. Commit your changes and push them.
4. Submit a pull request for review.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact
For any inquiries, suggestions, or collaborations, feel free to reach out:
- **Muhammad Asim Kundi**  
- Email: [muhammadasimkundi@gmail.com](mailto:muhammadasimkundi@gmail.com)  
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/muhammad-asim-kundi)  
- GitHub: [Muhammad Asim Kundi](https://github.com/MuhammadAsimKundi)  

---
**AI DermoScope - Empowering Healthcare with AI**

