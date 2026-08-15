DHS Admin App - Updated
- Top header: glass Notification + Profile SVG buttons.
- Bottom navigation: Home, Bookings, Bill, Payment (4 buttons only).
- Home dashboard: Total Bookings, Total Bills, Total Payments, New Notifications.
- Firestore realtime booking listener for new customer website bookings.
- New booking notification + repeating ring sound while the web app is active.
- Opening/focusing the app stops the ring.
- Browser Notification permission is requested after the first tap.
- Bills are saved to Firestore collection: bills.
- Payments are read from Firestore collection: payments.
- Required Firestore collection: bookings.
IMPORTANT: True background phone ringing while the PWA is fully suspended/closed requires Firebase Cloud Messaging (FCM) + a server/Cloud Function to send push notifications. This static app cannot create that server-side push by itself.
