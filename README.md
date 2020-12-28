# mkpreview
Simple bash script for creating thumbnail video previews

![screenshot](https://github.com/trifonovkv/mkpreview/blob/main/screenshot.png)  

## Installation
Install dependecies:  
[install ffmpeg to Fedora](https://computingforgeeks.com/how-to-install-ffmpeg-on-fedora/)   
Debian, Ubuntu:  
`sudo apt-get install imagemagick`  
RedHat, Fedora:  
`sudo dnf install ImageMagick`  

`wget https://raw.githubusercontent.com/trifonovkv/mkpreview/main/mkpreview`   
`chmod +x ./mkpreview`

## Usage
`mkpreview [OPTIONS] /path/to/videofile`

   `-n` NUMBER        how many thumbnails to create  
   `-s` WIDTHxHEIGHT  size of thumbnails  
   `-h`               show help   

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
