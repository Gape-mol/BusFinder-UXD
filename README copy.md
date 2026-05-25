# BusFinder UXD
Connecting rural Araucanía to reliable transit — one tap at a time

## Index

- [1. Introduction](#1-introduction)
  - [1.1. The Problem](#11-the-problem)
  - [1.2. Our Solution](#12-our-solution)
- [2. Team & Roles](#2-team--roles)
- [3. Strategy](#3-strategy)
  - [3.1. Value Proposition Canvas](#31-value-proposition-canvas)
  - [3.2. UX Personas](#32-ux-personas)
  - [3.3. Benchmarking](#33-benchmarking)
- [4. Scope](#4-scope)
  - [4.1 Customer Journey Map](#41-customer-journey-map)
    - [4.1.1 Decision Stage Interfaces](#411-decision-stage-interfaces)
- [5. Structure](#5-structure)
  - [5.1. Navigation Flow](#51-navigation-flow)
- [6. Skeleton](#6-skeleton)
  - [6.1. Low-Fi Wireframes](#61-low-fi-wireframes)
- [7. Surface](#7-surface)
  - [7.1. Interface Evolution](#71-ui-evolution)
  - [7.2. Results of the Heuristic Evaluation](#72-results-of-the-heuristic-evaluation)
  - [7.3. High Definition Interfaces](#73-high-definition-interfaces)

---

## 1. Introduction

### 1.1. **The Problem**

The Araucanía region faces a critical mobility challenge: thousands of people in rural localities depend exclusively on urban transportation to access essential services—education, healthcare, and employment opportunities—concentrated in major cities.

However, information about routes, schedules, fares, and transportation availability remains **fragmented, decentralized, and often available only in physical format**. This information gap creates **significant uncertainty** that disproportionately affects students and workers in rural areas, limiting their mobility, access to opportunities, and quality of life.

**The result: a rural population disconnected, lacking the information needed to plan their travel effectively.**

---

### 1.2. **Our Solution**

Our proposal consists of designing an intuitive mobile interface that serves as a bridge between bus operators and rural passengers in the Araucanía region. A user-centered solution that transforms the travel experience from the moment a trip is planned to the moment of arrival.
 
The proposal is built around four pillars designed to address our users' core pain points:
 
- **Real-time information hub.** Users access a clear, accessible interface that allows them to check updated schedules, estimated arrival times, and the operational status of each bus—including mechanical breakdowns. This eliminates the uncertainty that currently forces people to wait at bus stops with no assurance whatsoever, enabling them to plan their journey ahead of time, reduce the anxiety of waiting, and track their arrival time in real time.
 
- **Capacity and luggage management.** The platform provides real-time visibility into seat availability and luggage space. This directly addresses the frustration of arriving at a bus stop only to find the bus is full: users can reserve their spot and secure space for their luggage before leaving home, regaining control over their mobility.
 
- **Fare transparency and payment digitization.** The solution incorporates an advance-purchase system that automatically calculates and applies preferential fares—student, senior—without users losing these benefits due to lack of awareness or failure to carry physical documentation. This reduces queues at terminals, decreases cash dependency, and eliminates the friction rural passengers currently face when paying.
 
- **Smart notifications.** The application sends proactive alerts to the user's device regarding delays, route changes, or newly available seats. Rather than discovering a problem upon arrival at the bus stop, the system anticipates it, empowering users to make informed decisions and reorganize their day in time.

---

## 2. Team & Roles

**Angelo Huaiquil** - *Project Manager*

**Gustavo Pérez** - *Analyst*

**Daniela Díaz** - *Designer*

---

## 3. Strategy - First Layer

### 3.1. Value Proposition Canvas

The Value Proposition Canvas defines BusFinder’s fit between the needs of rural and intercity bus users in Araucanía and the services proposed by the platform.

The customer segment focuses on passengers who need to arrive on time to work, school, medical appointments, or other essential activities, while dealing with uncertainty about schedules, fares, luggage space, and bus availability. Their main pains include unreliable or fragmented schedule information, lack of fare transparency, baggage issues, and delays without prior notice.

BusFinder responds to these pains through a set of services and value creators: real-time transit alerts, estimated travel times, visible seat and luggage capacity, transparent pricing with pre-applied discounts, and push notifications for delays or newly available seats. These features aim to reduce uncertainty, improve planning, increase reliability, and make the travel experience more inclusive for rural passengers, students, workers, and seniors.

![Value Proposition Canvas](/Docs/Value%20Proposition%20Canvas-BusFinder.jpg)

***

### 3.2. **UX Personas**  

The UX Personas represent three key user profiles affected by rural and intercity mobility issues in Araucanía. They were created to reflect different levels of digital literacy, travel frequency, and dependency on public transport.

Together, these personas help guide BusFinder’s design decisions by highlighting the need for reliable route information, accessible interfaces, clear fare visibility, real-time alerts, and reduced uncertainty before and during the trip. Their needs directly inform the product’s main features, such as live bus tracking, capacity and luggage visibility, fare transparency, and proactive notifications.

Each persona represents a different mobility scenario: daily commuting, essential healthcare travel, and academic travel between rural towns and urban centers.

---

👥🔹 **Juan Carlos Muñoz (42, Male)**
*Agricultural worker from Freire who depends entirely on intercity buses to commute to Temuco. He relies on outdated printed schedules and word-of-mouth, and faces constant uncertainty about bus times, fares, and luggage capacity.*

👥🔹 **Maria Elena Soto Huenulao (67, Female)** 
*Retired senior living alone in Cunco who travels regularly to Temuco for medical appointments. She struggles with small text and confusing app navigation, and has missed appointments due to unreliable bus information.*  

👥🔹 **Andres Rivera (24, Male)** 
*5th-year Engineering student from Lautaro who wakes at 5:30 AM daily to catch the 6:15 bus. He values efficiency and time optimization but feels physically drained by the daily commute and lack of reliable transit data.*

---


![UX Persona 1](./Docs/UX-Persona-1.jpg)

![UX Persona 2](./Docs/UX-Persona-2.jpg)

![UX Persona 3](./Docs/UX-Persona-3.jpg)


### 3.3. Benchmarking

The benchmark compares **TurBus**, **Moovit**, and **Uber** to identify mobility UX patterns that can inform BusFinder. TurBus provides a direct reference for intercity bus ticket purchase and seat selection; Moovit contributes public transport route planning, live guidance, and service alerts; and Uber works as a design reference for map-centered tracking, ETA visibility, and fare transparency.

From this analysis, BusFinder prioritizes a **search-first flow**, **clear route comparison**, **real-time or estimated bus tracking**, **fare transparency**, and **capacity/luggage visibility**. The benchmark also defines what the project should avoid, such as intrusive ads, mandatory sign-up before basic use, hidden luggage information, and overloaded navigation.

**Full benchmark document:** [Benchmark BusFinder](./Docs/Benchmark%20BusFinder.pdf)

#### Feature Map

![Feature Map - Benchmark](./Docs/Benchmark_Images/Feature%20Map%20-%20Benchmark.jpg)

#### Comparative Summary Table

![Summary Table - 1](./Docs/Benchmark_Images/Sumarry%20Table%20-%201.jpg)

![Summary Table - 2](./Docs/Benchmark_Images/Sumarry%20Table%20-%202.jpg)


---

## 4. Scope - Second Layer

### 4.1. Customer Journey Map

---

## 5. Structure - Third Layer

### 5.1. Navigation Flow

The navigation flow is represented through the BusFinder site map diagram, showing the main app areas and how users move between search, live map, trip management, profile, payment, verification, and support flows.

![Site Map Diagram - BusFinder](./Docs/Site%20Map%20Diagram-BusFinder.jpg)

---

## 6. Skeleton - Fourth Layer

### 6.1. Low-Fi Wireframes

The low-fidelity wireframes document the core mobile screens and interaction paths for planning, selecting, paying for, managing, and modifying trips in BusFinder.

![Low-Fi Wireframes Preview](./Docs/Low-Fi%20Wireframes%20Preview.png)

The preview above shows three representative wireframes. The complete low-fi wireframe set is available in the PDF and Figma links below.

**Low-fi wireframes document:** [Low-Fi Wireframes - PDF](./Docs/Low-Fi%20Wireframes.pdf)

**Figma file:** [Low-Fi Wireframes - Figma](https://www.figma.com/design/ZrcgdOga1rsxqB9vF9FUYD/Act-Lunes-27-Abril-UIX?node-id=0-1&t=ouVhxJIyy2qqlC2H-1)

---

## 7. Surface - Fifth Layer

### 7.1. Interface Evolution

### 7.2. Results of the Heuristic Evaluation

### 7.3. High Definition Interfaces

---
---


## 8. Annex

### 3. Strategy Documents

### 4. Scope Documents

### 5. Structure Documents

### 6. Skeleton Documents

### 7. Surface Documents

---
