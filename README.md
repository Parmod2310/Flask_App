# Flask Regex Matcher Web App

🚀 **Regex Matcher and Email Validator**

This project is a web application built using **Flask** that allows users to test regular expressions against custom input strings. The app provides real-time visualization of regex matches and includes additional features like email validation. The application is deployed on **AWS** and features a responsive design with modern UI elements.🌐

---

## Features ✨

- **Regex Matching**: Test any regular expression against input strings.
- **Email Validation**: Quickly verify if an email address is valid.
- **Responsive Design**: Clean, modern UI with smooth animations for better user experience.
- **AWS Deployment**: Fully deployed and accessible on the web.

---

## Getting Started 🏁

### Prerequisites 🛠️

To get started, make sure you have the following installed:

- Python 3.8+  🐍
- Flask: You can install it using pip:

   ```bash
   pip install flask
   ```

## Installation ⚙️
1. Clone the repository:

    First, clone the repository to your local machine:
    ```bash
   git clone https://github.com/Parmod2310/Flask_App.git
   cd Flask_App
    ```
2. Set up a virtual environment:

    It's a good practice to set up a virtual environment for your project. You can do this with the following command:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   Install the required dependencies for the app:

   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:

    Once the dependencies are installed, you can run the Flask app:

    ```bash
      python app.py
    ```
5. Access the app:

    Open your browser and navigate to http://127.0.0.1:5000 to access the app locally.🌍

---

## Screenshots 📸
   Here is a screenshot of the Regex Matcher Web App:




---

## Deployment 🌐
The app is deployed on **AWS** for public access. You can access the live application via the following link:
Deployed Application💻

To deploy the app on AWS:

1. Set up an EC2 instance with a public IP. 🖥️
2. Configure security groups to allow HTTP traffic. 🔒
3. Use gunicorn or uwsgi for serving the Flask app in production. ⚙️
4. Configure nginx as a reverse proxy. 🔄

---

## 🗂️ Project Structure 
Here’s a quick overview of the project’s folder structure:  
```plaintext
Flask_App/
├── static/               # Static files (CSS, Images)
│   ├── style.css
│   └── images/
├── templates/            # HTML Templates
│   ├── index.html
│   └── results.html
└── app.py                # Main Flask Application
```

---

## 🙏 Acknowledgements
This project was developed as part of my internship at  [Innomatics Research Labs](https://www.innomatics.in)., under the mentorship of **Kanav Bansal**.
I learned a great deal about Flask, AWS deployment, and regular expressions during this internship. Special thanks to my mentor for the continuous support and guidance throughout the process.💡

--- 

## 📄 License

This project is licensed under the MIT License.  
Feel free to use, modify, and distribute as per the terms of the license.

---

## 📬 Contact

If you have any questions, feel free to reach out:

- **Email**: p921035@gmail.com  
- **LinkedIn**: [Parmod's LinkedIn Profile](https://www.linkedin.com/in/parmod2310/)  
