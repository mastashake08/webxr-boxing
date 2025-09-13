WebXR Peer-to-Peer Avatar Sync
📝 Overview
This project is a simple web application that demonstrates a shared multi-user experience in WebXR (VR/AR). It uses Three.js for 3D rendering, the WebXR API for immersive sessions, and PeerJS for establishing a direct peer-to-peer connection between two users.

When two users connect and enter an XR session, they can see a real-time representation of the other person's head movements, visualized as a simple avatar.

✨ Features
Shared 3D Space: A basic virtual room where users can interact.

Peer-to-Peer Connection: Uses PeerJS to connect two browsers directly without a central server for data transfer, ensuring low latency.

Real-Time Avatar Sync: Synchronizes the head position and rotation of each user in real-time.

WebXR Integration: Supports both VR and AR devices through the WebXR API.

Simple UI: A clean interface for copying personal IDs and connecting to a peer.

🚀 Technologies Used
Three.js: A JavaScript library for creating and displaying 3D graphics in a web browser.

PeerJS: Simplifies browser-based peer-to-peer WebRTC data connections.

WebXR Device API: Provides access to virtual reality (VR) and augmented reality (AR) devices.

Tailwind CSS: For styling the user interface.

⚙️ How to Use
This application is designed to be run directly in a browser and does not require a build step.

Open the Application: Open the index.html file in a modern, WebXR-compatible browser (like Google Chrome, Microsoft Edge, or the Meta Quest Browser). You will need two instances running.

You can do this on two separate devices on the same network.

Or, you can open two separate tabs on the same computer for testing.

Get Your ID: The application will automatically connect to the PeerJS server and display a unique ID under "Your ID".

Connect with a Friend:

Copy the ID from one user (User A).

In the other user's browser (User B), paste User A's ID into the "Friend's ID" input field.

Click the "Connect" button.

Enter XR: Once the status shows "Connected", both users should click the "Enter VR" (or "Enter AR") button that appears on the screen.

See Each Other: In the virtual space, you will now see a blue avatar that mirrors the head movements of the other connected user in real-time.

📁 File Structure
The entire application—including HTML structure, CSS styling, and JavaScript logic—is contained within a single index.html file for simplicity and portability.
