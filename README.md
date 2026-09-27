A React and JSON Server web application for veterinarians, pet owners and visitors, providing complete pet records, veterinary appointment management, pet identity verification, medical history updates and lost-and-found reports.

Υου can watch the website in the  video nn university's official Youtube channel : https://youtu.be/fcQR_kGM0_Y?si=zjoA_h_6fOcEr7Yo

Developed using React for the frontend and React Router for navigation, JSON Server as a mock backend through REST API requests and storing data in a db.json file.

### Pet Owners
- Manage pet profiles, health passports, medical history and microchip information
- Report lost or found pets and review previous reports
- Search for veterinarians by location, availability, specialty, education and experience
- Book and manage veterinary appointments
- Receive appointment status updates
- Rate and review veterinarians after completed visits

---

### Veterinarians
- Create and manage a professional profile
- Identify and register pets
- Access and update complete pet medical and life history
- Record vaccinations, surgeries, neutering and other medical procedures
- Record events such as loss, adoption, fostering and ownership transfer
- Set availability and manage appointment requests
- View ratings and reviews from pet owners

---

### Guests / Citizens
- Browse public lost-pet listings
- View information about reported lost animals
- Submit found-pet reports without creating an account

---

## Appointment Management
Pet owners can request appointments, while veterinarians can confirm or reject them. Appointments can be Pending, Confirmed, or Cancelled, with status updates visible to both users.

---

## Pet Records
Each pet has a centralized digital record containing identification details, microchip information, medical history, procedures, vaccinations and important life events.

---


## How to Run
Needs:
- Node.js
- npm

### Installation
```bash
git clone <repository-url>
cd <folder>
npm install
```

Start the mock backend:
```bash
npx json-server --watch db.json --port 3001
```

In a second terminal, start the React application:

```bash
npm start
```

The React application runs on port `3000` and JSON Server runs on port `3001`.
---

## Academic Context

Developed for the Human-Computer Interaction course at the Department of Informatics & Telecommunications, National and Kapodistrian University of Athens.

The project was completed in three phases:

- 1st part — Requirements Analysis of https://pet.gov.gr/ & User Personas
- 2nd part — Storyboard / Wireframes 
- 3rd — Full frontend implementation 

This repository is the final implementation developed during 3th part.

## Technologies
- React
- JavaScript
- React Router
- JSON Server
- REST APIs
- HTML
- CSS

## What I Practiced

- Building a multi-role web application 
- Implementing navigation with React Router
- Creating reusable React components
- Communicating with a REST API
- Working with JSON Server as a mock backend
- Managing pet, user, report and appointment data
- Implementing search and filtering 
- Handling forms, validation and input
- Managing appointment and status changes
