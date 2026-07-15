[![License: OML v1.4](https://img.shields.io/badge/License-Osy_Matrix_v1.4-4B0082?style=for-the-badge&logo=shield&logoColor=white)](./LICENSE)

# The Osy Matrix License (OML)

The GNU GPL was written for the 1980s. The AGPLv3 was written in 2007. The tech landscape has fundamentally changed, and open-source labor is currently being exploited by loopholes that older licenses never anticipated.

The **Osy Matrix License (OML)** is an experimental, modern "copyleft-on-steroids" protocol designed for the AI and IoT era. It is built to close the SaaS cloud loophole, enforce true hardware Right-to-Repair, and protect developer labor from closed-source AI scraping.

## 🛡️ The Core Directives
1. **The Matrix Exchange:** Standard strong copyleft. If you distribute it, you share the source.
2. **The Cloud Trigger:** SaaS and Network Interaction count as distribution. (Closes the AWS/Cloud loophole).
3. **The Hardware Ally:** If embedded in physical/IoT devices, you *must* provide the cryptographic signing keys and Secure Boot tokens to the user. (Anti-Tivoization 2.0).
4. **The AI Boundary:** You may use this code to train AI. However, by ingesting it, you enter a contractual agreement: if you deploy a commercial model trained on this code, the model's weights and architecture must be open-sourced under the OML.
5. **The Grace Period:** A 30-day cure period for honest administrative mistakes to prevent weaponized litigation against indie devs.
6. **Home-Court Advantage:** Jurisdiction defaults to Delaware (or the copyright holder's sole discretion) with a "Loser Pays" attorney fee clause.

## ⚖️ How to Apply the OML to Your Project
To apply the Osy Matrix License to your project, create a `LICENSE.md` file in your repository and paste the [full OML v1.4 text](./LICENSE.md) into it. 

Then, add this boilerplate header to the top of your source code files:

```text
<one line to give the program's name and a brief idea of what it does.>
Copyright (C) <year>  <name of author>

This program is free software: you can redistribute it and/or modify
it under the terms of the Osy Matrix License (OML) as published by
the author, either version 1.4 of the License, or (at your option) 
any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
Osy Matrix License for more details.
