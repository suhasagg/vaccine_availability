
#  Data Sheets for vaccine availability are available in this repository

Please download the CSVs available in the repository.
This data is in lieu of Heal the World - Campaign - according to Om Shanti Principles. 

![alt_text](https://i.ibb.co/0BZzw1B/Photo-from-Suhas-1.jpg)

![alt_text](https://i.ibb.co/zJTn9dC/Photo-from-Suhas.jpg)


😊😊😊

![alt text](https://lh3.googleusercontent.com/proxy/sS408uehbFFrftV-2yJJqqJZjlHt7X32w-HwNI6-mVa5lQwGQveqSckK5idrO2qR64wU9lxW98q-N-92cutq17TzhvtMErooyBNzc4rXRugzHmM7-HDsweteG2iGGQxn=w1200-h630-p-k-no-nu)


# Possible Preventions 



1)Sprays


https://www.clickoncare.com/viro-shield-mouth-spray-30ml/questions
https://viraleze.co/


2)Siver nanotechnology on microbes !!

https://www.miracle.care/


3)Capsules (Herbal)

https://www.amazon.in/gp/product/B08NPJXBNY/ref=ppx_yo_dt_b_asin_title_o08_s00?ie=UTF8&psc=1




# Tutorial

# Vaccine Availability With Python
Get vaccine availability in India

## [Streamlit app](https://share.streamlit.io/bhavsarpratik/vaccine_availability/main)  
![Mail](.github/streamlit.png?raw=true")  

## CRON job for mail
Script runs every 6 hours. You can change this [here](https://github.com/bhavsarpratik/vaccine_availability/blob/main/.github/workflows/cron.yaml#L8)  

Steps
- Fork the code
- Enable [less secure apps](https://myaccount.google.com/lesssecureapps)
- Set up 2-factor authentication, and then generating an app-specific password with these [instructions](https://support.google.com/domains/answer/9437157)
- Add [these](https://github.com/bhavsarpratik/vaccine_availability/blob/main/.github/workflows/cron.yaml#L32) secrets to repo settings. Use the app specific password generated above
- Get district id from [here](https://github.com/bhavsarpratik/vaccine_availability/blob/main/districts.csv)
- Change config in your [code](https://github.com/bhavsarpratik/vaccine_availability/blob/main/availability.py#L119)


## Mail preview  
![Mail](.github/mail.png?raw=true")
