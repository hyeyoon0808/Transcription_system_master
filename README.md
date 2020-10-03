<h1 align="center"> W.A.M.D.L System </h1> 

<div align="center"><b>W</b>estern <b>A</b>ustralian <b>M</b>ilitary <b>D</b>igital <b>L</b>ibrary </div>

<div align="center">
  <b>Clients : </b>Western Australian Genealogical Society and                  Army Museum of Western Australia
</div>
<div align="center">
  <b>Team : </b>Manuscript
</div>
<div align="center">
<img src="https://user-images.githubusercontent.com/62449446/95002145-d998aa80-060b-11eb-8f1a-acf215aa9e08.png" width="600px"></img>
</div>

## Table of Contents

- [Introduction](#introduction)
- [Build Process](#build-process)
- [Features](#features)
- [Contributors](#contributors)



## Introduction

The W.A.M.D.L system uploads images from World War I and World War II and transcribe them into a digital format. These images were provided to us from two main museums in Australia which are Western Australian Genealogical Society (WAGS) and Army Museum of Western Australia (AMWA). 

**Available for both Desktop and Mobile.**



## Build Process

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

A few of the things you can do with W.A.M.D.L system:

* Login to the system.
* Admin page.
* Manage users in admin page.
* Image upload and handwritten content within the uploaded image is recognized and converted as text onto a text file.
* Option to edit the transcribed text.
* "Collections" page for display results after transcription.
* Hyperlinks to other museum collections in Western Australia.
* Translation into other languages.



## Contributors

Hyeyoon Cho, Harshad Suresh, Ulysses Rodrigues, Jolene Mathews, Areesha Faisal, Qurat Ul Ain, Fayaz Faruk



