# DLH-Project-Text-EGM
# Create a virtual environment named 'envname' with 
 python3 -m venv venv
 or
 python -m venv venv

# Activate the environment # On macOS/Linux: 
source venv/bin/activate
or 
on Windows: venv\Scripts\activate

# Upgrade pip (optional but recommended) 
pip install --upgrade pip

# For mac I used this command 
curl -O https://physionet.org/static/published-projects/iafdb/intracardiac-atrial-fibrillation-database-1.0.0.zip
Instead of
wget https://physionet.org/static/published-projects/iafdb/intracardiac-atrial-fibrillation-database-1.0.0.zip

ON windows, I did:
curl -o iafdb.zip https://physionet.org/static/published-projects/iafdb/intracardiac-atrial-fibrillation-database-1.0.0.zip

