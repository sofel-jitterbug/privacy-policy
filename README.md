# Privacy Policy for Library Robot Application

This repository contains the privacy policy and documentation for a jitterbug-takephoto.

## 📚 About the App

This application is designed to assist library visitors by enabling simple conversations and photo-taking through a robot.

Each library is provided with a dedicated Google account. When a library visitor agrees to have their photo taken, the robot captures the image and uploads it to Google Drive using the `drive.file` scope. 
A QR code containing the download link is then generated and shown to the visitor.

The visitor can scan the QR code with their smartphone or device to download the photo. Once the download is complete, the file is promptly deleted from Google Drive to ensure privacy.

- The app only accesses files it uploads itself.
- It does **not** access other Drive contents.
- No data is stored on external servers or shared with third parties.

## 🔗 Privacy Policy

The full privacy policy is available here:  
👉 [View Privacy Policy](https://github.com/sofel-jitterbug/privacy-policy/)

## 🛡️ Permissions

This app uses the following Google OAuth scope:

- `https://www.googleapis.com/auth/drive.file`  
  _(Used only to upload and delete photos captured by the robot.)_

## 🛠️ Intended Use

This app is designed exclusively for use in physical library environments and is not distributed for personal use.

## 📬 Contact

For questions or inquiries, please contact:  `sofel.jitterbug@gmail.com`
