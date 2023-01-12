
# Project Description
This project is a prototype for an infusion pump device controlled using a mobile application which displays the ICU monitor vital signals; in our project's case, heart rate.
When the heart rate is outside of the normal range the infusion pump changes the speed of infusion of the drug.

## Components  
1. Stepper motor (from recycled CD ROM [learn more](https://www.youtube.com/watch?v=xJxB2O2FsAo))
2. Arduino Uno board
3. Heart Rate sensor ([get it here](https://ram-e-shop.com/product/kit-pulse-rate/))
4. H-bridge (L298N module) ([get it here](https://ram-e-shop.com/product/kit-l298-red/)) 
5. Arduino Bluetooth Module ([get it here](https://ram-e-shop.com/product/kit-bluetooth-hc05/))
6. Medical Syringe

# Demo
https://user-images.githubusercontent.com/89668727/210170470-487194ef-cf14-48da-ba94-601b862ab763.mp4

# How to Use
The sensor is placed on the patient's hand to measure their heart rate. 

# Limitations
- Heart rate sensor is not highly accurate and has high risk of losing skin-contact
- Stepper motor might not be strong enough for viscous infusion drugs
