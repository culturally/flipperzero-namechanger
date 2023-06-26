# Flipper0 Name Changer

![License](https://img.shields.io/badge/license-MIT-blue)

Flipper0 Name Changer is a small program that cycles through a list of names and renders them on a canvas. It provides a fun way to display different names dynamically. This README provides an overview of the program and instructions for usage.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

---

## Installation

To use the Flipper0 Name Changer, follow these steps:

1. Replace the old `passport.c` file with the new one in the following directory: `applications/settings/dolphin_passport`.

2. Modify the desired names for cycling. Locate the section of code that defines the `cycleNames` array and update it with your desired names. Here is an example:

   ```c++
   const char* cycleNames[] = {
       "detective",
       "d3t3ctiv3",
       "det3ct1v3",
       "d3t3ct1ve",
       "d3t3ct!ve",
       "detect1ve",
       "d3t3ct1ve",
       "d3t3ct!ve",
       "detect!ve",
       "d3t3ctive",
       "d3t3ctiv3",
       "det3ct1ve",
       "d3t3ct!ve"
   };

## Usage

The Flipper0 Name Changer program will now cycle through the updated list of names when executed on your device. The names will be rendered on a canvas according to the code logic.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
