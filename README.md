# 🎓 SIES GST Certificate Generator

A specialized web-based automation tool developed for the **Computer Engineering Department at SIES Graduate School of Technology**. This application allows faculty to generate high-quality, standardized internship certificates instantly by simply inputting student details.

##  Features
* **Automated Design:** Stamps student data onto the official SIES GST internship template.
* **Real-time Validation:** Includes a **30-character limit** on student names to ensure perfect visual alignment on the certificate.
* **Cursive Typography:** Uses the **Great Vibes** calligraphy font for an authentic, hand-signed appearance.
* **Browser-Based Processing:** Uses the **HTML5 Canvas API** to process images locally—no data is sent to a server, ensuring student privacy.
* **Mobile Friendly:** Fully responsive CSS designed for faculty to use on-the-go via smartphones.

##  Tech Stack
* **Frontend:** HTML5, CSS3 (Flexbox & CSS Gradients).
* **Logic:** JavaScript (Asynchronous Font Loading & Canvas API).
* **Deployment:** Netlify.

## 📂 Project Structure
```text
Certificate-Generator/
├── index.html     # Main application logic and structure
├── style.css      # Branding and responsive styling
├── template.jpg   # The official SIES GST blank certificate
└── font.ttf       # Great Vibes TrueType font file

## 📖 How to Use
1. **Enter the Student Full Name**: Please keep this under **30 characters** to ensure it fits perfectly on the certificate line.
2. **Input the Certificate ID**: Use the departmental format, for example: `CE/INT/2026/01`.
3. **Provide Details**: Enter the specific **Internship Dates** and the **Project Title** (e.g., Feedback System).
4. **Click Generate & Download**: The browser will instantly process the image and trigger a `.png` download.

## 👨‍💻 Author
**Vrushabh Deepak Shirke** *Computer Engineering Student, SIES GST*