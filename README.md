# Tesla TO-DO List

A personal C++/Qt project exploring a task list in a Tesla-style infotainment interface.

## Goal

I built this project to get hands-on experience with an infotainment-style interface and connect a simple task list to persistent storage.

## Implementation

The application uses a QML interface with a C++ backend. The `System` controller creates a local SQLite database through `QSqlDatabase` and provides functions to load, add, and delete tasks.

**Tools:** C++, Qt, QML, SQLite

## Design Choices

Local storage keeps tasks available between sessions. The task-list logic sits in the C++ controller, while QML handles the interface.

## Demo

[![Tesla TO-DO List demo](https://img.youtube.com/vi/1lpmXSvHT2g/0.jpg)](https://www.youtube.com/watch?v=1lpmXSvHT2g)

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1-qvX5sgqVHgOTvnw5n9ALN0hOJimTywd" alt="Tesla Infotainment" width="400"/>
  <img src="https://drive.google.com/uc?export=view&id=1tZAoCs--5HrF_ZGXRSsyHHwOnRElNKIS" alt="Second Logo" width="300"/>
  <img src="https://drive.google.com/uc?export=view&id=1UniQPPduOcKh8h8CVTd4Yq3qtGhYwfAD" alt="Third Logo" width="250"/>
</p>

## Scope

This repository presents a personal interface prototype. It does not document deployment into a production Tesla infotainment system. Mobile synchronization and user accounts were ideas for future work.
