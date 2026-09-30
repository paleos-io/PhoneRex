Phone Rex is an offline, security-first dialer that keeps calling data from becoming an easy target. It has no Internet permission; meaning, absolutely no cloud caller-ID lookup, telemetry, analytics, ads, or sync. And its caller screening is local. Block numbers on your list, hidden callers, and confirmed unknown callers without feeding contacts, call behavior, or spam decisions to a third party. No network path means far less opportunity for remote exfiltration, malicious remote content, and cloud-connected dialer surveillance.

Its in-call interface is engineered for hostile-device conditions. Screenshot and screen-recording protections keep protected call surfaces out of routine capture paths; overlay suppression and obscured-touch filtering help stop fake call screens, tapjacking, and consent spoofing. Security-focused project-owned UI reduces reliance on dynamic system theming, while hardened surfaces reduce GPU and compositor exposure. A proximity-sensor control and status-bar privacy option reduce call-state signals and visible indicators other apps can scrape.

Phone Rex delivers SS7, Stingray, IMSI-catcher, and TEMPEST mitigation at the endpoint. Although it cannot alter carrier signaling or radio hardware, it limits the app-level data those threats can pair with or pull through a compromised device: there is no Phone Rex account to subpoena, poison, or silently sync; no app network channel to receive hostile caller data; and no exported blocked-call dossier. Encrypted settings, a separate encrypted redacted audit, disabled Android backup, and bounded retention keep sensitive evidence local and minimize what remains after intrusion. Phone Rex is built to disclose less, trust less, and resist more.

New Features

    Obscured touch filtering

Features

    SS7 extraction resistance
    Zero call history export controls
    ADB forensic extraction mitigation
    No reliance on system UI components or fonts
    Hardened call screen with unconditional FLAG_SECURE
    CPU-only rendering for GPU side-channel defense
    Native tapjacking/overlay protection
    Disable proximity sensor during calls
    Systen-CA only trust anchors
