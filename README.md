<div id="top"></div>

<br />
<div align="center">

  <h3 align="center">Image Scraper without Scraping Library !</h3>

</div>


<!-- ABOUT THE PROJECT -->

## About The Project

This repository is just a handbook to scrape or download images from a text file containing list of links. You do not need any python or scraping library to do that. All you need just a txt file with links and a terminal command (curl , wget etc).


### Built With

* GNU wget
* A text file containing links

<!-- GETTING STARTED -->
## Getting Started

First create a text file (.txt) which contains the links of the images to be downloaded. All the links must be seperated by a newline.

### Prerequisites

You need to have installed wget or curl in your terminal to execute the terminal command. By default, Ubuntu or linux-based operating systems have wget.

### Step 1

Make a folder and inside that folder, create a text file containing links of images to download. In this repository, check the images.txt file for example.

* Suppose, I am creating a folder named 'Image-Scraper'
  ```sh
  mkdir Image-Scraper
  ```

* Go inside that folder
  ```sh
  cd Image-Scraper
  ```

* Make a text file suppose called 'images.txt'
  ```sh
  touch images.txt
  ```
<br>
  
Now fill up the file with links. Check the images.txt in this repository for example.
<br>
<br>
<br>

### Step 2

* Now write on the terminal : wget -i <textfile_name>. Suppose 'images.txt' will contain all the links. Then,
  ```sh
  wget -i images.txt
  ```
### Step 3
All the images will be download in current folder one by one. Yay !


## Contact

Akif Islam - [Facebook](https://facebook.com/AkifIslamOfficial) - iamakifislam@gmail.com



