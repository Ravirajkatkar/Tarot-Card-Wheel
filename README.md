# Tarot Card Wheel 🎡🃏

This project is a React Native application that simulates an interactive spinning wheel where users can select and flip tarot cards. The project was created to demonstrate React Native's animation and interaction capabilities.

---
https://github.com/user-attachments/assets/d214891e-33b3-47b7-98d6-404c175abf44


https://github.com/user-attachments/assets/7b80c215-d8ec-498c-8a33-32ffa1aad69f



## Features ✨

1. **Card Flip Animation**:  
   - When the centered card is selected, it flips in the same position to reveal its back side.
   - After 1500ms, the full image of the card is displayed.

2. **Interactive Wheel**:  
   - The wheel becomes non-interactive once a card is selected.
   - After selection, the wheel reloads for the next spin.

3. **Independent Selections**:  
   - Every card selection is independent; there’s no need to display three cards at the end.
   - The wheel reloads automatically after each selection for a seamless user experience.

---

## Getting Started

> **Note**: Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions till "Creating a new application" step before proceeding.

### Step 1: Start the Metro Server

First, you will need to start **Metro**, the JavaScript _bundler_ that ships _with_ React Native.

To start Metro, run the following command from the _root_ of your React Native project:

```bash
# using npm
npm start

# OR using Yarn
yarn start
