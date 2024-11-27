# 👋 Hey, Let's understand a research field in 5 minutes!

*   This notebook automatically fetches citation information of a specific paper from google scholar.
*   If a citation is availble on arxiv, its full abstract will be extracted.
*   The information will be saved in a text file with a prompt to let an LLM to summarize the citations.
*   Please run it on Google Colab to get fast access to Google Scholar.

### 💡Step 1: Install Dependancies
Just click the "run" button in the notebook.

### 📚 Step 2: Find a famous paper in this field on Google scholar and get its citedby_id
How to acquire the citedby_id?

1. You can first search a paper on Google Scholar by the title, like:

<div align=center>
	<img width = '500' height ='150' src = "https://github.com/user-attachments/assets/946af137-110b-474d-87fa-0c59d7fcb4e7"/></div>

2. Then please click the **"cited by xxxx"** page, like:

<div align=center>
	<img width = '500' height ='90' src = "https://github.com/user-attachments/assets/4d38607d-b3c7-4701-be84-463284834471"/></div>

3. Now you will see the **citedby_id** in the url of the web page.

<div align=center>
	<img width = '500' height ='50' src = "https://github.com/user-attachments/assets/986e09ec-555f-4cae-b03a-cc93d3a7d2a1"/></div>

### 💪 Step 3: Set the citedby_id below and generate the prompt file

Note: 

* You can only access a limited number of citations in a single search (perhaps under 120), other wise Google will block your IP address.
* **No worries!** You are using Google colab! If Google blocks you, just restart the kernal of this notebook!

### 🎉 Step 4: Ask any LLM (ChatGPT, Claude, ChatGLM...) with the generated prompt file
Happy researching! 😊
 




