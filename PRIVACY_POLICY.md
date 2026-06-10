# Privacy Policy

**Mintaris** ("the App") is operated by Own The Stars ("we", "us", "our"). This policy describes how we collect, use, and protect your information.

**Last updated:** June 9, 2026

---

## 1. Information We Collect

### Wallet Data
When you create an account, the App generates a cryptographic wallet on your device. Your private key is stored locally in your device's secure enclave (iOS Keychain / Android Keystore) and is **never transmitted** to our servers or any third party.

Your public wallet address is sent to our backend to identify your account and execute blockchain transactions on your behalf (minting NFTs, managing resources, etc.).

### Blockchain Data
All game actions (building, minting, trading) are recorded on the Base blockchain, a public network. Blockchain transactions are permanent, public, and cannot be deleted. Your wallet address and transaction history are visible to anyone on the blockchain.

### Analytics & Crash Data
We use **Firebase Analytics** and **Firebase Crashlytics** (by Google) to understand app usage and diagnose crashes. This includes:
- App events (screen views, feature usage)
- Crash logs and stack traces
- Device type, OS version, and app version
- A Firebase-assigned device identifier

Analytics and crash data are associated with your wallet address to help us debug issues.

### ENS Names
If an ENS subdomain (e.g., `yourname.ownthestars.eth`) is registered for your account, this name is stored on the Base blockchain (public) and cached in our database for in-app display.

## 2. Information We Do NOT Collect

- Personal identity (name, email, phone number)
- Location data
- Contacts or photos
- Biometric data
- Payment information (all transactions use blockchain gas fees)

## 3. How We Use Your Information

- **Wallet address:** To identify your account, execute game transactions, and display your game state
- **Analytics:** To understand how players use the App and improve the experience
- **Crash data:** To identify and fix bugs
- **ENS names:** To provide human-readable wallet identification within the App and on the blockchain

## 4. Third-Party Services

We use the following third-party services:

| Service | Purpose | Data shared |
|---------|---------|-------------|
| Firebase Analytics (Google) | Usage analytics | Device ID, app events, wallet address |
| Firebase Crashlytics (Google) | Crash reporting | Crash logs, device info, wallet address |
| Firebase Cloud Messaging (Google) | Push notifications | Device push token |
| Alchemy | Blockchain RPC provider | Wallet address, transaction data |
| Pinata | IPFS storage for NFT metadata | NFT metadata (no personal data) |

These services have their own privacy policies. We do not sell or share your data for advertising purposes.

## 5. Data Retention

- **On-device data** (wallet keys, cached game state): Stored until you delete the App
- **Analytics data**: Retained per Google's Firebase data retention policy (default: 14 months)
- **Crash data**: Retained for 90 days
- **Blockchain data**: Permanent and immutable (cannot be deleted)

## 6. Data Security

Private keys are stored in your device's hardware-backed secure storage and never leave your device. Backend communications use HTTPS encryption. Blockchain transactions are signed locally on your device.

## 7. Children's Privacy

The App is not intended for children under 13. We do not knowingly collect information from children under 13.

## 8. Your Rights

Since we do not collect personal identity information, there is no personal data to request, modify, or delete from our servers. Your wallet address is a pseudonymous identifier. Blockchain data cannot be modified or deleted due to the nature of public blockchains.

You can delete all local data by uninstalling the App.

## 9. Changes to This Policy

We may update this policy from time to time. Changes will be reflected in the "Last updated" date above.

## 10. Contact

If you have questions about this privacy policy, contact us at **privacy@ownthestars.eth** or open an issue at our GitHub repository.
