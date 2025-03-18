# Theft-Detection

## Project highlights
---
- A new novel approach in human action recognition (HAR) that combine the advantage of deep neural network **3D-CNN** in learning complex features and patterns, and lightweight models architecture suitable for real-time interference and edge devices deployment.
- SL models are built using a unique dataset designed explicitly for convenience stores and supermarkets containing row videos of theft events performed by actors
- model designed for use in real-time environments using surveillance
  cameras and deliver real-time alerts on theft incidents occurring in the store.
 
Architecture advantages:
- Extremely low inference time suitable for real-time system deployment 
- Run efficiently on Edge devices memory savings, due to the low number of the network parameters







## Introduction 
---

### Computer vision and Human action recognition quick overview
- Artificial intelligence and recent innovations in deep learning (DL) and neural networks took great leaps in recent years. One of the most effective types of AI is computer vision. Computer vision is the field of computer science that focuses on replicating parts of the complexity of the human vision and enabling computers to identify and process objects in images in a similar way has humans accomplish.
One of the most challenging tasks in computer vision is Human Action Recognition (HAR) which aims to understand human behavior and assign a label to each action.

- A common approach in the HAR domain, is to treat video frames as images and apply **2D-CNN** (Conventional Neural Network) to recognize the action in every single frame from the video stream.One of the main deficiencies of this approach is that each video frame forms only a tiny part of the video's story, such an approach will be using incomplete information and could, therefore, easily wrongly classified, especially if there are fine-grind distinctions. In the HAR domain a single frame analysis may interoperate as different activity from the realty, when there are different shapes (e.g., person is doing pushups, or he fall down). This is termed interclass similarity, which is a common phenomenon in HAR.

### Problem statement
Real-time analysis of each camera has become an exhaustive task due to human limitations. The primary human limitation is the visual focus of attention. The human gaze can only concentrate on one specific point at once. Although there are large screens and high-resolution cameras, a person can only regard a small segment of the image at a time. Thieves are well aware that watching all the video footage is too demanding for "SMBs" such as retailers\ grocery\convenience stores, which makes the technology lose its role as a deterrent
 
#### Project goals:
provides a comprehensive solution for monitoring and detecting unusual events in real-time without the need for human supervision, the system will alert on
a variety of scenarios. **The following example describes the chain of events in the case of a
shoplifting incident, where the customer steals an alcoholic beverage and hides it in a bag**.

![sl_proecess_1](https://user-images.githubusercontent.com/34807427/171988455-913c721b-92ae-4f61-91fe-32eee77b5989.png)


When one of these actions will detected by our AI model, we will provide the store owner with an
immediate alert.

The system monitors basic customer activities in the store, activities that we will define as pre-
crime such as:
- Taking an item off the shelf.
- Returning an item to the shelf.
- Examining an item.
These activities are routine customer procedures in the store.


And activities that we will define as crime lapse in which our system will monitor and report in real-
time on a case of theft in the store.
crime lapse activities such as:
- Concealing an item in clothes.
- Concealing an item in a bag.

### MODEL PLOT

 
 <img src="https://user-images.githubusercontent.com/34807427/171699014-2f4c0d51-662f-42fc-b2b9-4c8b9e2b1d43.png" width="750" height="600">





## Input-Output
![SL_event_record_1__ (1)](https://user-images.githubusercontent.com/34807427/172144654-730d19a4-8f04-4a7c-940a-dacf8586973c.gif)
![SL_event_record_1__](https://user-images.githubusercontent.com/34807427/172144668-d7d6d467-000c-48de-9d80-2ea3e43d342f.gif)
![SL_event_record_4__](https://user-images.githubusercontent.com/34807427/172144677-34f3038a-e4d8-4006-9e1b-ca7f3cd38d33.gif)
![SL_event_record_5__](https://user-images.githubusercontent.com/34807427/172144680-7c02115b-b0c9-4607-b3e8-702618adccd1.gif)
![SL_event_record_6__ (1)](https://user-images.githubusercontent.com/34807427/172144682-88f7eda0-c41b-4fb4-87fe-e324d82591ae.gif)
![SL_event_record_6__ (2)](https://user-images.githubusercontent.com/34807427/172144686-75d2ff53-f614-4388-8b97-a1a33a533f65.gif)
![SL_event_record_6__](https://user-images.githubusercontent.com/34807427/172144693-72bc66b2-37b3-4624-8537-b06781a96002.gif)
![SL_event_record_7__ (1)](https://user-images.githubusercontent.com/34807427/172144698-6b3b57d7-6c1d-490b-bc54-520a701ce2e0.gif)
![SL_event_record_7__](https://user-images.githubusercontent.com/34807427/172144706-6eb4acf5-f408-424f-8b84-e471b41aa3d1.gif)
![SL_THEFT_3](https://user-images.githubusercontent.com/34807427/172144711-3eacccc9-cd0a-4935-a0d8-be5db8e9886f.gif)
![SL_event_record_4__ (1)](https://user-images.githubusercontent.com/34807427/172144715-94d3b4af-5343-4e2c-bb8c-4a23562e0802.gif)



https://user-images.githubusercontent.com/34807427/171149238-3cabeffb-1087-4748-b7ca-1927cd4cf6f8.mp4

https://user-images.githubusercontent.com/34807427/171149909-50489465-6fb0-4e61-ad56-927233318259.mp4



