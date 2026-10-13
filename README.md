# Campus Access

Public SDP barrier control website. It connects directly to authenticated EMQX
Cloud MQTT over secure WebSocket. The ESP32 connects to the same broker over
MQTT TLS. The website requires the operator’s MQTT login; no credentials are
embedded in these files.

The ESP32 must remain powered and connected to its configured 2.4 GHz Wi-Fi.
RF receipts confirm transmission, not physical position. Session activity is
held in the current tab only. Fonts and their licenses are self-hosted.

This repository contains deployed static assets only. Private device
configuration and other project files are kept in the separate private project.
