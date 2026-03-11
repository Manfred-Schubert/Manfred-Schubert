# iOS & macOS Development Portfolio

Welcome! I am a software developer focused on building high-performance, user-centric applications for the Apple ecosystem. This repository serves as a showcase of my published work in the App Store.

While the source code for these projects is proprietary, I have provided technical overviews and architecture highlights for each application below.

---

## MetroPacer | Running App for Apple Watch and iPhone
*The ultimate running companion for Apple Watch & iPhone.*
<p align="center">
  <img src="https://github.com/user-attachments/assets/acdffffd-d49e-486a-a9ce-ba3a36d51955" width="150" alt="MetroPacer Apple Watch" hspace="50">
  <img src="https://github.com/user-attachments/assets/906575ae-ee7f-4d54-9676-4b3dc17efd6b" width="200" alt="MetroPacer iPhone" hspace="50">
</p>

**MetroPacer** is an "offline-first" fitness application designed to provide real-time tracking of pace, cadence, heart rate, and distance. It allows runners to hit specific goals through guided workouts with spoken feedback.

### Technical Highlights:
* **Offline-First Architecture:** Designed to handle data reliably even in areas with poor cellular connectivity, ensuring no workout data is lost.
* **Core Data & Synchronization:** Leverages Core Data for local persistence, with a robust sync engine to bridge data between the Apple Watch companion and the iPhone app.
* **Reactive UI:** Built using **Combine** to handle real-time sensor data streams and provide immediate UI feedback during high-intensity runs.
* **HealthKit Integration:** Seamlessly reads and writes health metrics while respecting user privacy and system permissions.

**[metropacer.com](http://metropacer.com/) | [View on App Store](https://apps.apple.com/us/app/metropacer/id6749025808)**

---

## Diffraction | Image Editor
*Professional Image Editor for macOS.*
<p align="center">
<img width="800" alt="diffraction-main-window-brush-tool-2-1184" src="https://github.com/user-attachments/assets/b340ffd7-6479-4e18-b302-b66f120e1843" alt="Diffraction"/>
</p>

**Diffraction** is a comprehensive image editing suite tailored for creative professionals. It features a custom image processing core capable of handling complex compositions with layers, masks, and AI-driven tools.

### Technical Highlights:
* **Custom Framework Structure:** Built with a modular architecture, separating the UI layer from the **ImageCore** (processing) and **IO** (file management) modules.
* **Advanced Image Processing:** Implements classic and modern image processing algorithms, including color correction (Curves, Levels), blurring, and distortion filters.
* **AI-Powered Tools:** Features intelligent subject masking and spot removal, utilizing machine learning to simplify complex retouching tasks.
* **High Performance & Stability:** Includes an extensive suite of **Unit Tests** for core modules to ensure stability when processing large, multi-layered PSD and HEIC documents.
* **Apple Silicon Optimized:** Fully optimized for M1/M2/M3 chips to ensure near-instant rendering of effects.

**[schubert-it.com/diffraction](https://www.schubert-it.com/diffraction/)** | **[View on Mac App Store](https://apps.apple.com/app/diffraction-image-editor/id1544476110)**

---

## Technical Skills
* **Languages:** Swift, Objective-C
* **Frameworks:** SwiftUI, AppKit, UIKit, WatchKit, Combine, Core Data, HealthKit, Core Image
* **Tools:** Xcode, Git, XCTest (Unit & UI Testing)
* **Focus:** Clean Architecture (MVVM/MVC), Performance Optimization, User Privacy

---
*Contact: [manfred@schubert-it.de](mailto:manfred@schubert-it.de)*
