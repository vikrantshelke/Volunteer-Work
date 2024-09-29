## Creating your own ChatGPT with Streamlit and OpenAI API

### Prerequisites
1. Python 3.6 or above
2. An OpenAI API Key

### App Demo
![](https://private-user-images.githubusercontent.com/48050596/254776334-e1c62c71-0b3d-4a3b-9855-e48fc73e402b.gif?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Mjc2NDc0MzgsIm5iZiI6MTcyNzY0NzEzOCwicGF0aCI6Ii80ODA1MDU5Ni8yNTQ3NzYzMzQtZTFjNjJjNzEtMGIzZC00YTNiLTk4NTUtZTQ4ZmM3M2U0MDJiLmdpZj9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA5MjklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwOTI5VDIxNTg1OFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTg1Y2VjYjc5MTUwYjRiODNkYzYxYTk4MjI4NGVkMDM2YWNhZTdkOWFmZjljZTgxODZkMGNhOWM4NjMzZTViZTEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.EAszT0zAregf9ZwBlh0f99AEmpqUbpnFfWox2PC7jyo)

### Steps to run the application
**1. Navigate to the project directory:**
```shell
cd Volunteer-Work/Week_2
```

3. Create a virtual environment and activate it:

On macOS and Linux:
```shell
python3 -m venv myenv
source myenv/bin/activate
```

On Windows:
```shell
python -m venv myenv
.\myenv\Scripts\activate
```

3a. Upgrade pip (optional but recommended)
```shell
pip install --upgrade pip
```

4. Install the necessary Python packages:
```shell
pip install -r requirements.txt
```

5. Create a .env file in the root directory of the project and add your OpenAI API key:
```shell
echo OPENAI_API_KEY=your-api-key > .env
```
OR

```shell
cp .env.example .env
```

Please replace your-api-key with your actual OpenAI API key.

6. Run the Streamlit application:
```shell
streamlit run chatbot.py
```

Open a web browser and navigate to http://localhost:8501 to interact with the application.
