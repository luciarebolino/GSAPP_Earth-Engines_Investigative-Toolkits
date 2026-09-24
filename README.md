# ⟣ Earth Engines - Investigative Toolkits 

<img width="800" height="450" alt="bacgroundgithub-ezgif com-video-to-gif-converter (2)" src="https://github.com/user-attachments/assets/47425b8f-265d-46a5-979a-d2637a8af50b" />

Investigative toolkits (IT) are experiments with remote sensing as both method and medium, using Google Earth Engine to explore the atmospheric and spectral layers of the Earth. Through coding and cloud-based data processing, we reframe satellite imagery as temporal and moving surfaces to interpret and translate environmental change.

## CLOUD COMPUTING 

<img width="1459" alt="Screenshot 2025-02-18 at 2 01 30 AM" src="https://github.com/user-attachments/assets/1736e108-9530-48f6-ae5f-32a578e28f48" />

[Google Earth Engine requires all users to sign-up for an account](https://code.earthengine.google.com/register). This account is linked with Google Cloud and users must create a Google Cloud Project to use the service. 
- On the Product Registration Page, select Register a Noncommercial or Commercial Cloud project.
- Next, you need to choose How do you want to use Earth Engine?. Choose the Unpaid usage, click Next. Since we are in Academia provider, we have chosen Unpaid usage → Research & Academia.
- In the next dialog, choose Create a new Google Cloud Project. Select No organization for Organization and enter a Project-ID. This id needs to be unique. A standard practice is to use the project-ID in the form of ee-<yourusername>. Click CONTINUE TO SUMMARY. If you have never used Google Cloud before, an error message will be displayed with a note You must accept the Cloud Terms of Service before a Cloud Project can be created.
- Choose your Country and review the Google Cloud Platform Terms of Service and the terms of service of any applicable services and APIs. After reviewing, click AGREE AND CONTINUE.
- You will be presented with a summary in the Confirm your Cloud project information dialog. Review and click CONFIRM.
- The project will be registered and you will be redirected to the Code Editor. If you are not redirected automatically, visit the Earth Engine Code Editor.


Database links:
<br>
[Earth Engine Data Catalog](https://developers.google.com/earth-engine/datasets/catalog/landsat) <br>
[GEE Community Catalogue](https://gee-community-catalog.org/)<br>
[Spectral Indexes](https://awesome-ee-spectral-indices.readthedocs.io/en/latest/index.html)





## CODE SNIPPETS ❊

The following code snippets are designed as **interactive examples** to be used during the semester. 

### W3 - Workshop 1 - 23 September 2026 - WATER

** A (very) quick intro to Remote Sensing **
- **SATELLITES** – Understanding how satellite images are composed of discrete units of information (pixels, resolution, orbits)
. [EE_GSAPP_Satellite](https://code.earthengine.google.co.in/9c4ceffd1f4d8af839f9ffa060b2a9ea?hideCode=true)
- **TIME MACHINE** – Exploring how satellites capture imagery at different time intervals (satellite missions, technological gaps)
. [EE_GSAPP_Time Machine](https://code.earthengine.google.co.in/446facbc6f11567f6b9ae001a6bd93c5?hideCode=true)
- **SPECTRUM** – When light strikes an object, it can be absorbed, transmitted, or reflected. How this interaction happens and how it depends on the material properties of the surface.

<p align="center">
<img width="478" height="475" alt="Screenshot 2025-10-22 at 9 56 22 PM" src="https://github.com/user-attachments/assets/a832263c-6eb1-4eb9-b8c9-baf2ca848618" />
</p>

  
. [EE_GSAPP_Spectrum](https://code.earthengine.google.co.in/d5e4b8c9a7143a895805d58d9e922529?hideCode=true)
- **WEATHER** – 
. [EE_GSAPP_Weather](https://code.earthengine.google.co.in/ff83f9b12c304f64d9633e53cb0276f0?hideCode=true)


<img width="1841" height="1149" alt="Screenshot 2026-09-24 at 12 55 58 PM" src="https://github.com/user-attachments/assets/fe3b5cde-4808-4436-af54-d388c0c4f361" />


- **WATER 1** – Water Classification


<img width="1841" height="1149" alt="Screenshot 2026-09-24 at 11 05 45 AM" src="https://github.com/user-attachments/assets/a1fbe7c4-11f1-48e2-a33a-ff7d0ac1652c" />



. [EE_W1](https://code.earthengine.google.co.in/7d2f3980686cac2f7b5429372a056f0d?hideCode=true)

- **WATER 2** – PCA (Principal Component Analysis) - Change Detection

<img width="1841" height="1149" alt="Screenshot 2026-09-24 at 11 10 36 AM" src="https://github.com/user-attachments/assets/20a23b00-e674-481d-b038-3fc9cbbd3593" />


. [EE_W2](https://code.earthengine.google.co.in/9cb856e8f2ddef607a9a6d42f0e143e5?hideCode=true)

- **WATER 3** – PCA - Spectral Bands


<img width="1841" height="1149" alt="Screenshot 2026-09-24 at 11 13 18 AM" src="https://github.com/user-attachments/assets/f2c21f5b-fcb5-434d-b996-fc7989c04e7d" />



. [EE_W3](https://code.earthengine.google.co.in/d02532ef3b55c4636e6ec5fd78f30bab?hideCode=true)

- **WATER 4** – Water Pollution

<img width="1841" height="1149" alt="Screenshot 2026-09-24 at 11 15 02 AM" src="https://github.com/user-attachments/assets/f67bc8ee-bd7e-45ae-af3a-65041ebd69ce" />




. [EE_W4](https://code.earthengine.google.co.in/3f0c8b6425d6c08fa85b46f0f0f5ffc3?hideCode=true)




