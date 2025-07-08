
# 🎙️ Text Narrator 📚

Text Narrator is a web-based tool that allows users to either type text or upload an image containing written text — then have it narrated aloud using Amazon Polly. It's perfect for accessibility, learning, or quick text-to-speech conversion.

## ✨ Features
- 📝 Type or paste any text to hear it narrated
- 📷 Upload a photo of written text — it uses **Textract OCR**
- 🔊 Voice generated with **Amazon Polly**
- 🌐 Built with HTML + AWS Lambda + API Gateway + S3

## 💻 Technologies Used
- Frontend: HTML, CSS, JavaScript
- Backend: AWS Lambda (Python), Amazon Textract, Amazon Polly, Amazon S3, API Gateway

## 🔧 Setup Instructions

1. Clone the repo:
```bash
git clone https://github.com/AsipheMalindi/text-narrator.git
```

2. Deploy your Lambda using AWS Console

3. Host `index.html` via S3 static website hosting

4. Update the API Gateway URL in the frontend script

## 📦 Folder Structure
```
text-narrator/
├── index.html            # Main frontend interface
├── lambda_function.py    # Backend Lambda function
└── README.md             # This file
```

## 🙋‍♂️ Author
**Asiphe Malindi**  
Cloud Associate | Business Analyst | AWS & Web Projects  
📧 http://asiphemalindi1.lovable.app

