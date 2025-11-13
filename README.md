# Smart Home Energy Saver

This project is a Smart Home Energy Saving application designed to optimize energy consumption in smart homes. It uses machine learning models to predict energy usage and provides actionable insights to save energy.

## Setup Instructions

### 1. Create a Virtual Environment

#### For Windows:
```cmd
python -m venv venv
venv\Scripts\activate
```

#### For macOS/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

### 2. Install Dependencies
Once the virtual environment is activated, install the required dependencies:
```bash
pip install -r requirements.txt
```

### 3. Configure Environment Variables
Create a `.env` file in the root directory of the project and add the following environment variables:

### 4. Add `.env` file:
Set these environment configs:

    AZURE_OPENAI_ENDPOINT = "your-azure-openai-endpoint"

    AZURE_OPENAI_CHAT_DEPLOYMENT_NAME = "gpt-4o-mini"


### 5. Update Email Agent
Open the `email_agent.py` file and update your email id.

### 6. Generate Email Password/Token
Follow the link below to generate the email password or token:
[Generate Email Password/Token](https://myaccount.google.com/apppasswords)

### 7. Start the Applications

To start the UI application, run the following command in one terminal:
```cmd
python app.py
```

To start the Streamlit application, run the following command in another terminal:
```cmd
streamlit run streamlit_app.py
```

---

Once all the steps are completed, you can run the application and start optimizing your smart home energy usage!