**Hand Sign Recognition Using Machine Learning**
This project demonstrates a hand recognition system built with TensorFlow, OpenCV, and Machine Learning techniques. It allows users to interact using hand signs, collect custom data, and recognize alphabets via gestures.

**Features**
- Real-time Hand Sign Recognition: Detects and interprets hand signs.
* Custom Data Collection: Collect hand gesture data for training.
+ Alphabet Display: Recognizes hand signs and displays corresponding alphabets.
   
**Project Structure**
- app.py: Main application for recognizing hand signs.
* datacollection.py: Script to collect custom hand gesture data from users.
+ test.py: Tests and displays alphabets based on recognized hand gestures.
   
**Requirements**
Make sure to install the required dependencies before running the scripts.

**bash:**
pip install -r requirements.txt

**Usage**
1. Data Collection
Run th datacollection.py script to collect data for training the model:
**bash:**
python datacollection.py

2. Hand Sign Recognition
Use the app.py script to recognize hand signs in real time:
**bash:**
python app.py

3. Testing Hand Signs
Test the system's ability to display alphabets using test.py:
**bash:**
python test.py

**Dependencies**
1. Python
2. TensorFlow
3. OpenCV
4. NumPy

**Setup**
1. Clone this repository:
**bash:**
git clone https://github.com/your-repo-name.git
cd your-repo-name

2. Install the virtual environment:
**bash:**
python -m venv env
source env/bin/activate  # Use `env\Scripts\activate` on Windows

4. Install dependencies:
**bash:**
pip install -r requirements.txt
