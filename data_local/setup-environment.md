# How to set up Environment

---

- Create an account on Kaggle and sign up for the [March ML Mania](https://www.kaggle.com/competitions/march-machine-learning-mania-2023) competition  
- Make a top level directory and name it `data_local`  
- Save the competition data inside `data_local` using either method
   - download the data manually 
   - pull directly with the [Kaggle Api](https://www.kaggle.com/docs/api)
     - `kaggle competitions download -c march-machine-learning-mania-2023`

---

Note: If your environment does not contain venv run  
`pip3 install venv`


`python3 -m venv venv`   
`source venv/bin/activate`  
`pip install -r requirements.txt`


> Download Data with Kaggle API  
> 1. In your home directory make a file called `.kaggle`
> 2. Go to your Kaggle Account page and generate a new API Key
> 3. Save the `kaggle.json` file in the `~/.kaggle/` folder
> 4. Open your terminal and change directory to `data_local/` of this project 
> 5. Download data by running: `kaggle competitions download -c march-machine-learning-mania-2023`
> 6. Unzip the file you just retrieved with: `unzip march-machine-learning-mania-2023.zip`
> 7. Delete the zip file: `rm march-machine-learning-mania-2023.zip`


