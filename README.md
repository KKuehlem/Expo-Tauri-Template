[![runs with Expo Go](https://img.shields.io/badge/Runs%20with%20Expo%20Go-4630EB.svg?style=flat-square&logo=EXPO&labelColor=f3f3f3&logoColor=000)](https://expo.dev/client)
[![Tauri](https://img.shields.io/badge/Runs%20with-Tauri-blue)](https://v2.tauri.app/)
[![build-tauri](https://github.com/KKuehlem/Expo-Tauri-Template/actions/workflows/BuildTauri.yml/badge.svg)](https://github.com/KKuehlem/Expo-Tauri-Template/actions/workflows/BuildTauri.yml)

# Expo + Tauri Template
A simple template based on the [Expo TypeScript](https://docs.expo.dev/guides/typescript/) template with desktop builds using [Tauri](https://v2.tauri.app/) and building pipelines for the desktop variants.

# Development
Use `npm start` to start Expo CLI and `npm run desktop` to start Tauri.

# Building
- For Web: `npm run build-web`
- For Desktop (Windows / Linux / MacOS): `npm run build-desktop`
- Apps can be build using `eas`

# Pipelines
When code is pushed to `main`, the installers and executables will be built for Windows, Linux and MacOS using GitHub Actions.
