# SHIFT-2026-HW6F6P
Challenge_X_Yoddhas
# E-Move: AI-Assisted Battery Intelligence and Route Optimization

**SHIFT Hackathon Project | IIT (BHU), Varanasi**

E-Move is an early-stage prototype designed to help electric micromobility riders estimate battery consumption, understand the effect of temperature and elevation, and plan journeys with better awareness of energy requirements and travel costs.

## 1. Problem Statement

Electric bicycle and micromobility riders need to estimate whether their remaining battery is sufficient for a journey. Energy consumption can vary with riding distance, temperature, elevation changes, vehicle characteristics and riding conditions.

Without reliable estimates, riders may face unexpected battery depletion, unplanned charging stops or uncertainty about journey costs.

## 2. Our Proposed Solution

E-Move aims to combine route information, weather data, elevation data and a battery energy model to provide useful journey estimates before a rider starts travelling.

The project will progressively develop from a basic browser-based prototype into a route-aware decision-support tool.

## 3. Planned Features

- **Battery intelligence:** Estimate journey energy requirements and remaining usable range.
- **Weather-aware estimates:** Explore how temperature conditions influence battery consumption.
- **Elevation-aware estimates:** Account for additional energy demand during uphill travel.
- **Cost estimation:** Calculate approximate electricity costs for a journey.
- **Route comparison:** Compare candidate routes using distance, elevation, estimated energy and cost.
- **Charging discovery:** Identify suitable charging options when reliable location and compatibility data are available.

## 4. Current Implementation

The first prototype includes:

- A browser-based dashboard built with HTML, CSS and JavaScript.
- User inputs for distance, battery percentage, battery capacity, temperature, uphill climb and electricity price.
- A simplified energy-consumption estimate.
- Estimated battery requirement, trip electricity cost and remaining range.
- A basic battery-feasibility message.

## 5. Technology Stack

| Technology | Purpose |
| --- | --- |
| HTML | Dashboard structure |
| CSS | Layout and visual design |
| JavaScript | Input validation and calculations |
| Git and GitHub | Version control and public project repository |
| Weather API | Planned live weather integration |
| OpenStreetMap and elevation data | Planned route and elevation analysis |

## 6. System Architecture

The planned workflow is:

1. Collect the rider's origin, destination and vehicle details.
2. Retrieve route distance and elevation information.
3. Retrieve weather conditions for the relevant journey.
4. Estimate energy consumption using a documented model.
5. Calculate estimated battery feasibility and electricity cost.
6. Compare available routes and identify charging options where reliable data exists.

## 7. Development Roadmap

- [x] Create the initial dashboard.
- [x] Implement a basic energy and cost estimator.
- [ ] Add live weather API integration.
- [ ] Retrieve real route geometry and elevation.
- [ ] Improve the energy model using vehicle-specific parameters.
- [ ] Add route comparison and charging discovery.
- [ ] Test assumptions and document limitations.

## 8. Model Assumptions and Limitations

The current version is an educational prototype, not a certified vehicle-performance predictor. Its energy-per-kilometre value, temperature multipliers and uphill-energy allowance are simplified assumptions. They have not yet been calibrated against measured journeys or a specific vehicle.

Weather data is entered manually. The prototype does not yet retrieve live weather, calculate real routes, or verify charging-station availability. Actual consumption also depends on factors such as vehicle efficiency, rider and cargo mass, speed, tyre pressure, road surface and wind.

Future versions will use real data where available and clearly communicate uncertainty.

## 9. Expected Outcome

E-Move aims to help riders make more informed decisions about battery feasibility, journey energy and electricity costs through an accessible, progressively data-driven tool.

## 10. Project Status

**Version:** 0.1 — Initial working prototype  
**Event:** SHIFT Hackathon, IIT (BHU), Varanasi  
**Status:** Dashboard and simplified estimator implemented; external data integrations are planned.
