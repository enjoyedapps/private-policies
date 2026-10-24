# Privacy Policy for FreeToilet

**Last updated:** October 24, 2026

**FreeToilet** ("we", "our", or "us") is dedicated to protecting your privacy. This Privacy Policy explains how our native Android application ("App") handles your information when you use our service to find free, clean, and accessible public restrooms.

---

## 1. Information We Collect

### A. Location Data
- **What We Collect:** When you grant permission, the App accesses your device's approximate (`ACCESS_COARSE_LOCATION`) or precise (`ACCESS_FINE_LOCATION`) location.
- **Why We Collect It:** Location data is used **exclusively in real time** to identify and display nearby public restrooms, calculate walking distances, and estimate walking times.
- **Retention & Storage:** **We do NOT store, record, or track your location on any remote server.** Your location stays on your device and is discarded when the query completes.
- **Optional Use:** You can use the App without granting location permissions by searching for cities, addresses, or landmarks manually.

### B. User-Generated Contributions (Crowdsourcing)
- If you voluntarily submit a new restroom location, update an access door code, verify whether a toilet is free, or submit a review/rating, this non-personal information is stored locally and contributed to the public map dataset to benefit other travelers.

---

## 2. Third-Party Services & Map Providers

The App utilizes open, transparent, and privacy-respecting mapping infrastructure:
- **OpenStreetMap (OSM) & Overpass API:** We retrieve public restroom coordinates and map tiles from OpenStreetMap. Tile requests communicate with OSM tile servers subject to OSM’s privacy policy. No personal identifiers are transmitted.
- **External Navigation Services:** When you tap "Navigate", the App initiates an Android Intent allowing you to choose your preferred external navigation provider (such as Google Maps). That provider's respective privacy policy governs their service.

---

## 3. Data Safety & GDPR Compliance

- **No Data Sharing:** We do not sell, rent, or trade your personal data to any third parties or advertising networks.
- **No Account Required:** You do not need to register an account, provide an email address, or log in to use FreeToilet.
- **Encryption:** All network communications with OpenStreetMap / Overpass API occur over secure HTTPS / TLS protocols.
- **European GDPR:** Because our primary target is the European Union, we fully adhere to data minimization and user consent principles.

---

## 4. Permissions Used

- `android.permission.ACCESS_FINE_LOCATION` & `ACCESS_COARSE_LOCATION`: To display nearby public restrooms.
- `android.permission.INTERNET` & `ACCESS_NETWORK_STATE`: To load map tiles and query OpenStreetMap public toilet nodes.

---

## 5. Contact Us

If you have any questions or concerns regarding this Privacy Policy, please contact:
- **Developer:** enjoyedapps
- **Email:** enjoyedapp@gmail.com
