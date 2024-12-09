# LinkedIn_Profile_Scrapper
Made a python script to scrape data from linkedin and export it to a JSON file. Using Selenium and beautiful soup. 
The function returns a python dictionary containing full_name, profile_pic_image, banner_image, linkedin_url, about_section, experience, project, skills. It also save the JSON file in the same directory.
Get the data as per your convineince. POINT TO NOTE: This code might get out dated easily, as the linkedin company frequently makes changes to their html names and classes along with its structure, but the general principle of hardcoded scrapping remains the same.

# To run
1 . First install all the requirements:
```
pip install -r requirements.txt
```
2 . Pass the url of the profile you want to scrape:
```
python scrapper.py "https://www.linkedin.com/in/aryan-kanyawar-1a5482290/"
```
3 . A JSON file would be created with the fetched data within the same directory

4 . create a .env file and put, make a dummy account on linkedin, DO NOT USE your own credentials, your account might get banned or you might face legal consequences as per the terms and conditions.
```
EMAIL="YOUR_EMAIL"
PASSWORD="YOUR_PASSWORD"
```

5 . Refer to Test.py on how to call the function and view scrapper.py to understand the scrapping code

6 . ipynb files were used in order to develop and test logic. 
