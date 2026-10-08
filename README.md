# Hi, I'm Anastasia Shimo*** 👋

### Aspiring QA Engineer · QA Intern

I’m transitioning from technical support into software testing. I have around two years of experience handling technical support requests, reproducing issues, reviewing logs and technical information, working with tickets, and escalating complex cases to specialists.

I’m currently learning QA and programming. I also co-created **Neon Relay**, a small game published on Playgama.

🌐 Remote · Contact me via GitHub

---

## Contents

- [About me](#about-me)
- [Skills](#skills)
- [Experience](#experience)
- [Projects](#projects)
- [QA learning](#qa-learning)
- [Contact](#contact)

## About me

I’m looking for a **QA Intern / Software Quality Control Intern** role. I’d like to apply my troubleshooting and user support experience, grow my web and API testing skills, and continue learning programming.

I don’t yet have professional QA experience. My professional technical experience is in first- and second-line support.

## Skills

| Area | Skills |
|---|---|
| **QA** | Learning test cases, checklists, bug reports, and the fundamentals of web and API testing |
| **Web / API** | Basic understanding of HTTP, methods, status codes, headers, REST APIs, authentication, pagination, and WebSockets; familiar with OpenAPI |
| **Troubleshooting** | Reproducing issues, reviewing logs and technical information, working with tickets, monitoring, and metrics |
| **Programming** | JavaScript — beginner, self-studying; C++ — beginner; Python — basic knowledge |
| **Systems** | Windows — confident; Linux — basic, including command line |
| **Tools** | VS Code, Excel, Word |

### Linux CLI

I have practiced using `cd`, `rmdir`, `grep`, `find`, `mv`, `head`, `tail`, and `usermod`.

### Languages

- Russian — native
- English — B1 (intermediate)

## Experience

### Technical Support Specialist · Yandex Crowd

**May 2026 – August 2026 · Remote**

- Received and handled user requests by email and chat.
- Investigated second-line incidents and helped resolve technical and organizational issues.
- Shared user feedback with developers and product managers.
- Maintained request records in the CRM and followed internal procedures and guidelines.
- Handled up to 50 requests per shift; average KPI rating: **4.8/5**.
- Helped train two new employees.

### Technical Support Specialist · IT Company / Internet Service Provider

**May 2023 – May 2024 · Tolyatti, Russia**

- Handled requests by phone and email, advised customers, and resolved technical issues.
- Maintained request records in the CRM and followed internal procedures.
- Handled up to 50–60 requests per shift and up to 40 calls a day.
- Worked across 3–4 communication channels and processed more than 2,000 requests during the role.

### Technical Support Specialist · Grand Limited

**August 2022 – May 2023 · Tolyatti, Russia**

- Handled requests by phone and email and resolved first- and second-line incidents.
- Documented requests in the CRM and followed internal procedures.
- Handled up to 50 calls and 30 written requests per shift.
- Average service quality rating: **4.7/5**; helped train two new employees.
- Investigated an incident where a turnstile stopped reading access cards. The reader was found to be dirty; after it was cleaned, access was restored. See the [incident case](#real-world-incident-turnstile-does-not-read-access-cards).

### Healthcare Administration · Medical Administrator with Additional Duties

**January 2020 – July 2023 · Zhigulyovsk, Russia**

- Scheduled patient appointments, coordinated visitor flows, and worked with medical records and statistics.
- Helped organize reception for 40–50 patients a day and followed internal procedures.
- Learned to use a medical information system and suggested small improvements to the appointment process to reduce queues.

This experience strengthened my attention to detail, ability to stay calm under pressure, and ability to process a high volume of requests. I apply these skills in technical support by investigating issues systematically and explaining solutions clearly.

## Projects

### Neon Relay — Game

A small game co-created **50/50 with Playgama AI tools** and published on Playgama. AI was responsible for the concept and design. The project also gave me practice with JavaScript and game logic.

- **Play:** [Neon Relay on Playgama](https://playgama.ai/play/o4g5okwtvv)
- **Source code:** private

## Real-world incident: turnstile does not read access cards

**Case type:** workplace incident and troubleshooting case — not a formal commercial QA bug report.  
**System:** access control system; turnstile with a card reader.

- **Precondition:** the employee has a valid access card.
- **Steps:** approach the turnstile, present the valid card to the reader, and try to pass through.
- **Actual result:** the turnstile does not recognize the card and does not allow the employee to enter.
- **Expected result:** the reader recognizes a valid card and unlocks the turnstile.
- **Root cause:** the reader was dirty, which interfered with card reading.
- **Resolution and verification:** the reader was cleaned. After cleaning, cards were recognized and the turnstile worked normally.
- **Severity:** Medium.
- **Priority:** High if several employees are unable to enter the workplace.

This case is based on a real support incident. The steps and expected result have been structured for this portfolio; the incident was not filed as a defect in a QA tracking system.

## QA learning

I’m learning software testing fundamentals and practicing test cases, checklists, and bug reports. I plan to create a separate educational repository, `qa-practice-portfolio`, with a README, checklist, 5–7 test cases, and sample bug reports.

### Sample test scenarios

| Scenario | Check | Expected result |
|---|---|---|
| Submit a form with valid data | Fill in all required fields and submit | Data is accepted and a confirmation or next screen is displayed |
| Leave required fields empty | Submit the empty form | Submission is blocked and required fields show clear messages |
| Enter an invalid email | Enter an incorrectly formatted address | An error is shown with guidance on how to correct it |
| Add spaces around a value | Enter an email with spaces at the beginning and end | The behavior matches the application requirements |

### Bug report template

```text
Title: [Area] Brief description of the issue and condition
Environment: [OS, browser and version, device]
Preconditions: [Application state and test data]
Steps to reproduce:
1. [Step]
2. [Step]

Actual result: [What happened]
Expected result: [What should have happened according to the requirements]
Severity / priority: [According to the project's scale]
Attachments: [Screenshot, video, log, or request/response]
```

## Educational sample bug reports

The following examples were written from text-based prompts and have not been reproduced in real applications or APIs. They demonstrate how to describe steps, actual and expected results, severity, and priority. No screenshots, videos, or real request/response data are attached.

### 1. Incorrect message shown during login

- **Title:** `[Login] “User not found” message is shown when an incorrect password is entered`
- **Environment:** Windows 11, Google Chrome 155.
- **Preconditions:** the user is registered; the login page is open.
- **Steps to reproduce:**
  1. Enter the registered email address.
  2. Enter an incorrect password.
  3. Click **Log in**.
- **Actual result:** the message “User not found” is displayed.
- **Expected result:** a neutral message indicating that the email or password is incorrect is displayed.
- **Severity / priority:** Minor / Medium.
- **Attachments:** None; educational example.

### 2. Registration accepts an email without a domain

- **Title:** `[Registration] Email field accepts a value without a domain`
- **Environment:** Windows 11, Google Chrome 155.
- **Preconditions:** the new user registration form is open.
- **Steps to reproduce:**
  1. Enter `test@` in the Email field.
  2. Fill in the other required fields with valid data.
  3. Click **Register**.
- **Actual result:** the form is submitted and registration is completed.
- **Expected result:** the system validates the email format and displays an error message.
- **Severity / priority:** Major / High.
- **Attachments:** None; educational example.

### 3. Registration form can be submitted with required fields empty

- **Title:** `[Registration] Register button is enabled when required fields are empty`
- **Environment:** Windows 11, Google Chrome 155.
- **Preconditions:** the registration form is open.
- **Steps to reproduce:**
  1. Leave the required fields empty.
  2. Click **Register**.
- **Actual result:** the button is enabled, a request is sent, and the form does not prevent submission.
- **Expected result:** the button is disabled, or the system displays errors for the required fields and rejects the submission.
- **Severity / priority:** Major / High.
- **Attachments:** None; educational example.

### 4. Search is case-sensitive

- **Title:** `[Search] Search does not find a product when the query uses a different letter case`
- **Environment:** Windows 11, Google Chrome 155.
- **Preconditions:** the catalog contains the product `Wireless Mouse`.
- **Steps to reproduce:**
  1. Open the catalog.
  2. Enter `wireless mouse` in the search field.
  3. Click **Search**.
- **Actual result:** the system displays “No results found”.
- **Expected result:** search finds the product regardless of the letter case used in the query.
- **Severity / priority:** Minor / Medium.
- **Attachments:** None; educational example.

### 5. API accepts a user with an invalid email

- **Title:** `[API] POST /users returns 200 OK when an invalid email is provided`
- **Environment:** REST API, Postman.
- **Preconditions:** the API is available; the user registration endpoint is active.
- **Steps to reproduce:**
  1. Send `POST /users` with this body:

     ```json
     {
       "email": "test@",
       "password": "Test12345"
     }
     ```
  2. Check the HTTP status code and response body.
- **Actual result:** the API returns `200 OK` and creates a user with an invalid email.
- **Expected result:** the API returns `400 Bad Request` with a message indicating an invalid email format.
- **Severity / priority:** Major / High.
- **Attachments:** None; educational example, request not sent.

### 6. API returns user data without authentication

- **Title:** `[API] GET /users returns 200 OK without the required authorization header`
- **Environment:** REST API, Postman.
- **Preconditions:** the `/users` endpoint requires authentication.
- **Steps to reproduce:**
  1. Send `GET /users` without an `Authorization` header.
  2. Check the server response.
- **Actual result:** the server returns `200 OK` and user data.
- **Expected result:** the API returns `401 Unauthorized`.
- **Severity / priority:** Critical / High.
- **Attachments:** None; educational example, request not sent.

### 7. Button text is clipped when the window is resized

- **Title:** `[UI] Button text is clipped when the screen width is reduced`
- **Environment:** Windows 11, Google Chrome 155, 1280×720 display; browser window resized to 800 px wide.
- **Preconditions:** the checkout page is open.
- **Steps to reproduce:**
  1. Open the checkout page.
  2. Reduce the browser window width to 800 px.
  3. Check the **Proceed to checkout** button.
- **Actual result:** part of the button text extends beyond its boundaries and is clipped.
- **Expected result:** all button text is visible at supported screen sizes.
- **Severity / priority:** Minor / Medium.
- **Attachments:** None; educational example.

## Contact

- GitHub: [@Zesshoku](https://github.com/Zesshoku)
- Neon Relay: [Play on Playgama](https://playgama.ai/play/o4g5okwtvv)

---

*Open to QA internship opportunities and hands-on learning.*


