# Medical Bill OCR

This project extracts medicine names and their prices from medical bills using OCR (Optical Character Recognition).

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Future Expansion](#future-expansion)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project allows users to upload images of medical bills, extracts relevant information using OCR, and displays the structured data.

## Features

- Upload medical bill images
- Extract medicine names and prices using Tesseract OCR
- Display structured data from extracted text
- Compare extracted medicine costs with official prices

## Technologies Used

- **Frontend:**
  - React
  - React Router
  - Bootstrap
- **Backend:**
  - Node.js
  - Express
- **OCR:**
  - Tesseract.js
- **Database:**
  - MongoDB (for storing user data and images)

## Setup and Installation

### Prerequisites

- Node.js and npm installed
- MongoDB instance running

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/medical-bill-ocr.git
   cd medical-bill-ocr
