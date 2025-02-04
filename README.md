# ADSB.tv by Decentrafly, Inc.

**ADSB.tv** is an innovative project by **Decentrafly, Inc.** that aggregates live ADS-B data and integrates it with real-time YouTube streams from various global locations. Our mission is to provide aviation enthusiasts and the public with an interactive map that not only shows live aircraft tracking but also streams live ADS-B video feeds.

## Project Overview

Our project consists of:

* An [**Interactive Map**](https://john-d-fly.github.io/adsb-tv-map/) providing a web-based interface displaying multiple locations with live ADS-B video streams
* A **Real-Time Data Feeder** powering our map with a custom tar1090 feeder hosted at [globe.decentrafly.org](https://globe.decentrafly.org), which collects live ADS-B data
* **Stream Integration** where each map marker corresponds to a live YouTube stream for watching live aircraft tracking and viewing the skies

## Goals

### 1. Display Live ADS-B Streams
Show various ADS-B live feeds on an interactive map for aviation enthusiasts worldwide.

### 2. Leverage Our Custom Data Feeder
Utilize our own tar1090 feeder ([globe.decentrafly.org](https://globe.decentrafly.org)) to supply real-time aircraft tracking data.

### 3. Empower Community Contributions
Enable anyone to contribute by adding new stream locations or updating existing ones via pull requests.

### 4. Enhance User Experience

* **Short Term**: Automate the detection of live streams and visually highlight active feeds
* **Medium Term**: Integrate live statistics (e.g., viewer counts, aircraft tracked) on the page
* **Long Term**: Develop a custom version of Tar1090 that overlays aircraft tracking data directly onto the live YouTube stream view

## How to Contribute

We welcome community contributions! Here's how you can help:

### 1. Fork the Repository
Click the **Fork** button at the top-right of the repository page.

### 2. Clone Your Fork Locally
```bash
git clone https://github.com/your-username/adsb.tv.git
cd adsb.tv
```

### 3. Create a New Branch
Create a branch for your changes:
```bash
git checkout -b add-new-location
```

### 4. Update Location Data
* Locate the file where channel/location data is stored
* Add your new location with geographical coordinates and YouTube stream link
* Ensure your changes follow the existing format and style

### 5. Submit a Pull Request
Submit your changes via pull request and include relevant context and descriptions.

## Future Enhancements

### Automated Live Stream Detection
Develop a system that automatically detects when a stream goes live and highlights the corresponding marker on the map.

### Live Statistics Integration
Display real-time stats such as active stream viewer counts, the number of aircraft tracked, and other relevant metrics.

### Custom Tar1090 Integration
Create a tailored version of Tar1090 that overlays live ADS-B data onto the YouTube streams, helping viewers track incoming aircraft directly in the live stream view.

## About Decentrafly, Inc.

Decentrafly, Inc. is dedicated to harnessing real-time aviation data to create engaging, informative platforms for aviation enthusiasts and the general public. By democratizing access to live ADS-B data, we empower the community to contribute and expand our projects, making aviation data more accessible and interactive for everyone.

For further inquiries or support, please reach out at contact@decentrafly.org.

Thank you for your interest in ADSB.tv. We look forward to your contributions and to creating a world-class aviation tracking experience together!
