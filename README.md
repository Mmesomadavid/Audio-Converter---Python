![speechai](https://github.com/Mmesomadavid/AI---speech-recognition/assets/108488301/954d4b83-0fa7-48f7-8bda-35d05fe0917d)
# Speech Recognition Web App

This web application allows users to upload audio files for speech recognition. The app is built using Python with Flask for the backend and HTML/CSS for the frontend.

## Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Mmesomadavid/speech-recognition-app.git
    ```

2. **Navigate to the Project Directory:**

    ```bash
    cd speech-recognition-app
    ```

3. **Install Dependencies:**

    Ensure you have Python installed. Then, create a virtual environment and install the required packages.

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'
    pip install -r requirements.txt
    ```

## Running the App

4. **Run the Flask App:**

    ```bash
    flask run
    ```

    Open your browser and go to `http://127.0.0.1:5000` to access the web app.

## Usage

- Upload an audio file using the "Choose File" button.
- Click on the "Submit" button for speech recognition.
- View the transcript below the upload section.

## Design Details

- The "Choose File" input has a transparent background, a dotted border, and a download icon in the middle.
- The transcript text area has a design inspired by the ChatGPT interface.

## Media Responsiveness

The web app is designed to be responsive, adapting to different screen sizes, including smartphones and tablets.

Feel free to customize and extend the functionality according to your requirements!
