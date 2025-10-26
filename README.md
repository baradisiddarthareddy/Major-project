# Major-project
It is a Deep learning Application developed in team of three members as a Major project in final year of graduation
# MedAI Nexus

**MedAI Nexus** is an innovative AI-powered solution designed to detect, recognize, and extract meaningful information from handwritten doctor prescriptions. It leverages cutting-edge Deep Learning and Natural Language Processing (NLP) techniques to enhance patient safety, streamline healthcare workflows, and ensure accurate interpretation of prescriptions.

## 🚀 Features

- 🔍 **Handwritten Text Detection & Recognition**  
  Utilizes transformer-based encoder-decoder models (e.g., TrOCR) for accurate interpretation of handwritten text in prescription images.

- 🧠 **Intelligent NLP Processing**  
  Named Entity Recognition (NER) using BERT and spaCy to extract and categorize critical entities such as medicine names, dosages, and usage instructions.

- 🎯 **Post-Processing & Refinement**  
  Implements custom scripts for noise reduction, fuzzy matching, error correction, and structured formatting of recognized text.

- 💻 **User-Friendly Web Interface**  
  A React-based frontend allows users to upload prescription images and view extracted medical information in a clean, intuitive interface.

- ⚙️ **Backend Architecture**  
  Built with PyTorch for model training and inference, leveraging GPU acceleration for high performance.

## 🏗️ System Architecture

1. **Preprocessing & Text Localization**  
   Feature extraction and bounding box detection isolate relevant text regions from input images.

2. **Text Recognition**  
   A transformer-based encoder-decoder model processes localized image regions to generate structured text.

3. **Named Entity Recognition (NER)**  
   Contextual embeddings via BERT identify and classify key medical entities like drug names and dosages.

4. **Post-Processing Pipeline**  
   Custom scripts clean noisy text, correct OCR errors, and enhance output readability using fuzzy string matching.

5. **Frontend & Visualization**  
   ReactJS interface displays extracted prescription details to users and healthcare providers in real time.

## 🧰 Tech Stack

| Category                | Tools & Frameworks                     |
|------------------------|----------------------------------------|
| Deep Learning          | DBNet,TrOCR,CRNN                       |
| NLP                    | Bio BERT,Biom BERT                     |
| Frontend               | ReactJS                                |
| Backend/API            | Python, Flask/FastAPI (optional)       |
| Image Processing       | OpenCV, PIL                            |
| Development Tools      | Visual Studio Code, Git, GitHub        |

## 📷 Example Use Case

1. User uploads an image of a handwritten prescription.
2. The system detects and extracts text from the image.
3. Extracted content is processed to identify medicines, dosages, and instructions.
4. Final output is displayed clearly on the web interface for both patients and providers.

## 🛠️ Installation

> **Note:** Ensure you have Python 3.8+, Node.js, and Git installed.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/medai-nexus.git
   cd medai-nexus
## Snaps of Project

# Hero page
 <img width="959" height="437" alt="Homepage" src="https://github.com/user-attachments/assets/9dcc10b3-d874-4a1e-908b-4a27fc34d863" />


# Signup and Login page

 <img width="960" height="433" alt="signupmed" src="https://github.com/user-attachments/assets/6f1ceca0-9038-4a3e-b9c8-acc2a4595848" />


 <img width="960" height="439" alt="LoginMed" src="https://github.com/user-attachments/assets/30266132-1da5-493a-91aa-fc24e60c13cd" />


# Main page

  <img width="960" height="431" alt="Mainpagemed" src="https://github.com/user-attachments/assets/c36f665e-5138-4772-b781-42a11e4cab2b" />


# Sample output 
   
 <img width="889" height="402" alt="OutputMed" src="https://github.com/user-attachments/assets/5ab6bcb1-6f1d-4c8f-8ad1-34a35885656d" />






