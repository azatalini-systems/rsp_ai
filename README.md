# RSP AI Detector (Web-Based Implementation)

A real-time **Rock-Paper-Scissors** gesture recognition application built with **TensorFlow.js**. This project demonstrates the seamless integration of machine learning into a mobile-friendly web environment, deployed securely via **GitHub Pages**.

## Key Features
* **Real-time Inference**: Ultra-fast gesture detection using the smartphone's camera.
* **Edge Computing**: Powered by `TensorFlow.js`, processing happens entirely on the user's device (client-side) for maximum privacy and speed.
* **Cross-Platform**: Zero installation required; runs directly in any modern mobile browser (Chrome/Safari).
* **Secure Deployment**: Fully compliant with **Secure Context** policies through enforced HTTPS.

## Tech Stack
* **Core**: HTML5, CSS3 (Flexbox/Grid), JavaScript (ES6+).
* **AI/ML**: `@tensorflow/tfjs` & `@teachablemachine/image`.
* **Deployment**: GitHub Pages (SSL/TLS Encrypted).
* **Development Environment**: PyCharm & Google Teachable Machine.

## Cyber Security Insights (DevSec)
As a **Cyber Security** enthusiast, this project incorporates several security best practices:
1.  **Secure Origin Policy**: Implemented HTTPS to satisfy browser requirements for accessing sensitive hardware (Camera API).
2.  **CDN Subresource Integrity**: Loading machine learning libraries from trusted Content Delivery Networks.
3.  **No Server-Side Data Logging**: By utilizing client-side inference, no image data is transmitted to a server, significantly reducing the attack surface for data breaches.

## Demo
Check out the live application here: https://azatalini-systems.github.io/rsp_ai/

---
Developed with ❤️ by **Amalia**. 
*Advancing at the intersection of AI Development and Cyber Security.*
