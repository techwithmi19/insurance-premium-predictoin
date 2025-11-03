# create environment
python -m venv myenv

# activate the environment
myenv\Scripts\activate

# install packages
pip install -r requirements.txt

# run the server
uvicorn app:app --reload
