# Awesome Mobile Security [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of tools, frameworks, practices, and resources for mobile security — covering secure storage, app hardening, reverse engineering protection, authentication, and privacy across iOS and Android.

## Contents

- [Security Standards & Guidelines](#security-standards--guidelines)
- [Secure Storage](#secure-storage)
- [Authentication & Identity](#authentication--identity)
- [Network Security](#network-security)
- [App Hardening & Protection](#app-hardening--protection)
- [Reverse Engineering & Analysis](#reverse-engineering--analysis)
- [Vulnerability Scanning & Testing](#vulnerability-scanning--testing)
- [Monitoring & Runtime Protection](#monitoring--runtime-protection)
- [Privacy & Data Protection](#privacy--data-protection)
- [Learning & Resources](#learning--resources)

## Security Standards & Guidelines

Best practices and frameworks for mobile security.

- [OWASP Mobile Top 10](https://owasp.org/www-project-mobile-top-10/) — List of the most critical mobile security risks.
- [OWASP Mobile Security Testing Guide (MSTG)](https://owasp.org/www-project-mobile-security-testing-guide/) — Comprehensive guide for mobile app security testing.
- [OWASP MASVS](https://owasp.org/www-project-mobile-app-security/) — Mobile Application Security Verification Standard.
- [Apple App Security](https://developer.apple.com/security/) — Security guidelines and documentation for iOS.
- [Android Security](https://source.android.com/security) — Android platform security model and practices.

## Secure Storage

Mechanisms for securely storing sensitive data on mobile devices.

- [Keychain Services](https://developer.apple.com/documentation/security/keychain_services) — Secure storage for iOS credentials and secrets.
- [Android Keystore](https://developer.android.com/training/articles/keystore) — Secure key storage for Android apps.
- [EncryptedSharedPreferences](https://developer.android.com/topic/security/data) — Encrypted storage for Android preferences.
- [SQLCipher](https://www.zetetic.net/sqlcipher/) — Encrypted SQLite database for mobile apps.
- [Secure Storage (Flutter)](https://pub.dev/packages/flutter_secure_storage) — Secure key-value storage for Flutter apps.

## Authentication & Identity

Tools and frameworks for user authentication and identity management.

- [Firebase Authentication](https://firebase.google.com/products/auth) — Authentication platform supporting multiple providers.
- [Auth0](https://auth0.com/) — Identity platform for authentication and authorization.
- [OAuth 2.0](https://oauth.net/2/) — Authorization framework for secure access.
- [OpenID Connect](https://openid.net/connect/) — Identity layer on top of OAuth 2.0.
- [Apple Sign In](https://developer.apple.com/sign-in-with-apple/) — Privacy-focused authentication for iOS apps.

## Network Security

Tools and practices for securing data in transit.

- HTTPS/TLS — Secure communication protocol for network requests.
- [TrustKit](https://github.com/datatheorem/TrustKit) — SSL pinning implementation for iOS.
- [OkHttp Certificate Pinning](https://square.github.io/okhttp/) — Certificate pinning support for Android.
- [Charles Proxy](https://www.charlesproxy.com/) — Tool for inspecting network traffic.
- [mitmproxy](https://mitmproxy.org/) — Intercepting proxy for analyzing network traffic.

## App Hardening & Protection

Techniques for protecting apps against tampering and unauthorized access.

- [ProGuard](https://www.guardsquare.com/proguard) — Code shrinking and obfuscation for Android.
- [R8](https://developer.android.com/studio/build/shrink-code) — Android code optimizer and obfuscator.
- [DexGuard](https://www.guardsquare.com/dexguard) — Advanced protection for Android apps.
- [iOS App Attest](https://developer.apple.com/documentation/devicecheck/validating_apps_that_connect_to_your_server) — App integrity verification for iOS.
- Code obfuscation — Techniques for making code harder to reverse engineer.

## Reverse Engineering & Analysis

Tools for analyzing and decompiling mobile applications.

- [Frida](https://frida.re/) — Dynamic instrumentation toolkit for mobile apps.
- [Jadx](https://github.com/skylot/jadx) — Dex to Java decompiler for Android.
- [apktool](https://ibotpeaches.github.io/Apktool/) — Tool for reverse engineering Android APKs.
- [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) — Automated mobile security testing framework.
- [Ghidra](https://ghidra-sre.org/) — Software reverse engineering suite.

## Vulnerability Scanning & Testing

Tools for identifying and testing security vulnerabilities.

- [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) — Static and dynamic analysis for mobile apps.
- [QARK](https://github.com/linkedin/qark) — Static analysis tool for Android vulnerabilities.
- [Drozer](https://github.com/FSecureLABS/drozer) — Security testing framework for Android.
- [Needle](https://github.com/mwrlabs/needle) — Security testing framework for iOS apps.
- [Burp Suite](https://portswigger.net/burp) — Web and mobile application security testing platform.

## Monitoring & Runtime Protection

Tools for detecting threats and protecting apps at runtime.

- [Firebase App Check](https://firebase.google.com/products/app-check) — Protect backend resources from abuse.
- [Sentry](https://sentry.io/) — Error monitoring and performance tracking.
- [Appdome](https://www.appdome.com/) — Mobile app security and runtime protection platform.
- [Guardsquare](https://www.guardsquare.com/) — Mobile app security solutions.
- Runtime Application Self-Protection (RASP) — Techniques for detecting and preventing attacks during execution.

## Privacy & Data Protection

Tools and practices for protecting user data and ensuring compliance.

- [GDPR](https://gdpr.eu/) — Data protection regulation in the European Union.
- [CCPA](https://oag.ca.gov/privacy/ccpa) — California privacy regulation.
- [Apple App Privacy](https://developer.apple.com/app-store/app-privacy-details/) — Privacy requirements for iOS apps.
- [Android Privacy](https://developer.android.com/privacy) — Privacy practices for Android apps.
- Data minimization — Collecting only necessary user data.

## Learning & Resources

Educational materials and references for mobile security.

- [OWASP Mobile Security Project](https://owasp.org/www-project-mobile-security/) — Resources and tools for mobile security.
- [Android Security Blog](https://security.googleblog.com/) — Updates on Android security.
- [Apple Security Updates](https://support.apple.com/en-us/HT201222) — Security advisories for Apple platforms.
- [Mobile Security Testing Guide](https://owasp.org/www-project-mobile-security-testing-guide/) — In-depth testing reference.
- [PortSwigger Web Security Academy](https://portswigger.net/web-security) — Training on web and mobile security concepts.

## Related Awesome Lists

- [Awesome Mobile Development](https://github.com/brandonhimpfen/awesome-mobile-development) — Tools and frameworks for mobile apps.
- [Awesome Cybersecurity](https://github.com/brandonhimpfen/awesome-cybersecurity) — General security tools and frameworks.
- [Awesome Privacy](https://github.com/brandonhimpfen/awesome-privacy) — Privacy tools and resources.
- [Awesome DevOps](https://github.com/brandonhimpfen/awesome-devops) — DevOps tools and practices.
  
## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

Automated checks: link checking (PR + weekly), duplicate URL detection, and a lightweight Awesome List lint.
