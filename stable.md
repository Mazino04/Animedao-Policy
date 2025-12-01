# 6.6.0

### 1. Fixed App Tab Layout Scrolling Issue
- **Problem:** The app tab bar layout had a "cliche" effect when scrolling, causing the interface to not apply the correct color to the tab bar
- **Fix:** Updated the tab layout behavior to provide smooth scrolling.
  - Applied Material Design guidelines for tab interactions.

### 2. Updated App Lock Interface
- **Problem:** The Previous app lock interface was not user-friendly and lacked visual feedback.  
- **Fix:** Redesigned the app lock screen for better user experience:
  - Added smooth animations for correct and incorrect PIN entries.
  - Implemented temporary message display for status updates (e.g., "Correct Passcode", "Incorrect Passcode").
  - Updated `TextView` styling to prevent text shrinking or layout interference.
  - Added proper double-tap exit logic to prevent looping back to the app lock unintentionally.
