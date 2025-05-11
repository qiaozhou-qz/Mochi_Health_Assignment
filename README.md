Run the following commands in your Mac Terminal or Windows Command

Step 1: Clone the Repository

git clone https://github.com/qiaozhou-qz/Mochi_Health_Assignment.git

cd Mochi_Health_Assignment

Step 2: Set Up a Virtual Environment 

python -m venv venv(if python3 is installed, use python3; use this line of command to check if python3 is installed: python3 --version)

On windows: venv\Scripts\activate

On Mac: source venv/bin/activate

Step 3: Install Dependencies

pip install -r requirements.txt

Step 4: Run the Streamlit App

streamlit run app.py
