# 🌾 Crop Recommendation System

Welcome to the **Crop Recommendation System** repository! This project leverages machine learning to suggest the most suitable crop for cultivation based on soil and environmental parameters. Designed for farmers, agricultural enthusiasts, and researchers, this system helps in efficient crop planning and resource utilization.

---

## 📋 Features

- **Input Parameters**: Supports parameters like Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, and Rainfall.
- **Machine Learning Model**: Recommends the best crop based on trained data.
- **Interactive UI**: User-friendly form for entering input values.
- **Real-Time Results**: Displays crop recommendations instantly.
- **Validation**: Ensures numeric-only inputs with error handling.

---

## 🛠️ Installation and Setup

Follow these steps to set up the project on your local machine:

### Prerequisites

1. Python 3.7+
2. Flask
3. Bootstrap (integrated via CDN)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/crop-recommendation-system.git
   cd crop-recommendation-system
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:

   ```bash
   python app.py
   ```

4. Open your browser and navigate to:

   ```
   http://127.0.0.1:5000
   ```

---

## 🚀 How It Works

1. **Input Parameters**: The user provides soil and environmental parameters.
2. **Validation**: Inputs are validated to ensure accuracy.
3. **Machine Learning Model**: The backend processes the inputs and predicts the best crop using a pre-trained model.
4. **Result Display**: The recommended crop is displayed in the results section.

---

## 📂 Project Structure

```plaintext
├── static/
│   ├── css/            # Stylesheets
│   └── images/         # Placeholder for UI images
├── templates/
│   ├── index.html      # Main HTML file
├── app.py              # Flask application
├── model.pkl           # Pre-trained ML model
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

---

## 🌟 Key Highlights

- **Real-Time Input Validation**: Ensures accurate data entry.
- **Smooth Scrolling**: The form submission automatically navigates to the results section.
- **Mobile Responsive Design**: Optimized for devices of all sizes.

---

## 🤝 Contributing

We welcome contributions! Feel free to fork the repository, make your changes, and submit a pull request.

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## 🧪 Sample Inputs

| Parameter   | Example Value |
| ----------- | ------------- |
| Nitrogen    | 45.0          |
| Phosphorus  | 35.0          |
| Potassium   | 50.0          |
| Temperature | 27.5 °C       |
| Humidity    | 75.0 %        |
| pH          | 6.5           |
| Rainfall    | 200.0 mm      |

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 📧 Contact

For any inquiries or feedback, please reach out to:

- **Name**: Gayathri 
- **Email**: gayathrirasangikahw@gmail.com
- **GitHub**: https://github.com/Gaya39877

---

Thank you for exploring the **Crop Recommendation System**! 🌱

