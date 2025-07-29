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


