# Galactic Shipping Company – Interstellar Logistics Simulation

## Overview

This is a university semester project simulating an interstellar logistics company using a variety of modeling techniques including **OntoUML**, **UML**, **BPMN**, **DEMO**, and **Object-Role Modeling (ORM/OCD)**. The project focuses on modeling and analyzing mission planning, cargo transportation, and fleet maintenance in a galaxy-spanning shipping company.

## Domain Description

**Galactic Shipping Company** is an advanced logistics enterprise specializing in the transport of various types of cargo across planets and space stations throughout the galaxy. The company ensures safe, efficient, and timely delivery of shipments – from basic commodities like food and medicine to valuable or hazardous materials.

Each ship in the fleet has its own specifications and constraints (e.g., cargo capacity, fuel consumption, hyperdrive compatibility), making careful mission planning essential.

### Fleet and Personnel

The fleet consists of multiple ship classes:
- **Courier Ships**: Fast and agile, suitable for time-sensitive deliveries.
- **High-Capacity Freight Ships**: Slower but with large cargo holds and designed for long-haul missions.

Company employees include:
- **Captains**,  
- **Operators**,  
- **Technicians**,  
- and other **crew members** responsible for mission success and ship maintenance.

### Mission Planning & Transport Process

1. **Order Analysis**: Evaluates shipment type (standard, valuable, or hazardous), volume, and delivery deadline.
2. **Ship Assignment**: Selects the most suitable ship based on cargo needs, capacity, and route.
3. **Route Planning**: Considers fuel needs, potential threats (e.g., pirates), and rest stops.
4. **Monitoring**: Tracks cargo status and ship performance during missions.
5. **Delivery**: Includes unloading and post-mission handling depending on the ship and cargo type.

Operators use historical data and real-time updates to react to unexpected events and ensure operational sustainability.

### Domain Constraints (OCL)

The system implements several domain-specific constraints using **Object Constraint Language (OCL)**:

1. **Ship Capacity**:  
   Total cargo weight and volume must not exceed ship limits.
2. **Delivery Deadlines**:  
   Time-sensitive shipments must be delivered within their allowed timeframe.
3. **Fuel Consumption**:  
   Ships must have enough fuel for the planned route.
4. **Hyperdrive Restrictions**:  
   Unstable cargo cannot be transported using hyperdrives.
5. **Crew Rest Requirements**:  
   Crew members must rest between missions based on mandatory rest periods.
6. **Mission Assignment**:  
   A ship can only participate in one active mission at a time.
7. **Distinct Mission Locations**:  
   The mission's origin and destination must be different.

## Technologies and Modeling Tools

- **OntoUML** – for conceptual domain modeling
- **UML (Class, Activity, Sequence diagrams)** – for system and process structure
- **BPMN** – for business process modeling
- **DEMO methodology** – for enterprise modeling
- **OCD/ORM** – for object-role interactions
- **OCL (Object Constraint Language)** – for domain logic enforcement

## Authors

This project was developed as part of a semester course in information systems modeling.

## License

This project is intended for educational and academic use only.
