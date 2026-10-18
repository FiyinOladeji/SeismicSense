# SeismicSense
**Technathon Fall 2026 Project**
Alex Ma, Fiyin Oladeji, Fiyin Oladeji

**Overview**

SeismicSense is a prototype designed to detect abnormal motion locally and provide emergency information when conventional communication infrastructure may be unavailable.

An ESP32 microcontroller reads motion data from an MPU6050 accelerometer and gyroscope module. When measured motion meets the prototype's configurable detection criteria, the firmware transitions into an emergency state.

The planned emergency response includes a local audible/visual alarm, a Wi-Fi access point, and a browser-based emergency information portal hosted directly on the ESP32.

The ESP32 also is connected to a local network of other SeismicSense's conversing between each other if one is in Emergency State

**Problem**

Earthquake early warnings may provide little or no lead time near an earthquake's source. Earthquakes can also disrupt electrical power, cellular networks, internet access, and cloud services.

SeismicSense explores how a locally operating device can continue providing essential information without relying on those external services.

DUE DATE: 10/18/2026
