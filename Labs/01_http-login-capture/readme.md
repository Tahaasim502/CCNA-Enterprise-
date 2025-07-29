# Lab 01 – Capturing HTTP Login Credentials with Wireshark

## Objective
To capture a username and password submitted via an HTTP login form using Wireshark and analyze the `POST` request.

## Tools Used
- Wireshark
- Local or test HTTP login page
- testphp.vulnweb.com/login.php(testing website)

## Steps Followed
1. Started Wireshark and selected the Wi-Fi interface.
2. Applied the display filter: `http.request.method == "POST"`
3. Logged into a test website with a username and password.
4. Inspected the captured `POST` packet and extracted the credentials from the `HTML Form URL Encoded` section.

## Key Concepts Learned
- HTTP is plaintext and not secure for credentials
- POST method carries sensitive data in the payload
- Importance of HTTPS in modern networks

## ScreenShots 

<img width="1363" height="90" alt="Screenshot 2025-07-29 170900" src="https://github.com/user-attachments/assets/d0d4b329-627f-4083-acba-b08f9018f6ac" />

<img width="623" height="388" alt="Screenshot 2025-07-29 170919" src="https://github.com/user-attachments/assets/adae797b-15d4-48f5-86c6-3e6afc3b3c72" />

<img width="514" height="31" alt="Screenshot 2025-07-29 170937" src="https://github.com/user-attachments/assets/3b336c69-4fa9-4325-975d-56108b1e5db9" />


