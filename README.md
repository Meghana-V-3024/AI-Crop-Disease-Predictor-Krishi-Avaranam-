# AI Crop Disease Predictor - Krishi Avaranam 🌱

A state-of-the-art Plant Disease Detection system that uses Machine Learning and AI to identify plant diseases from images. This project combines TensorFlow for disease detection and Google Generative AI for interactive chatbot support.

## 🌟 Features

- **Advanced Disease Detection**: Uses a pre-trained TensorFlow model to detect 38 different plant diseases
- **AI Chatbot Support**: Integrated Google Generative AI for real-time plant health assistance
- **User-Friendly Interface**: Beautiful Streamlit web application
- **History Tracking**: Maintains a database of all disease detection results
- **Multi-Crop Support**: Detects diseases in various crops including:
  - Tomatoes (Early Blight, Yellow Curl Virus, Healthy)
  - Potatoes (Early Blight, Healthy)
  - Corn (Common Rust)
  - Apples (Scab, Cedar Rust)

## 🚀 Quick Start

### Prerequisites
- Python 3.8 or higher
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Meghana-V-3024/AI-Crop-Disease-Predictor-Krishi-Avaranam-.git
   cd AI-Crop-Disease-Predictor-Krishi-Avaranam-
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   python -m streamlit run main.py
   ```

4. **Access the application**
   - Open your browser and go to: `http://localhost:8501`
   - Or double-click `run_app.bat` (Windows)

## 📁 Project Structure

```
AI-Crop-Disease-Predictor-Krishi-Avaranam-/
├── main.py                          # Main Streamlit application
├── requirements.txt                 # Python dependencies
├── README.md                       # Project documentation
├── run_app.bat                     # Windows batch file to run the app
├── .gitignore                      # Git ignore file
├── trained_plant_disease_model.keras # Pre-trained TensorFlow model
├── test/                           # Test images directory
│   └── test/                       # Sample plant images for testing
├── *.db                           # SQLite database files
└── uploaded_image.jpg             # Sample uploaded image
```

## 🛠️ Technologies Used

- **Frontend**: Streamlit
- **Machine Learning**: TensorFlow, Keras
- **AI Chatbot**: Google Generative AI (Gemini)
- **Database**: SQLite
- **Image Processing**: PIL (Pillow)
- **Data Processing**: NumPy, Pandas

## 📊 Dataset Information

The system uses an enhanced dataset with approximately 87,000 RGB images:
- **Training Set**: 70,295 images
- **Testing Set**: 33 images  
- **Validation Set**: 17,572 images
- **Classes**: 38 distinct plant disease categories

## 🎯 How to Use

1. **Navigate to Disease Recognition**: Select "Disease Recognition" from the sidebar
2. **Upload Image**: Click "Browse files" and select a plant image
3. **Get Results**: The system will analyze the image and display:
   - Disease prediction
   - Confidence score
   - Recommendations
4. **Chat Support**: Use the "Chat Support" page for additional plant health questions
5. **View History**: Check "History" to see all previous detections

## 🔧 Configuration

### Google Generative AI Setup
The application uses Google Generative AI for chatbot functionality. The API key is configured in the code:
```python
genai.configure(api_key="YOUR_API_KEY")
```

### Model Configuration
The system uses a pre-trained TensorFlow model (`trained_plant_disease_model.keras`) that can detect 38 different plant diseases.

## 📱 Application Pages

1. **Home**: Overview and introduction to the system
2. **About**: Detailed information about the project and technology
3. **Disease Recognition**: Main feature for uploading and analyzing plant images
4. **Chat Support**: AI-powered chatbot for plant health queries
5. **History**: Database of all previous disease detection results

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Meghana V**
- GitHub: [@Meghana-V-3024](https://github.com/Meghana-V-3024)

## 🙏 Acknowledgments

- Dataset: Enhanced plant disease dataset with 87,000+ images
- TensorFlow: For machine learning capabilities
- Google Generative AI: For chatbot functionality
- Streamlit: For the web interface

## 📞 Support

If you encounter any issues or have questions:
1. Check the [Issues](https://github.com/Meghana-V-3024/AI-Crop-Disease-Predictor-Krishi-Avaranam-/issues) page
2. Create a new issue with detailed information
3. Use the chat support feature in the application

---

**Note**: The trained model file (`trained_plant_disease_model.keras`) is large (90MB). GitHub may show a warning about large files, but the file will still be uploaded successfully.

⭐ **Star this repository if you find it helpful!**
