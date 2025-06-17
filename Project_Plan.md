 1. **Problem Clarity**

* What **problem** are you solving? -> problems for early children who do not have sense of emoton recognition
* Who will **use** it? users from 5-25
 
 ✅ 2. **Goal Definition**

* What does **success** look like for this project? -> Where children detects emotions by use of AI.
* Is it a **demo**, a **MVP**, or a **full product**? -> MVP
* Are you solving it as a **learning project** or for real users? -> Learning Project

 3. **User and Market Research**

* Who are your **users**? -> children and youth 
* Any **existing tools** solving this problem? -> (OpenFace + FER + AffectNet + DeepFace)


### ✅ 4. **Tech Feasibility**

* Skills Required: Computer Vision, Deep Learning, Python Programming, OpenCV, Data Preprocessing, Facial Landmark Detection, Emotion Classification, Dataset Handling (e.g., FER+, AffectNet), Model Evaluation, Machine Learning Fundamentals, API Integration (optional for deployment)

* Tools Required: Python, OpenCV, TensorFlow, PyTorch, Keras, Dlib, DeepFace, Jupyter Notebook, NumPy, Pandas, Matplotlib, Seaborn, FER Library, MediaPipe (optional), Flask or FastAPI (for deployment), Git, Google Colab or JupyterLab, Visual Studio Code (VS Code)

* Is the AI/ML model **available**, trainable, or too complex for now?  -> trainable with mimal effort/ complex when built from scratch
* Any APIs, datasets, or frameworks available?
*    DeepFace, FER 2013 Dataset, MediaPipe, OpenCn + DNN, Hugging Face Models all are free and available


### ✅ 5. **Scope & Features**

* Define **core features** vs. optional ones (MVP first).
*   System Shall be able to detect user emotion
*   System shall respond according to the emotion


6. **Tool Stack Selection**

* Choose tools based on ease, scalability, and your comfort:

  * Language (Python)
  * Framework (Flask) **not needed as of yet as using local window
  * AI Tools (DeepFace / FER)
  * Camera Feed (OpenCv)
---

### ✅ 7. **Architecture Design**

* Basic **system architecture** diagram
*    It runs locally with OpenCV GUI.
*    WebCam -> Python(Backend) ->DeepFace(AI Model)
* How components (frontend, backend, AI, DB) connect
*    No frontend-backend separation yet. It runs locally with OpenCV GUI.

### ✅ 8. **Data Considerations (For AI Projects)**

* What data do you need?
*    Images or video frames of faces showing different emotions:
*       Happy 😄
*       Sad 😢
*       Angry 😠
* Do you need to **collect**, **scrape**, or **buy** it?
*      Using pre trained model trained on FER-2013
* Do you need to **clean** or label it? NO

### ✅ 9. **Time & Resource Planning**

* How much time do you have? -> 1 year
* What’s your **priority** – learning or launching? -> learning
