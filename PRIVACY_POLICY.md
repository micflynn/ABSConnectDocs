# Privacy Policy — ABS Connect

**Effective Date:** November 19, 2026  
**Application:** ABS Connect (Roku Channel)

---

## 1. Overview
**ABS Connect** is an independent, third-party Roku client for self-hosted [Audiobookshelf](https://www.audiobookshelf.org/) servers. ABS Connect is **not** affiliated with, maintained by, or endorsed by Audiobookshelf.

ABS Connect does **not** operate any developer-hosted backend servers, does **not** collect telemetry or usage analytics, and does **not** display advertisements or share data with third-party trackers.

---

## 2. Information Processed by the Application

### A. Data Sent Directly to Your Audiobookshelf Server
All network requests made by ABS Connect go **exclusively** to the Audiobookshelf server URL(s) that you configure inside the app. Depending on how you use the app, ABS Connect transmits:
- **Authentication Credentials:** Your username and password when signing in to your Audiobookshelf server (used solely to obtain an authentication token from your server; your password is **not** stored on the Roku device).
- **Library & Playback Requests:** Requests for libraries, audiobooks, podcasts, cover art, audio streams, search queries (including text entered via Roku voice dictation), playback progress syncs, queue updates, and playlist edits.

Your self-hosted Audiobookshelf server's own logging and privacy practices govern how your server handles those requests.

### B. Data Stored Locally on Your Roku Device
To remember your setup and preferences between launches, ABS Connect stores the following data locally in your Roku device's private channel registry (`roRegistrySection`):
- **Server Configurations:** Server names and URLs you add.
- **User Profiles & Session Tokens:** User ID, username, server association, and the session authentication token returned by your Audiobookshelf server.
- **Playback Bookmarks:** Local resume timestamps and durations for active items.
- **App & Per-User Preferences:** Slideshow settings, mini-player mode, view-wrapping preference, overscan compensation, grid/list layout and font sizes, and audio/video player node selection.

This local data never leaves your Roku device except when authenticating or syncing with your configured Audiobookshelf server.

---

## 3. Third-Party Services & Children's Privacy
- **No Third-Party SDKs or Ads:** ABS Connect contains no third-party advertising networks, analytics SDKs, or data brokers.
- **Roku Platform Features:** If you use Roku's system voice-to-text microphone on the on-screen keyboard, voice processing is handled by Roku OS under Roku's own Privacy Policy.
- **Children's Privacy:** ABS Connect does not knowingly collect personal information from children; any content accessed depends entirely on the Audiobookshelf server you connect to.

---

## 4. Managing & Deleting Your Data
You are in full control of all locally stored data:
- **Remove a User Profile:** On the **Who's Listening?** screen, press and hold **OK** on a profile tile and select **Remove User**.
- **Remove a Server:** Open **Configure Servers**, select a server, and choose **Delete Server**.
- **Clear All Local Data:** Uninstalling **ABS Connect** from your Roku device removes the channel and its local registry storage.

---

## 5. Changes & Contact
This Privacy Policy may be updated alongside future releases of ABS Connect. For questions or support regarding ABS Connect, please contact the developer via the support contact listed on the Roku Channel Store listing or project repository.
