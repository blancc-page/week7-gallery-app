# Gallery App

> A web app that displays picturesand gives users the ability to view and copy an image url link. 

## :hammer: Built With

- HTML, CSS, Python
- Django

## :link: Link to web app(Deployment Link):

https://gallery-app-ip.herokuapp.com/

### :computer: Setup
To get a local copy up and running follow these simple example steps.
  
##### Cloning the repository:  
 ```bash 
git clone https://github.com/blancc-page/week7-gallery-app.git
```
##### Navigate into the folder and install requirements  
 ```bash 
cd week7-gallery-app 
```
##### Install and activate Virtual  
 ```bash 
python3 -m venv virtual - source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations gallery
 ``` 
 Now Migrate  
 ```bash 
python manage.py migrate 
```
##### Run the application  
 ```bash 
python manage.py runserver 
``` 
##### Testing the application  
 ```bash 
python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  

## Behaviour Driven Development

> A user should be able to:

- View different photos.
- Click on a single photo to expand it and also view the details of the photo.
- Search for different categories of photos. (ie. Sports, Books)
- Copy a link to the photo to share with my friends.
- View photos based on the location they were taken.
  

## :bug: Known Bugs
Deployed site has no known bugs.

## :trollface: Authors

👤 **Moses Muta**

- GitHub: [@githubhandle](https://github.com/blancc-page)
- LinkedIn: [LinkedIn](<linkedIn link>)


## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## :muscle: Show your support

    Please give a⭐️if you love this project.

## 📝 License

This project is [MIT](./MIT.md) licensed.
