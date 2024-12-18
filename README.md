# 🎮 VLDL Mural Wall Name Finder 🏰

A Simple Streamlit app to locate your name on the grand VLDL Mural Wall!

---

App Hosted on Streamlit Community Cloud: https://vldl-mural-wall-name-finder.streamlit.app/

---

## Local Setup

1. Clone the repo:

   ```shell
   git clone https://github.com/JairajJangle/vldl-mural-wall-name-finder.git
   ```

2. Change the directory to the cloned repo folder

   ```shell
   cd vldl-mural-wall-name-finder
   ```

3. Inside this folder, create a Python virtual environment:

   ``` shell
   python3 -m venv venv
   ```

4. Activate the virtual environment:

   ```shell
   source venv/bin/activate
   ```

5. Install the python dependencies:

   ```shell
   pip install requirements.txt
   ```

6. Run the app:

   ```shell
   streamlit run main.py
   ```

---

## How the App was made

1. This app uses a database file that contains a map of Image Name, Word and the Word location in that image.
2. Google Cloud Vision API was used to extract all the text from the images and save their locations to the db. This is a one time job and all this app does is, it queries the database file and finds the word or even word combos and the image name against the found results.
3. I'll be sharing the Google Cloud Vision API code base soon, after some cleanup...

---

###### VLDL Mural Wall Name Finder - Made with ❤️ for Viva La Dirt League fans.

###### Crafted with care by [JairajJangle](https://github.com/JairajJangle)