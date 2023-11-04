<!-- 
Hugginface METADATA
title: NeuroHealthCareBot! 
emoji: 🚀
colorFrom: #FF5733
colorTo: #FFBF00
sdk: streamlit
sdk_version: 1.25.0
app_file: app.py
pinned: false
 -->
# Neuro Health Care Chat Bot 🤖


## Make sure you have git-lfs installed [Git LFS](https://git-lfs.com) ✅
# 🧑🏻‍💻Steps to download the Code

**📌 NOTE-1: If the Llama 2 Model is not donwloaded then the code will not work properly.** 

**📌 NOTE-2: If the HuggingFaces API is not in ```.env``` file then generate your own API key from HugginFaces and use it.**

---

Step:0
- Copy and Paste the below command in terminal.
- This command will help to download the code to your local machine.
```shell
git clone https://huggingface.co/spaces/AAYUSH27/Neuro
```
- The file is of approx. 5GB
- If you want to clone without large files (Llama 2 Model).
```shell
git clone https://huggingface.co/spaces/AAYUSH27/Neuro
GIT_LFS_SKIP_SMUDGE=1
```

Step:1 
- Copy and Paste the below command in terminal.
- This command helps to go into the project directory.
```shell
cd Neuro
```

Step:2
-  Copy and Paste the below command in terminal.
- This commmand helps to install all the libraries in one take from ```requirements.txt```.
```shell
pip3 install -r requirements.txt
```

Step:3
- Copy and Paste the below command in terminal.
- This command helps to run the code into local host via ```streamlit```.
```shell
streamlit run -app.py
```