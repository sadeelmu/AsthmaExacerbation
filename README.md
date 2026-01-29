# AsthmaExacerbation  
### Asthma Exacerbation Prediction and Management Mobile System

**Author:** Sadel Muwahed  
**Year:** 2026  

---

## Overview

AsthmaExacerbation is a mobile health system designed to predict and manage asthma exacerbation risk using a combination of environmental signals and physiological biosignals collected from wearable devices.

The system integrates Apple Watch biosignals with environmental context to compute a personalized asthma risk index and deliver actionable alerts, guided interventions, and remote monitoring capabilities.

This repository serves as a **public companion to a conference submission** and contains project documentation and interface illustrations only.

The full implementation is not publicly released at this stage.

---

## System Description

The platform performs continuous risk estimation by combining:

- environmental exposure indicators  
- physiological biosignals  
- user-reported context  
- historical trends  

These signals are fused into a predictive model that produces a dynamic asthma threat score. When elevated risk is detected, the system triggers preventive guidance and alerts.

The architecture supports both patient-facing interaction and remote companion monitoring.

---

## Features

- **Asthma Risk Prediction**  
  Continuous prediction based on environmental and wearable biosignal data.

- **Real-Time Monitoring**  
  Integration with Apple Watch and HealthKit for heart rate, blood oxygen saturation, and activity metrics.

- **Personalized Alerts**  
  Risk-based notifications with emergency contact options and intervention guidance.

- **Guided Breathing Exercises**  
  Built-in therapeutic breathing workflows for acute relief.

- **Companion Application**  
  Remote dashboard allowing a clinician or caregiver to monitor patient risk levels.

---

## Technology Stack

- **Mobile Development:** Swift, SwiftUI  
- **Database:** SQLite  
- **Frameworks:** HealthKit, WatchKit, WeatherKit  
- **Wearable Integration:** Apple Watch biosignal pipeline

---

## Code Availability

The complete source code is currently restricted.

This repository is provided for documentation and academic transparency only.  
The implementation may be shared upon request for research collaboration or peer review.

For inquiries: contact the author directly.

---

## License

Copyright (c) 2026 Sadel Muwahed  
All rights reserved.

This material is provided for academic documentation purposes only.  
No permission is granted to copy, modify, or redistribute the implementation without explicit written consent.

---

## Screenshots

<table>
  <tr>
    <td align="center">
      <img src="Pics/Asthma%20threat%20dashboard.png" width="300"><br>
      Asthma Threat Dashboard
    </td>
    <td align="center">
      <img src="Pics/High%20asthma%20threat.png" width="300"><br>
      High Asthma Threat Alert
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="Pics/Survey.png" width="300"><br>
      Environmental Survey
    </td>
    <td align="center">
      <img src="Pics/Asthma%20threat%20breakdown.png" width="300"><br>
      Threat Breakdown
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="Pics/Historical%20data.png" width="300"><br>
      Historical Data Overview
    </td>
    <td align="center">
      <img src="Pics/Breathing%20exercises.png" width="300"><br>
      Breathing Exercises
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="Pics/Companion%20dashboard.png" width="300"><br>
      Companion Dashboard
    </td>
    <td align="center">
      <img src="Pics/Login%20companion.png" width="300"><br>
      Companion Login
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="Pics/Login%20patient.png" width="300"><br>
      Patient Login
    </td>
    <td align="center">
      <img src="Pics/Register%20patient.png" width="300"><br>
      Patient Registration
    </td>
  </tr>
</table>
