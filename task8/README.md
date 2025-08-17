Tools Used
ProtonVPN Free (Windows desktop client)

whatismyipaddress.com (for IP verification)

Steps Performed
Sign-up and Install

Created a Proton account and installed the ProtonVPN desktop client (free tier).

Initial Status (No VPN)

Opened ProtonVPN. Status showed Unprotected with the system’s normal Internet route. The home screen displayed “Fastest free server” with Connect button.

Evidence: screenshots/Screenshot-2025-08-17-190019.jpg

Baseline IP Check (No VPN)

Visited whatismyipaddress.com before connecting. The site displayed my real ISP and Indian geolocation (Ariyalur, Tamil Nadu).

Evidence: screenshots/Screenshot-2025-08-17-190213.jpg

Connect to VPN

Chose “Fastest free server” and connected to a United States free server (label: US-FREE). Protocol shown in the app: WireGuard (UDP).

Evidence: screenshots/Screenshot-2025-08-17-190351.jpg

Verify IP Change (With VPN)

Refreshed whatismyipaddress.com after connection. The site now showed a different public IPv4 address associated with a VPN server in Miami, Florida, United States. IPv6 not detected over this tunnel—expected on many VPN endpoints.

Evidence: screenshots/Screenshot-2025-08-17-190327.jpg

Encrypted Browsing Test

Opened several HTTPS sites while connected. ProtonVPN’s live traffic graph indicated ongoing encrypted traffic through the tunnel.

Disconnect and Compare

After testing, disconnected from the VPN. IP reverted to the original ISP/geolocation and browsing speed improved versus the VPN session, demonstrating the typical speed overhead of tunneling and extra routing distance.