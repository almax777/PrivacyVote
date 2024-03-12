# AleoMail

## Project Overview

AleoMail is a groundbreaking messaging application that leverages the power of the Aleo platform to provide end-to-end encrypted communication with an additional layer of privacy through zero-knowledge proofs (ZKPs). It's designed to enable users to send messages securely and privately, ensuring that only the intended recipients can decrypt and read the messages, while also allowing senders to prove the integrity and origin of their messages without revealing any sensitive information.

## Authors
Discord: almax_777

## Getting Started

This section will guide you through the setup process to get AleoMail running on your machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:
- Rust programming language
- Aleo CLI

Follow the official Aleo documentation to install these prerequisites.

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/YourUsername/AleoMail.git
cd AleoMail

2. **Build the project:**
```aleo build
```
This will compile the AleoMail application and prepare it for running.

### Usage
To use AleoMail for sending a secure message, follow these steps:

1. **Generate an Aleo account (if you don't already have one):**
   ```aleo account new
```
2. **Send a message:**
``` aleo run send_message --account [YOUR_ACCOUNT] --recipient [RECIPIENT_ACCOUNT] --message "Your secure message here"
```
3. **Receive a message:**
   ```aleo run receive_message --account [RECIPIENT_ACCOUNT]
```
### Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Please refer to CONTRIBUTING.md for our contribution guidelines.

### Versioning
For transparency into our release cycle and to maintain backward compatibility, AleoMail is maintained under the Semantic Versioning guidelines. Sometimes we screw up, but we adhere to those rules whenever possible.

