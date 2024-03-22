# WMO Code to Emoji Converter

   This module provides a function to convert WMO (World Meteorological Organization) codes to corresponding emoji.

   ## Installation

   ```
   npm install wmo-emoji
   ```

   ## Usage

   ```javascript
   import { wmoCodeToEmoji } from 'wmo-emoji';

   console.log(wmoCodeToEmoji(0));  // Output: ☀️
   console.log(wmoCodeToEmoji(3));  // Output: ☁️
   console.log(wmoCodeToEmoji(61)); // Output: 🌧️
   console.log(wmoCodeToEmoji(99)); // Output: ⛈️
   console.log(wmoCodeToEmoji(100)); // Output: ❓
   ```

   ## License

   This module is released under the MIT License.