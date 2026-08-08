# Vision Fox Privacy Policy

**Last updated:** August 7, 2026

Vision Fox (“Vision Fox,” “we,” “us”) is a visual assistant that lets you capture or select an image, ask a question, receive an AI-generated analysis, and optionally save or share the result. This policy explains what data Vision Fox processes, how it is used, and the choices you have.

---

## Summary

- **Camera and selected images:** Vision Fox processes photos you capture in the app or images and screenshots you deliberately select.
- **AI processing:** When you tap **Analyze**, the selected image, your request, and any relevant on-device OCR text are sent to **Google Gemini through Firebase AI Logic**.
- **Follow-up processing:** When you ask a follow-up, Vision Fox may send the same image, the earlier analysis, your follow-up question, and a limited recent conversation history to Gemini.
- **On-device OCR:** For text-focused requests, Apple Vision may read text from the image on your device. Relevant OCR text may then be included in the Gemini request.
- **Local history is optional:** Vision Fox saves a scan only when you tap **Save**. Saved history remains on your device.
- **No accounts, no ads, and no cross-app tracking.**

---

## Data Vision Fox processes

### 1) Camera access

Vision Fox requests camera permission so you can capture an image for analysis.

**Purpose:** To display the camera preview and capture the photo you choose to analyze.

You can use an existing photo or screenshot instead of capturing a new image.

### 2) User-selected photos and screenshots

Vision Fox uses Apple’s photo picker to let you deliberately select an image or screenshot.

**Purpose:** To analyze the selected image.

Vision Fox does not require unrestricted access to your entire photo library for this picker-based flow.

### 3) Images submitted for AI analysis

When you tap **Analyze**, Vision Fox prepares the selected image for upload and sends it to Google Gemini through Firebase AI Logic.

The submitted image may contain personal, sensitive, confidential, or identifying information depending on what you capture or select. Only submit images you are comfortable sending to the AI provider.

**Purpose:** To generate observations, interpretations, uncertainty, next actions, extracted text, and suggested follow-up questions.

### 4) Face Data

Vision Fox does not perform facial recognition, biometric identification, face matching, Face ID authentication, or create face templates, face embeddings, face meshes, facial landmark data, or user profiles based on a person’s face.

A photo or screenshot deliberately captured or selected by the user may contain a human face. When the user reviews that image and taps **Analyze**, the complete selected image, including any visible face contained in the image, may be sent to Google Gemini through Firebase AI Logic solely to perform the visual analysis requested by the user.

Vision Fox does not separately extract or store biometric face data. Face information is not used for authentication, advertising, marketing, tracking, profiling, or identifying anonymous users.

If the user taps **Save**, Vision Fox may store a compressed thumbnail of the selected image locally on the user’s device. If the original image contains a face, the thumbnail may also contain that face. Saved thumbnails remain only on the user’s device until the saved scan is deleted, multiple scans are deleted through History, or the app is deleted.

Images submitted to Google Gemini, including images that may contain faces, are processed by Google solely to provide the requested AI functionality and according to Google’s applicable data-retention and abuse-monitoring policies. Google currently states that Gemini API prompts, contextual information, and outputs may be retained for up to 55 days for abuse monitoring.

Vision Fox does not sell face data or share it with advertising platforms, analytics providers, data brokers, or information resellers.

### 5) Requests and questions

Vision Fox processes:

- the selected analysis mode;
- the app’s default question for that mode;
- any custom request you type; and
- follow-up questions you submit.

**Purpose:** To understand what you want Vision Fox to do and tailor the response.

### 6) On-device OCR text

For Extract mode and some text-focused Custom requests, Vision Fox may use Apple Vision to recognize visible text locally on your device.

Recognized text may include names, dates, amounts, phone numbers, instructions, labels, receipt content, document text, or other text visible in the selected image.

Relevant OCR text may be included with the image and request sent to Gemini. Very long OCR text may be shortened before transmission.

**Purpose:** To improve text extraction and help Gemini interpret readable content more accurately.

### 7) AI-generated analysis and follow-up conversation

Gemini may return:

- a title and summary;
- visible observations;
- possible interpretations;
- risks or uncertainty;
- recommended next actions;
- extracted text;
- suggested follow-up questions; and
- answers to follow-up questions.

For a follow-up request, Vision Fox may send the selected image, the earlier analysis, the current follow-up question, and a limited recent conversation history to Gemini. A fallback request may use text context without resending the image.

**Purpose:** To continue answering questions about the same image.

### 8) Optional saved history

Vision Fox saves a history record only when you tap **Save**.

A saved record may include:

- a compressed thumbnail of the image;
- selected mode;
- original request;
- analysis title and summary;
- structured analysis;
- date and time; and
- pinned or renamed status.

Saved records are stored locally on your device using Apple SwiftData.

The live follow-up conversation is not preserved in saved history.

### 9) Sharing

If you tap **Share**, Vision Fox opens the iOS share sheet with the generated report text.

**Purpose:** To let you send or save the report through a destination you select.

Any destination app or service you choose has its own privacy practices.

### 10) App security and configuration data

Vision Fox uses:

- **Firebase App Check**, together with Apple App Attest or DeviceCheck, to help confirm that requests come from the authentic app; and
- **Firebase Remote Config** to retrieve technical settings such as the current model name, output limit, and prompt version.

These services may process technical app, device-integrity, attestation, token, network, and configuration-request information needed to secure and configure the service. They are not used by Vision Fox for advertising or cross-app tracking.

---

## What Vision Fox does not collect

Vision Fox does not:

- require an account or login;
- operate its own user profile database;
- request microphone or speech-recognition access;
- request contacts;
- request precise location;
- connect to email, calendar, banking, social-media, or CRM accounts;
- run advertising;
- sell personal data; or
- track users across other apps or websites for advertising.

---

## Third-party processing and equal protection

Vision Fox uses third-party services only to provide and secure app functionality:

- **Google Gemini through Firebase AI Logic:** Processes submitted images, requests, OCR context, prior analysis, and follow-up context to generate AI responses.
- **Google Firebase App Check and Remote Config:** Protect and configure Firebase-connected services.
- **Apple:** Provides camera permission controls, the photo picker, on-device Vision OCR, SwiftData storage, the share sheet, App Attest, and DeviceCheck.

Any third party that processes user data for Vision Fox provides the **same or equal protection of user data** as stated in this policy and as required by Apple’s App Review Guidelines.

---

## Data retention and deletion

### Images during the current session

Captured or selected images are held by the app as needed for the current analysis and follow-up session.

Vision Fox does not add the image to saved history unless you tap **Save**. When saved, Vision Fox stores a compressed thumbnail, not the original full-resolution image, with the local history record.

### Local saved history

Saved scans remain on your device until you:

- delete an individual scan;
- select and delete multiple scans; or
- delete the app.

You may also rename, pin, unpin, open, or share a saved scan.

Deleting the app removes locally stored Vision Fox data from the device, subject to normal iOS backup and restore behavior.

### Live follow-up conversation

The live follow-up conversation is held during the active session and is not included in saved history.

### Google Gemini

Google states that Gemini API prompts, contextual information, and outputs may be retained for up to **55 days** for abuse monitoring. For Vision Fox, this may include submitted images, typed requests, OCR context, prior analysis, follow-up questions, recent conversation context, and generated responses.

Vision Fox cannot directly delete data retained by Google for abuse monitoring. Retention and deletion of that data are governed by Google’s applicable terms and policies.

### Firebase App Check and Remote Config

App Check attestation information and tokens are processed according to Google Firebase and the applicable Apple attestation provider’s policies. Remote Config values and configuration requests are processed according to Firebase’s policies.

Vision Fox does not use these services to store your saved scan history.

---

## Your choices and consent

### Camera permission

You may deny or revoke camera access through iOS Settings. If camera access is unavailable, you may still select an existing image or screenshot through the system photo picker.

### Photo selection

Vision Fox processes only the photo or screenshot you deliberately select for the current workflow.

### AI processing consent

Tapping **Analyze** requests AI processing of the selected image and accompanying request or OCR context by Google Gemini through Firebase AI Logic.

Tapping a suggested follow-up or sending a typed follow-up requests additional AI processing using the same image and relevant conversation context.

You can stop future AI processing by not tapping **Analyze** and not submitting follow-up questions.

### Delete local data

You can delete saved scans individually or in a multi-selection from History. You can also delete the app to remove locally stored Vision Fox data.

### Third-party deletion requests

For information retained by Google, Firebase, Apple, or a destination selected from the share sheet, retention and deletion requests are governed by that provider’s policies.

---

## Sensitive information

Images and OCR text can contain sensitive information. Avoid submitting content such as:

- passwords, authentication codes, or private keys;
- complete payment-card or bank-account details;
- medical records;
- government identification numbers;
- confidential business documents;
- private information about another person; or
- images you do not have permission to process.

Vision Fox’s responses are informational and may be incomplete or incorrect. Do not rely on Vision Fox as a substitute for qualified medical, legal, financial, repair, safety, or other professional advice.

---

## Security

Vision Fox minimizes local storage and uses Firebase App Check to help protect AI service requests. Data submitted for AI analysis is transmitted to the configured third-party provider to perform the requested function.

No transmission or storage method can be guaranteed to be completely secure.

---

## Children’s privacy

Vision Fox is not directed to children under 13, and we do not knowingly collect personal information from children under 13.

---

## Changes to this policy

We may update this policy from time to time. The “Last updated” date above reflects the latest version.

---

## Contact

For questions or privacy requests, contact:

**Email:** Simon.Yam227@gmail.com
