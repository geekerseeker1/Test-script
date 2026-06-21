Automated Signup Theorem

Overview

This project automates the signup flow for:
https://authorized-partner.vercel.app/

The automation covers all steps of the signup process without manual intervention.

---
 Tech Stack

* Language: JavaScript (Node.js)
* Framework: Playwright
* Browser: Chromium (default)

###Install Dependencies

```bash
npm install
npx playwright install
```

--

```bash
npm test
```

To view report:

```bash
npm run report
```


Test Coverage

* Navigation to signup page
* Multi-step form submission
* Input validation
* Final submission verification

Test Data

Test data is stored in:

```
test-data/userData.json
```






 Demo

A demo video (demo_video.mp4) is included showing full execution.


Report

A test report (test_report.pdf) is included with execution results.
