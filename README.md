# ProofSender 

## Overview

**ProofSender ** is a cross-platform desktop application that allows users to verify the authenticity of messages and files by attaching unique verification keys. This ensures that the content you receive comes from the intended sender and has not been tampered with. The app operates offline, meaning no data is sent to external servers, and it stores all verification information securely on your device.

### Key Features

- **Add Contacts**: Add contacts manually or by scanning a QR code. Each contact includes a verification key.
- **Verification Keys**: Create and share verification keys tied to your device for ensuring secure communication.
- **Secure Messages**: Optionally sign messages with your verification key to ensure their authenticity.
- **Offline Mode**: Works completely offline to ensure privacy and data security.
- **PIN Protection**: Protect your key with a user-created PIN.
- **Multimedia Support**: Attach verification keys to text, audio, video, images, and other file formats.

### How It Works

- Each user generates a **private key** unique to their device, based on hardware details.
- Messages and files can be signed with this private key to generate a **verification key**.
- Contacts use the shared public verification key to ensure that messages/files have been sent by the correct person and have not been altered.

### Future Features

- Integrating verification keys with audio, video, and image files.
- Improved UI for managing large contact lists.
- Enhanced cryptographic features for improved security.

### Contributing

Welcome contributions! Please fork this repository and submit a pull request with any features or bug fixes you'd like to contribute.

### Security
- This project is in early stages of development, so please use it responsibly.
- Ensure that you keep your private key secure and do not share it with anyone.
