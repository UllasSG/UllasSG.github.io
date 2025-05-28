---
title: "3-Factor Authentication"
excerpt: |
  <style>
    .hover-card {
      position: relative;
      width: 400px;
      height: 250px;
      background-color: #f2f2f2;
      border-radius: 10px;
      display: block;
      overflow: hidden;
      perspective: 1000px;
      box-shadow: 0 0 0 5px #ffffff80;
      transition: transform 0.6s cubic-bezier(0.175, 0.885, 0.32, 1.275), box-shadow 0.6s ease;
      margin-top: 10px;
      cursor: pointer;
    }

    .hover-card:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
    }

    .hover-card img {
      position: absolute;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: 1;
    }

    .hover-card .card__content {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      padding: 20px;
      box-sizing: border-box;
      background-color: rgba(242, 242, 242, 0.95);
      transform: rotateX(-90deg);
      transform-origin: bottom;
      transition: transform 0.6s cubic-bezier(0.175, 0.885, 0.32, 1.275);
      z-index: 2;
    }

    .hover-card:hover .card__content {
      transform: rotateX(0deg);
    }

    .hover-card .card__title {
      margin: 0;
      font-size: 24px;
      color: #333;
      font-weight: 700;
    }

    .hover-card .card__description {
      margin: 10px 0 0;
      font-size: 14px;
      color: #555;
      line-height: 1.4;
    }
  </style>

  <div class="hover-card" onclick="window.location.href='https://ullassg.github.io/portfolio/4-3factor-auth/';">
    <img src="/images/3fa-pic.jpg" alt="3-Factor Authentication">
    <div class="card__content">
      <p class="card__title">3-Factor Authentication</p>
      <p class="card__description">Hardware-based authentication system using Arduino.</p>
    </div>
  </div>
collection: portfolio
---

Designed and implemented a hardware-based multi-factor authentication system using Arduino.

- Integrated biometric fingerprint scanning, RFID tag verification, and secure keypad code entry  
- Developed firmware to manage authentication processes and security protocols  
- Created a layered security system with fail-safe mechanisms to prevent unauthorized access  
