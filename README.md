# Scavenger Hunt App

This is a simple iOS scavenger hunt app built as part of CodePath's Intermediate iOS Development course.

Author: **Semen Kolesnykov**  
Date: **02/02/25**

---

## 📱 Overview

This app displays a list of scavenger hunt tasks. For each task, the user can:
- View details
- Attach a photo from the photo library
- See the photo location on a map using MapKit

---

## ✅ Required Features

- [x] View a list of hardcoded tasks
- [x] Tap a task to open a detail screen
- [x] Attach a photo to mark a task as completed
- [x] Display a map annotation for the photo's location
- [x] Completed tasks are visually distinguished

---

## 🌟 Stretch Features

- [ ] Open the camera to capture photos (requires physical device)
- [ ] Alternative image importing method for simulator (manually drag images into simulator library)

---

## 🎥 Walkthrough

A full walkthrough with screenshots is available in the file:  
📄 [`Semen_Kolesnykov_ScavengerHunt_Walkthrough.docx`](Semen_Kolesnykov_ScavengerHunt_Walkthrough.docx)

*If required, a video walkthrough can also be added here.*

---

## 💡 Notes

- Location metadata is only available for photos that contain geotag info.
- Use `PHPickerViewController` instead of the deprecated `UIImagePickerController` for library access.
- Tested using iPhone SE (3rd generation) simulator running iOS 17.2.

---

## 🔗 Submission Checklist

- [x] All required features are implemented
- [x] App builds and runs on simulator
- [x] Code is available in this repository
- [x] Walkthrough screenshots are included
- [ ] (Optional) Video walkthrough uploaded
