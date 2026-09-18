# CarpoolBoard

CarpoolBoard is a carpool mobile app that allows drivers to offer rides and riders to request rides. The goal of the app is to make it easier for students to find and share available rides.

## Project Overview

CarpoolBoard was created using React Native and Expo. Drivers can create an available ride, and riders can add themselves to a waiting list. Drivers and riders can then be matched through the app.

Prototype 2 expands the original CarpoolBoard prototype with a redesigned interface, more ride information, and a more complete rider matching process.

## Prototype 2 Improvements

For Prototype 2, I made several improvements to the original app:

- Redesigned the interface to give CarpoolBoard a more modern mobile app appearance.
- Added destination and departure time information when offering a ride.
- Added a rider matching system.
- Matching a rider decreases the driver's available seats.
- A matched rider is removed from the Riders Waiting list.
- The Riders Waiting count updates automatically.
- Added a confirmation screen after a successful match.
- The confirmation shows the rider, driver, destination, and departure time.

## Features

### Offer a Ride
A driver can enter:
- Driver name
- Destination
- Departure time
- Number of available seats

The ride is then displayed under Available Rides.

### Request a Ride
A rider can enter their name to join the Looking for a Ride list.

### Match a Rider
An available driver can be matched with someone from the waiting rider list. When a match happens:
- The driver's available seats decrease by one.
- The rider is removed from the waiting list.
- The Riders Waiting count decreases.
- A confirmation is displayed for the completed match.

## Program States and Transitions

CarpoolBoard uses state to update the interface based on user interactions.

### Available Rides State
When a driver offers a ride, their information is added to the available rides. The interface updates to display the new ride.

### Riders Waiting State
When someone requests a ride, they are added to the waiting rider list. When they are matched, they are removed from the list.

### Available Seats State
Each ride keeps track of its available seats. Matching a rider decreases the seat count by one. When there are no seats remaining, the ride is shown as full.

### Rider Matching State
Selecting Match Rider opens the rider selection interface. The user can select one of the waiting riders or cancel the matching process.

### Match Confirmation State
After a rider is successfully matched, the app displays a confirmation showing the rider, driver, destination, and departure time. Pressing Done returns the user to the main CarpoolBoard screen.

## Technologies Used

- React Native
- Expo
- JavaScript
- Git
- GitHub
- Claude Code for AI-assisted development

## How to Run
Scan the QR Code or click the link to the expo server.
https://expo.dev/preview/update?message=Prototype+2+user+testing&updateRuntimeVersion=1.0.0&createdAt=2026-09-17T18%3A10%3A10.300Z&slug=exp&projectId=0e5d81b8-c9ef-4e3a-873f-83c78eb6d72c&group=ba32bed6-98fc-434a-b017-b1bd5cf6d1b6

<img width="283" height="288" alt="image" src="https://github.com/user-attachments/assets/ff361fb9-30a1-4e66-b154-b954118be950" />



For Android Users scan this QR Code or click the link for instructions.

<img width="508" height="582" alt="image" src="https://github.com/user-attachments/assets/3cd49953-9017-4202-9b6a-930e79d145b4" />

https://expo.dev/accounts/smu-c3-mobile-fall-26/projects/CarpoolBoard/builds/5eb1e4b5-7500-4db3-b104-6fb7905489c5




