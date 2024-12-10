
# MediBot: Implementation of Chatbot using NLP  

MediBot is a healthcare-focused chatbot built using Natural Language Processing (NLP) techniques. It is designed to assist users with common health-related queries in a friendly and interactive way. This project also integrates with *Streamlit* to provide a web-based interface for interacting with the bot.  

## Features  
- Predefined intents for health-related queries.  
- Customizable responses tailored for healthcare assistance.  
- Lightweight and easy to deploy using Streamlit.  

---

## How to Use MediBot  

Follow the steps below to clone and run MediBot locally:  

### 1. Clone the Repository  
Open your terminal and run the following command to clone the repository:  
bash  
git clone https://github.com/your-username/MediBot.git  
  
Replace your-username with your actual GitHub username.  

### 2. Navigate to the Project Directory  
bash  
cd MediBot  
  

### 3. Install Dependencies  
Make sure you have Python installed. Then, create a virtual environment (optional but recommended) and install the required dependencies:  
bash  
pip install -r requirements.txt  
  

### 4. Run the Streamlit Application  
Once the dependencies are installed, run the Streamlit app:  
bash  
streamlit run app.py  
  
This command will open the chatbot interface in your default web browser.  

---

## Project Structure  
- *app.py*: Main file for running the Streamlit interface.  
- *intents.json*: Contains the predefined intents and responses for MediBot.  
- *model.py*: Includes NLP implementation to process and classify user inputs.  
- *requirements.txt*: Lists the required Python packages for the project.  
- *README.md*: Instructions on how to use the project.  

---

## How to Customize  
### Modify Intents  
Update the intents.json file to add or edit chatbot intents and responses.  

### Retrain the Model  
If you modify the intents, you may need to retrain the NLP model:  
1. Update the training script (if available, e.g., train.py).  
2. Run the training script to generate a new model.  

### Update the Streamlit UI  
Edit app.py to customize the chatbot interface.  

---

## Contributions  
We welcome contributions to improve MediBot! If you'd like to contribute:  
1. Fork the repository.  
2. Create a new branch for your changes.  
3. Submit a pull request with a clear description of your updates.  

---

## License  
This project is licensed under the [MIT License](LICENSE).  

---

## Contact  
If you have any questions or suggestions, feel free to contact us at devunooribhavana@gmail.com.  

Happy Chatting with MediBot!  

--- 
