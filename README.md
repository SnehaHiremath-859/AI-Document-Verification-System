# 📄 DocuAI – AI Document Verification System

DocuAI is a web-based document intelligence application built with React and Vite. It provides a user-friendly workspace where users can upload, organize, analyze, and understand their documents.

The application uses Optical Character Recognition (OCR) to extract text from document images and provides document insights to help users understand their information.

## ✨ Features

* **Document Upload:** Upload multiple document files, including images and PDFs.
* **Document Library:** View, organize, select, and manage uploaded documents.
* **Text Extraction:** Extract text from document images using Tesseract.js OCR.
* **Document Analysis:** Generate document insights from extracted text.
* **AI Assistant Interface:** Ask questions about analyzed documents and receive responses for supported queries.
* **Interactive Dashboard:** Navigate between the dashboard, document library, and assistant.
* **Responsive Interface:** A modern interface designed to make document management easier.

## 🛠️ Technologies Used

* React
* Vite
* JavaScript
* HTML5
* CSS3
* Tesseract.js (OCR)

## 🚀 Getting Started

Follow these steps to run DocuAI on your local machine.

### Prerequisites

Install the following before getting started:

* Node.js
* npm
* Git

### 1. Clone the Repository

```bash
git clone https://github.com/SnehaHiremath-859/AI-Document-Verification-System.git
```

### 2. Navigate to the Project Directory

```bash
cd AI-Document-Verification-System
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

```bash
npm run dev
```

Open the local URL displayed in your terminal to access DocuAI in your browser.

## 🏗️ Build for Production

To create a production build, run:

```bash
npm run build
```

To preview the production build locally, run:

```bash
npm run preview
```

## 🌐 Live Demo

Explore the deployed application:

https://ai-document-verification-system-zeta.vercel.app/

## ⚠️ Current Limitations

* PDF text extraction is not enabled in the current frontend implementation.
* Image text extraction depends on the clarity and readability of the uploaded image.
* The assistant uses predefined question-handling logic and document insights; it is not currently connected to an external generative AI service.
* Document processing and storage are handled within the current frontend application; a persistent backend storage system is not included.

## 🔮 Future Enhancements

* Enable OCR for PDF documents.
* Integrate a generative AI model for more flexible document question answering.
* Add secure user authentication.
* Implement backend storage for uploaded documents.
* Enhance document verification and information validation capabilities.

## 👩‍💻 Author

**Sneha Hiremath**

GitHub: https://github.com/SnehaHiremath-859

## 📜 License

This project is intended for educational and portfolio purposes.
