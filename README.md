Save Me is an Android-based women’s security application designed to provide immediate emergency assistance during critical situations. The application enables users to quickly share their real-time location, send emergency SMS alerts, and initiate direct emergency calls, ensuring rapid response and enhanced personal safety.

##  Technology Stack
* **Programming Language:** Java
* **UI Design:** XML
* **Platform:** Android

###  APIs & Services
* GPS & Location Services
* SMS Manager
* Phone Call Services
* Android Runtime Permissions

## 🔄 Application Workflow
1. User grants required Android permissions (Location, SMS, Call)
2. User registers personal details and emergency contacts
3. Application fetches real-time location using GPS
4. In an emergency:

   * Sends SMS alerts with location details to trusted contacts
   * Optionally sends alerts to newly entered contacts
   * Automatically initiates an emergency call to **999**

##  Android Components & APIs Used
###  Location & Permission Handling
* `android.location.Location`
* `android.location.LocationManager`
* `android.location.Geocoder`
* `android.Manifest`

### 📩 Messaging & Calling
* `android.telephony.SmsManager`
* Phone call intents for emergency dialing

### 💾 Data Storage
* `SharedPreferences`
* Local data persistence for user and contact details

