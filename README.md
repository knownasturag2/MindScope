# MindScope_Full-stack

# MindScope – Smart Mental Health Screening Platform
MindScope is a mental-health awareness and self-assessment web platform designed to help users understand their emotional well-being through simple screenings, mood tracking, and supportive resources. The system focuses on accessibility, early detection, and stigma-free self-care.
# Features

# 1. User Authentication
* Secure login system
* Session handling and redirect verification
* Protection against unauthorized access
# 2. Navigation Flow
* Fully functional menu:
   Home → Dashboard → Screening → Mood Tracker → Chatbot → Logout
* Smooth, consistent navigation across modules

# 3. Screening Module

* PHQ-9 depression screening
* Other mental-health screening forms (as designed)
* Reliable form loading, input handling, and submission
 # 4. Mood Tracking
* Daily mood logging using selectable mood options
* Saves responses automatically
* Visual display of logged moods
 # 5. AI Chatbot
* Supports real-time conversation
* Processes user messages accurately
* Displays both user and bot responses correctly
 # 6. System Stability
* Correct page redirections
* Consistent and predictable URL behaviors
* Maintains user session across components
  # Testing Objectives
* Validate login authentication
* Test navigation between all core modules
* Ensure screening forms function properly
* Confirm mood tracking data is stored and displayed
* Verify chatbot message flow
* Check redirections and error-free user journey
* Run automated end-to-end workflow tests
  # Tools & Environment
 Technology Used for Automation:
 Python
 Selenium WebDriver
 Locators Applied:
* `By.ID`
* `By.NAME`
* `By.XPATH`
* `By.CSS_SELECTOR`
  # Selenium Test Script Overview
# Approach

* Full end-to-end automation of the user journey
* Covers
* Login → Dashboard → Screening → Mood Tracker → Chatbot → Logout

# Framework Highlights
* Exception handling for:
  * `TimeoutException`
  * `ElementClickInterceptedException`
* Screenshot capture after key operations
* Implicit waits + `scrollIntoView()` for dynamically loaded elements
* Console logs with ✓ / ✗ status indicators
* Designed to simulate real user behavior
  # Test Execution & Results
* All modules were automated successfully
* User workflow executed smoothly end-to-end
* No major errors encountered
* Visual screenshots captured for verification

