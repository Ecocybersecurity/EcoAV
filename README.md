# EcoAV

Free and open source anti-malware for Windows using machine learning.

- [<img src="https://2.bp.blogspot.com/-1FWyKR1ezxY/V7q3bPQYjLI/AAAAAAAAX5s/NvwFsE-G1i4TyXJ8PmINdVt__cUmmNczwCLcB/w1200-h630-p-k-no-nu/download.png" width="200"  alt="Get it  " />](https://1drv.ms/u/s!AkIjhtUmdMQ9cTPiVjQAa633fMM?e=VAMqWl "Get it Now") 
## About
EcoAV is an attempt to detect malwares on Windows by utilizing machine learning approach.
## Features
- Real time scanning
- On device inference
- Lightweight
- 100% free and no ads
## How it works?
EcoAv uses permissions and intent-filters to detect malicious applications. While scanning, it loads the machine learning model and extracts permissions and intents from the installed applications on the user's machine. These extracted features are then fed to the machine learning model in the form of a vector. The machine learning model returns a prediction score between 0 and 1 that denote the degree of maliciousness of the scanned application. We use this score to classify the scanned app into one of the following categories:
  1. Goodware: The prediction score is less than 0.5
2. Risky: Prediction score between 0.5 and 0.75
3. Malware: Prediction score is greater than 0.75
4. Unknown: If EcoAV is unable to extract permissions and intents from an app, then that app is labelled as 'Unknown'
  ## Open Source License
Unless explicitly stated otherwise all files in this repository are licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0-standalone.html). 
    EcoAV - Anti-malware for Windows using machine learning
    Copyright (C) 2020 EcoCybersecurity.
    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.
  
  This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
An unmodified copy of the above license text must be included in all forks.
