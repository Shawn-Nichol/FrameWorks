Supervised remote identity proofing is a specialized process outlined in SP 800-63A section 5.3.3.2, designed to provide controls for comparable levels of confidence and security to in-person identity proofing processes for situations where remote identity proofing is necessary or preferred. Here are some key points and requirements related to supervised remote identity proofing:

**Use Cases for Supervised Remote Identity Proofing:**
- Supervised remote identity proofing is optional for CSPs. If a CSP chooses to use it, the requirements outlined in section 5.3.3.2 apply.
- It's used for identity proofing of individuals in remote locations where traveling to the CSP for in-person identity proofing is impractical.
- It can also be used to achieve comparability with in-person requirements when face-to-face encounters pose health risks to the applicant or CSP personnel, such as during a health crisis like the COVID-19 pandemic.
- In cases where supervised remote identity proofing is used, applicants and CSP operators are not physically in the same location but are connected through technology.

**Components and Technology:**
- Supervised remote identity proofing takes advantage of advancements in sensor technology (cameras and biometric sensors) and high-speed communications to closely replicate the security of in-person identity proofing.
- A remote identity proofing station (or kiosk) is used, and it should be under the control of the CSP or a trusted third party.
- The integrity of the process relies on the continuous presence and observation of the applicant by the CSP operator throughout the session to prevent fraud.
- Cameras should be positioned to capture the upper body, hands, and face of the applicant, as well as all interactions with devices like a keyboard, fingerprint capture device, signature pad, or scanner, if applicable.

**Protection and Security:**
- Technologies like RFID and chip readers may be used for digital validation of identity evidence, and these devices should be integrated into the remote identity proofing stations to reduce the risk of tampering.
- The level of protection and integrity required for the kiosk depends on its location. For example, kiosks in restricted areas may require less tamper detection than those in semi-public spaces like shopping malls.
- In most cases, a human attendant oversees the kiosk, supplements security features, and ensures the integrity of the kiosk and the identity proofing process.
- The attendant's responsibilities may include ensuring that only one individual interacts with the kiosk during each session, maintaining the physical integrity of the kiosk and its sensors, verifying that the applicant does not use any devices to spoof biometric sensors, and reporting any issues to the CSP.

**Mutual Authentication and Encryption:**
- Supervised remote identity proofing stations/kiosks are required to employ mutual authentication, where both the station/kiosk and the server authenticate each other.
- This mutual authentication is often achieved through the use of mutual TLS (Transport Layer Security).
- Once successful mutual authentication occurs, an encrypted communication channel is established between the workstation/kiosk and the server, protecting the data exchanged between them.

In summary, supervised remote identity proofing is a secure process that allows for remote identity proofing in situations where in-person interactions are impractical or pose health risks. It relies on advanced technology, continuous applicant observation, and security measures to prevent fraud and maintain the integrity of the identity proofing process. Mutual authentication and encryption are also employed to protect data during the process.
