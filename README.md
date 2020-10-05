<h1 align="center"> W.A.M.D.L System </h1> 

<div align="center"><b>W</b>estern <b>A</b>ustralian <b>M</b>ilitary <b>D</b>igital <b>L</b>ibrary </div>
<div align="center">
  <b>Clients : </b>Western Australian Genealogical Society and                  Army Museum of Western Australia
</div>
<div align="center">
  <b>Team : </b>Manuscript
</div>
<div align="center">Python(Django), TensorFlow, Linux, XAMPP, Bootstrap, MariaDB</div>
<div align="center">
<img src="https://user-images.githubusercontent.com/62449446/95002145-d998aa80-060b-11eb-8f1a-acf215aa9e08.png" width="600px"></img>
</div>

## Table of Contents

- [Introduction](#introduction)
- [Build Process](#build-process)
- [Features](#features)
- [Guide](#guide)
- [Contributors](#contributors)



## Introduction
![ezgif com-gif-maker (3)](https://user-images.githubusercontent.com/62449446/95002820-406d9200-0613-11eb-96a6-ca0c8ed51f4c.gif)

The W.A.M.D.L system uploads images from World War I and World War II and transcribe them into a digital format. These images were provided to us from two main museums in Australia which are Western Australian Genealogical Society (WAGS) and Army Museum of Western Australia (AMWA). 

**Available for both Desktop and Mobile.**




## Build Process
![ezgif com-gif-maker (4)](https://user-images.githubusercontent.com/62449446/95044491-7c3f4f00-071a-11eb-9674-e09b3feca5de.gif)
- Clone or download the repo
- Install `python 3.6.5`
- `pip3 install -r requirements.txt` to install packages required to run
- Move into `cd djangoproject` folder
- `source djangoenv/bin/activate` to activate env
- Setting up authentication of Google Cloud and get an an api key
- `export GOOGLE_APPLICATION_CREDENTIALS="[PATH of api key]"` to use Google Cloud Storage API
- `python3 manage.py runserver` to start the server

**Api Keys**: To run the client library, you must first set up authentication by creating a service account and setting an environment variable. [Guide](https://cloud.google.com/storage/docs/reference/libraries#client-libraries-install-python)

**Admin Account**: Username: manuscript / password: transcript123




## Features
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/62449446/95002376-2da48e80-060e-11eb-96c3-3b10c3724ee9.gif)

A few of the things you can do with W.A.M.D.L system:

* Login to the system.
* Admin page.
* Manage users in admin page.
* Image upload and handwritten content within the uploaded image is recognized and converted as text onto a text file.
* Option to edit the transcribed text.
* "Collections" page for display results after transcription.
* Hyperlinks to other museum collections in Western Australia.
* Translation into other languages.



## Guide
**Volunteer page** 

  1. Volunteer will have to sign in, in order to transcribe documents.

  ![signin](https://user-images.githubusercontent.com/62449446/95002523-06e75780-0610-11eb-89e3-9ffd735d0561.png)

  2. Collection page for Volunteers (as well as Admin) to visit and upload new transcription.

  ![Picture1](https://user-images.githubusercontent.com/62449446/95002608-eec40800-0610-11eb-9cb4-c65f3d6c30e4.png)

  3. Avaliable to view the transcribed documents.  

  ![Picture2](https://user-images.githubusercontent.com/62449446/95002600-d18f3980-0610-11eb-9b33-839339584b4b.png)

  4. Volunteer (as well as Admin) clicks on the hyperlink of “choose file” on the collection page to upload new transcription.

  ![Picture4](https://user-images.githubusercontent.com/62449446/95002576-92f97f00-0610-11eb-85f9-fde70e231768.png)

  5. Volunteer has the option to edit the transcribed document and save it to the database.

  ![Picture6](https://user-images.githubusercontent.com/62449446/95002583-a4db2200-0610-11eb-89c0-cd799bc43ef4.png)


**Admin page** 

  1. A personal sign in is available in order to manage the website.

  ![admin1](https://user-images.githubusercontent.com/62449446/95002650-68f48c80-0611-11eb-86d2-4c04ca4a2991.png)

  2. After the admin signs in, he/she is redirected to the page shown in the screen dump below.

  ![admin2](https://user-images.githubusercontent.com/62449446/95002653-6b56e680-0611-11eb-9f0f-e3172e0c17ed.png)

  3. Admin clicks the “users” tab to manage, add and delete all the users. 

  ![admin3](https://user-images.githubusercontent.com/62449446/95002655-6e51d700-0611-11eb-865c-4c3ca9d9449f.png)

  4. By clicking on a single user tab, a window pops up where the admin can manage the user’s personal information and can grant permissions.

  ![admin4](https://user-images.githubusercontent.com/62449446/95002657-701b9a80-0611-11eb-9791-e054f13d35f4.png)


## Contributors
Hyeyoon Cho, Harshad Suresh, Ulysses Rodrigues, Jolene Mathews, Areesha Faisal, Qurat Ul Ain, Fayaz Faruk



