# [TicketPros.io](https://ticketpros.io)

## Overview

[TicketPros.io](https://ticketpros.io) is a specialized platform designed to streamline the process of handling debris load tickets. This application was developed in response to the cumbersome process of manually entering information from thousands of tickets every week to generate pay reports. By leveraging Tesseract OCR and PyTesseract, TicketPros.io automates this process, significantly reducing the workload and potential for human error. Built with Django, the application allows users to upload their debris tickets, and then extracts all relevant information from the tickets automatically. The application also includes features to identify errors in the OCR accuracy and generates pay reports based on user input information for each contractor/subcontractor. This repository serves as a showcase of the project and is not open for contributions as it is a private repository.

## Technologies Used

- Django: A high-level Python Web framework that encourages rapid development and clean, pragmatic design.
- Tesseract OCR: An optical character recognition engine for various operating systems.
- PyTesseract: A Python wrapper for Google's Tesseract-OCR Engine.
- Stripe: A technology company that builds economic infrastructure for the internet.
- Bootstrap CSS: A free and open-source CSS framework directed at responsive, mobile-first front-end web development.
- Digital Ocean: A cloud infrastructure provider focused on simplifying web infrastructure for software developers.

## Features

Here are some of the main features of [TicketPros.io](https://ticketpros.io):

1. **User Authentication:** Secure user registration and login functionality.
2. **Debris Ticket Upload:** Users can upload their debris load tickets.
3. **Information Extraction:** The application uses Tesseract OCR and PyTesseract to automatically extract all relevant information from the uploaded tickets.
4. **OCR Accuracy Check:** The application includes features to identify errors in the OCR accuracy.
5. **Pay Report Generation:** The application generates pay reports based on user input information for each contractor/subcontractor. It calculates the pay based on the contractors/subcontractors pay rate and the trucks calculated yardage.
6. **User Dashboard:** Users can view their uploaded tickets, the extracted information, and their generated pay reports.

## Screenshots
# Home Page
![Alt text](scrot.png "Optional title")
# User Dashboard
![Alt text](scrot1.png "Optional title")
![Alt text](scrot2.png "Optional title")
![Alt text](scrot3.png "Optional title")
![Alt text](scrot5.png "Optional title")
# Pay Report Example
![Alt text](pdf.png "Optional title")



