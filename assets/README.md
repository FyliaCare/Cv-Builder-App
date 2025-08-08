
---

# **CV Builder Web App**

A **Streamlit-based** application for creating professional CVs quickly and efficiently.
Users can upload a profile photo, enter personal details, preview their CV, and export it as a **.docx** file.

**Developed by:** **Philip Jojo Montford** – essonmontford@outlook.com.

---

## **Features**

* 📸 **Photo Upload** – Include a profile image in your CV.
* 📝 **Personal & Professional Details** – Enter contact info, skills, experience, and more.
* 👀 **Live Preview** – See your CV layout before downloading.
* 📄 **Export to Word (.docx)** – One-click professional CV generation.
* 🎯 **Easy to Use** – Works in any browser, no installation needed for end users.

---

## **Tech Stack**

* **Frontend & Backend:** [Streamlit](https://streamlit.io/)
* **Document Generation:** [`python-docx`](https://python-docx.readthedocs.io/)
* **Image Handling:** [`Pillow`](https://python-pillow.org/)

---

## **Installation & Setup**

1. **Clone this repository**

   ```bash
   git clone https://github.com/your-username/cv-builder.git
   cd cv-builder
   ```

2. **Create a virtual environment (optional but recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Mac/Linux
   venv\Scripts\activate      # On Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the app locally**

   ```bash
   streamlit run app.py
   ```

5. **Open in browser**
   Streamlit will open automatically, or visit:

   ```
   http://localhost:8501
   ```

---

## **Deploying on Streamlit Cloud**

1. Push your code to a GitHub repository.
2. Go to [https://share.streamlit.io/](https://share.streamlit.io/) and log in.
3. Click **New app** → Select your repo, branch, and `app.py`.
4. Click **Deploy** – your app will be live at:

   ```
   https://your-username-your-repo.streamlit.app
   ```

---

## **Requirements**

```
streamlit
pillow
python-docx
```

*(Add any extra libraries you use, such as `jinja2` if applicable)*

---

## **License**

This project is free – feel free to use and modify for your own needs.

---

