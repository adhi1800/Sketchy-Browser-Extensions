# Sketchy-Browser-Extensions

## How to Identify a Suspicious Browser**

**1. User-Agent String Analysis**

**2. Check if the User-Agent header looks unusual or inconsistent.**
Example of suspicious cases:

* Empty or missing User-Agent.

* Mismatched details (e.g., Windows NT 10.0 but claiming to be Safari on macOS).

* Known automation tools: curl, python-requests, sqlmap, nikto, etc.

* Use databases of valid User-Agents to compare.

**3. Browser Fingerprinting**
* Collect and check properties like:

* Screen resolution, timezone, plugins, WebGL, canvas fingerprint.

* If multiple clients show identical rare fingerprints, it may indicate bots or emulators.

* Tools like AmIUnique or FingerprintJS are used for this.

**4 Suspicious Browser Permissions**

* Excessive or Unnecessary Permissions

A regular site might request:

Camera / microphone (for video calls)

Location (maps)

Notifications (messaging apps)

* Suspicious signs:

A random website asking for camera or microphone access without reason.

Browser requesting file system, clipboard, or OS-level access unexpectedly.

Permission requests on sites that don’t need them (e.g., a blog asking for mic access).
<img width="1024" height="699" alt="image" src="https://github.com/user-attachments/assets/0e746071-d0d6-478c-a48a-16dd7637d560" />
