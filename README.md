# Project Photon - The Google photos clone

A microservices-based photo gallery application designed for image upload with usage and storage monitoring. Developed using the MERN stack (MongoDB, Express.js, React.js, Node.js), the application is structured as separate microservices to enhance scalability and maintainability.

## Features

- **User Account Management:** Users can simply register and start using our application.
- **Image Upload:** Users can easily upload images using the application.
- **Image Delete:** Users can delete individual images.
- **Bulk Delete:** Users can delete their images in bulk.
- **Logging:** Tracks the activity of users.
- **Usage Monitoring:** The application provides metrics for monitoring usage patterns.
- **Storage Monitoring:** Tracks and displays storage usage for the uploaded images.

## Architecture

The microservices architecture promotes a modular and scalable design:

- **Client (React.js):** Provides the user interface.
- **Other Microservices (Node.js):** Includes services for user authentication, user activity monitoring, and storage monitoring.

## Architectural Diagram

![image](https://github.com/tayyibgondal/Project_Photon/assets/99114574/b2e359e3-b762-4604-9338-88d6054b107c)


## Load testing cases
Tests invoked on frontend microservice
### 100 users, 2 sec ramp-up period, 10 iterations
Throughput increased without any failure
![image](https://github.com/tayyibgondal/Project_Photon/assets/58441901/5ae25c77-6df6-4902-a460-038204fc5531)

### 500 users, 2 sec ramp-up period, 50 iterations
25k requests were successfully served. Throughput 21.7/s, Spike was measured on gcp
![image](https://github.com/tayyibgondal/Project_Photon/assets/58441901/68b80152-c1b5-45d8-a5f2-5fecf7131f1b)


### 500 users, 2 sec ramp-up period, 100 iterations
~50k requests were 100% served. Throughput 29.3/s
![image](https://github.com/tayyibgondal/Project_Photon/assets/58441901/5f05145e-f6e3-4633-81e7-69e4ea289d3c)

## 📫 Get in Touch
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=fff)](https://www.linkedin.com/in/muhammad-bin-usman/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=000)](https://huggingface.co/Muhammad2003)
[![Medium](https://img.shields.io/badge/Medium-%23000000.svg?logo=medium&logoColor=white)](https://medium.com/@muhammadbinusman03)
[![X](https://img.shields.io/badge/X-%23000000.svg?logo=X&logoColor=white)](https://x.com/Muhamma97033716)
[![Substack](https://img.shields.io/badge/Substack-FF6719?logo=substack&logoColor=fff)](https://substack.com/@rethinkai)

