# Changelog for v1.0.0

This document contains all notable changes to the Avesta UI Core library for version 12.2.1.

## 🚀 Features

- **New Component**: Added `useAffordabilityStepper` hook for managing multi-step affordability search flow
- **Enhancement**: Added loading state to affordability stepper

## 🐛 Bug Fixes

- Fixed state management and completion tracking in affordability stepper
- Improved step completion logic in affordability stepper
- Updated types to make `selectedStateId` and `selectedCityId` required in StepProgressData

## 📚 Documentation

- Added proper descriptions to hooks and usecases
- Improved documentation style for warnings
- Added build command in prerelease script

## 🛠 Technical Improvements

- Refactored state handling in useAffordabilityStepper
- Streamlined state management for better performance

## Detailed Changes

### March 25-27, 2023

- **[fix]** Update package dependencies (`80cb8be`)
- **[chore]** Release version 12.2.1 (`ddaa27b`)
- **[fix]** Add descriptions to hooks and usecases (`8c63aa3`)
- **[fix]** Add loading state in useAffordabilityStepper (`3c78457`)
- **[fix]** Streamline state management and step completion updates (`623c04c`)

### March 21-24, 2023

- **[fix]** Enhance step completion logic and state saving (`cd9d1ce`)
- **[fix]** Remove redundant comments (`f6dd315`)
- **[fix]** Refactor useAffordabilityStepper to improve state handling (`67467bc`)
- **[fix]** Change selectedStateId and selectedCityId to non-optional (`faa4a87`)
- **[fix]** Update StepProgressData to include currentSubStep (`1beae80`)
- **[fix]** Improve doc style for warnings (`50b83c6`)
- **[fix]** Add build command in prerelease (`d148cf8`) 



# Changelog for v1.0.2

All notable changes to this project will be documented in this file.

## Features

### New Components
- Added affordability search stepper usecase ([`88fea8a`](https://github.com/realestateview/avesta-ui-core/commit/88fea8a))

### Enhancements
- Added loading in the useAffordabilityStepper ([`3c78457`](https://github.com/realestateview/avesta-ui-core/commit/3c78457))

## Bug Fixes

### Types
- Changed selectedStateId and selectedCityId to non-optional in StepProgressData ([`faa4a87`](https://github.com/realestateview/avesta-ui-core/commit/faa4a87))
- Updated StepProgressData to include currentSubStep and selectedCityId ([`1beae80`](https://github.com/realestateview/avesta-ui-core/commit/1beae80))

### State Management
- Streamlined state management and step completion updates ([`623c04c`](https://github.com/realestateview/avesta-ui-core/commit/623c04c))
- Enhanced step completion logic and state saving ([`cd9d1ce`](https://github.com/realestateview/avesta-ui-core/commit/cd9d1ce))
- Removed redundant comments ([`f6dd315`](https://github.com/realestateview/avesta-ui-core/commit/f6dd315))
- Refactored useAffordabilityStepper to improve state handling ([`67467bc`](https://github.com/realestateview/avesta-ui-core/commit/67467bc))
- State refactoring completed ([`ad71783`](https://github.com/realestateview/avesta-ui-core/commit/ad71783))
- Changed the states into one ([`83fd165`](https://github.com/realestateview/avesta-ui-core/commit/83fd165))

## Documentation

### Improvements
- Added description to hook and usecase ([`8c63aa3`](https://github.com/realestateview/avesta-ui-core/commit/8c63aa3))
- Added caution message in usecase and hooks ([`3be7a43`](https://github.com/realestateview/avesta-ui-core/commit/3be7a43))
- Removed extra line in hooks argument section ([`75b890e`](https://github.com/realestateview/avesta-ui-core/commit/75b890e))
- Removed property table in usecases ([`9865bf0`](https://github.com/realestateview/avesta-ui-core/commit/9865bf0))
- Added description in return property type for hooks ([`faf44a3`](https://github.com/realestateview/avesta-ui-core/commit/faf44a3))
- Improved doc style for warnings ([`50b83c6`](https://github.com/realestateview/avesta-ui-core/commit/50b83c6))

### Build System
- Added build command in prerelease ([`d148cf8`](https://github.com/realestateview/avesta-ui-core/commit/d148cf8))
- Updated package ([`80cb8be`](https://github.com/realestateview/avesta-ui-core/commit/80cb8be))

## Other Changes

### Chores
- Released version 12.2.1 ([`ddaa27b`](https://github.com/realestateview/avesta-ui-core/commit/ddaa27b))
- Released version 12.2.0 ([`21cd124`](https://github.com/realestateview/avesta-ui-core/commit/21cd124)) 
