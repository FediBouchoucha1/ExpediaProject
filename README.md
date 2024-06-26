# Expedia.com Simulation

This project is a simple implementation of an Expedia-like booking system developed in C++ with an emphasis on Object-Oriented Programming (OOP) and polymorphism concepts.

## Project Overview

### Itineraries
- Users can manage several itineraries, with each itinerary potentially consisting of:
  - **Flights:** Minimum of 0, example includes 4 flights.
  - **Hotels:** Minimum of 0, example includes 2 hotels.
  - **Cars:** Minimum of 0, example includes 2 cars.
- Each itinerary item, such as a flight or hotel booking, includes:
  - **Cost:** Individual cost for each item.
  - **Details:** For flights, this includes the user's request and selected flight details. For hotels, it includes the total nights and price per night.

### Calculation
- **Itinerary Cost:** The total cost is calculated as the sum of all items within the itinerary.

## Simplifications
- **Data Handling:** The project uses dummy data for simplicity.
- **User Types:** There are two types of users: Admin and Customer. The project primarily focuses on the customer's perspective.
- **API Calls:** Local APIs are simulated to manage the functionalities related to flights and hotels.

## Future Plans
- To enhance the system further by integrating real-world APIs for a more dynamic and responsive user experience.

