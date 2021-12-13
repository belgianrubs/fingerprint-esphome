# Fingerprint ESPHome
I made a wiring scheme and used some example code for the basic setup of a R307 fingerprint sensor with ESPHome. 

## Components list
* [D1 mini](https://s.click.aliexpress.com/e/_98eTUE)
* [R307 fingerprint sensor](https://s.click.aliexpress.com/e/_AZPqbc)
* or the R503 fingerprint sensor (I've not tested it yet)
* Some wires

## Guide
1) Wire the D1 mini to the fingerprint sensor as shown on the image: ![fingerprint wiring](https://github.com/belgianrubs/fingerprint-esphome/blob/main/fingerprint-wiring.jpg)
2) Make a new ESPHome project and make the .yaml file look like the example code fingerprint-project.yaml.
3) Upload the code to the D1 mini by using a micro USB connected to the PC you're working on or the hardware where your Home Assistant and ESPHome is running on.  
4) You can now learn fingerprints by going into Developer Tools of Home Assistant > Services > if you type ESPHome, an enroll service should pop up. You can give an integer for the finger_id and how many times it needs to be scanned with num_scans.

## If you really like this guide and want to support me:

<a href="https://www.buymeacoffee.com/rubs" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a> 
