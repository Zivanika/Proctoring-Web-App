<h1 align="center">Video Proctoring System</h1>

<p>Online examinations require human invigilation either by live monitoring or inspection of recorded video to ensure academic integrity. This process is not feasible always since exams can be taken at any time and it involves high cost. This project proposes an Online Proctoring System to automate invigilation processes. A computer vision-based system that detects gaze direction, mobile phone usage, and multiple people in a video feed using TensorFlow, OpenCV, and FER (Facial Emotion Recognition) library. The system helps identify potential cheating or distractions by analyzing frames from a camera feed.</p>

[Visit Now]() 🚀

## 🖥️ Tech Stack

**Frontend:**

![nextjs](https://img.shields.io/badge/next%20js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)&nbsp;
![tailwindcss](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)&nbsp;
![axios](https://img.shields.io/badge/Axios-20232A?style=for-the-badge&logo=axios&logoColor=61DAFB)&nbsp;

**Backend:**

![mongodb](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)&nbsp;
![python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)&nbsp;
![fastapi](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)&nbsp;
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)&nbsp;
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)&nbsp;
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)&nbsp;
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)&nbsp;


## 📌 Key Features:

<dl>
<dt>🎥 Live Webcam Feed:</dt>
<dd> Stream real-time video from the candidate's webcam for continuous monitoring.</dd>

<dt>👤 Face Detection:</dt>
<dd> Detects absence of face or multiple faces in the frame to ensure candidate authenticity.</dd>

<dt>📱 Object Detection:</dt>
<dd> Identifies prohibited objects such as mobile phones using advanced detection models.</dd>

<dt>📝 Real-Time Event Logging:</dt>
<dd> Logs suspicious events with precise timestamps for reliable monitoring.</dd>

<dt>📄 Downloadable Proctoring Report:</dt>
<dd> Generate and download a detailed PDF report summarizing all detected events.</dd>
</dl>

## 📌 Screenshots:

![home](/img/Home.png)
![report](/img/Report.png)

## 🚀 Getting Started:

Before you begin, ensure you have the following installed on your local machine:

- [Node.js](https://nodejs.org/) (v14 or later)
- [npm](https://www.npmjs.com/) (v6 or later) or [Yarn](https://yarnpkg.com/) (v1 or later)
- [Python](https://www.python.org/) (3.8+ recommended)
- [pip](https://pip.pypa.io/en/stable/) package manager

## 🏠 Running the Project Locally:

Follow these steps to run the Next.js project on your local machine:

1.  **Clone the Repository:**

    ```sh
    git clone https://github.com/Zivanika/Proctoring-Web-App.git
    cd
    ```

2.  **Install Dependencies:**

    Frontend using npm:

    ```sh
    npm install
    ```

    Backend using pip:

    ```sh
    pip install -r requirements.txt
    ```
    ## Download TensorFlow model

    curl -O http://download.tensorflow.org/models/object_detection/ssd_mobilenet_v2_coco_2018_03_29.tar.gz
    tar -xvzf ssd_mobilenet_v2_coco_2018_03_29.tar.gz

    ## Ensure correct moviepy version

    pip install moviepy==1.0.3

3. **Run the Development Server:**

   Frontend using npm:

   ```sh
   npm run dev
   ```

   Backend using Uvicorn:

   ```sh
   uvicorn server:app --host 0.0.0.0 --port 8000 --reload
   ```

4. **Open Your Browser:**

   Open your browser and navigate to [http://localhost:3000](http://localhost:3000). You should see the Next.js application running!

## 📜 License:

This project is licensed under the MIT License.


[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
