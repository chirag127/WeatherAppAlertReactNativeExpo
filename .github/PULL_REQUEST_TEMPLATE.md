# Pull Request Template

## 🚀 PR Checklist

Please review the following checklist before submitting your Pull Request:

- [ ] **Self-Review:** I have reviewed my own code and made sure it adheres to the project's coding standards.
- [ ] **Branch Name:** My branch name is descriptive and follows the convention (e.g., `feat/add-user-authentication`, `fix/login-bug`).
- [ ] **Commits:** My commit messages are clear, concise, and follow conventional commit standards (e.g., `feat:`, `fix:`, `chore:`).
- [ ] **Code Linting/Formatting:** My code passes all linting and formatting checks (Biome/Ruff, etc.).
- [ ] **Tests:** I have added or updated relevant unit/integration tests, and they all pass.
- [ ] **Documentation:** I have updated any relevant documentation (README, AGENTS.md, etc.) if my changes affect it.
- [ ] **CI/CD:** My changes do not break the Continuous Integration pipeline.
- [ ] **Security:** My changes do not introduce any new security vulnerabilities.

## ✨ Description

Provide a concise and clear description of the changes introduced in this Pull Request. What problem does it solve? What new functionality does it add?

## 📝 Related Issues

If this PR closes or relates to any issues, please link them here. Use keywords like `closes`, `fixes`, `resolves` to automatically close issues when the PR is merged.

Example:
`closes #123`
`fixes #456`

## 🧪 Testing

Describe the testing performed for these changes. Include:

*   **Unit Tests:** Which components or functions were covered by new or updated unit tests?
*   **Integration Tests:** Were any integration tests added or modified?
*   **Manual Testing:** Steps taken to manually verify the changes, especially for UI/UX related modifications.

## 🔗 Related Links

*   **Repository:** [AuraWeather-RealTime-Forecasting-Mobile-App](https://github.com/chirag127/AuraWeather-RealTime-Forecasting-Mobile-App)
*   **CI Workflow:** [GitHub Actions](https://github.com/chirag127/AuraWeather-RealTime-Forecasting-Mobile-App/actions)

---
## 🤖 AI Agent Directives Snapshot

This Pull Request adheres to the following AI Agent Directives, ensuring alignment with the project's core architecture and development standards as defined in AGENTS.md.

<details>
<summary>View Agent Directives</summary>

This repository, `AuraWeather-RealTime-Forecasting-Mobile-App`, is a **Cross-Platform Mobile Application** built with **React Native** and **Expo**. The development environment prioritizes performance, maintainability, and developer experience.

### 1. Core Technology Stack (Late 2025 Standards)

*   **Language:** TypeScript 6.x (Strict Mode Enabled).
*   **Framework:** React Native (Latest Stable). 
*   **Environment:** Expo (Latest Stable) for streamlined development, build, and deployment.
*   **State Management:** Signals (Standardized) or Zustand for efficient and predictable state management.
*   **Styling:** Tailwind CSS (v4+) via native-wind or similar for rapid UI development with a utility-first approach.
*   **Navigation:** React Navigation (Latest Stable).
*   **API Client:** Axios or native `fetch` with interceptors for robust network requests.

### 2. Architectural Patterns

*   **Modular Design:** Features are organized into independent, reusable modules (e.g., `features/weather`, `features/location`, `features/alerts`).
*   **Component Architecture:** Atomic Design principles are encouraged for UI components.
*   **SOLID Principles:** Applied rigorously to ensure maintainable and scalable code.
*   **DRY (Don't Repeat Yourself):** Encouraged through abstraction and utility functions.
*   **YAGNI (You Ain't Gonna Need It):** Avoid premature optimization or over-engineering.

### 3. Development Tooling & Verification

*   **Package Management:** `npm` or `yarn` (consistent choice enforced via project tooling).
*   **Linting & Formatting:** Biome (Latest) for ultra-fast linting, formatting, and code analysis across TypeScript and React Native.
*   **Testing Framework:** Vitest (Latest) for fast unit and integration tests. Playwright (Latest) for E2E testing on emulators/simulators.
*   **Type Safety:** Strict TypeScript configuration (`tsconfig.json`) is mandatory.

### 4. Build & Deployment

*   **Development Builds:** Expo Go for rapid iteration.
*   **Production Builds:** `eas build` for native application builds (iOS/Android).
*   **CI/CD:** GitHub Actions will be configured for automated testing and build processes. (See `.github/workflows/ci.yml`)

### 5. API Integration

*   **Weather API:** Integration with a reliable weather API (e.g., OpenWeatherMap, AccuWeather, WeatherAPI.com). API keys must be managed securely (e.g., via environment variables, not hardcoded).
*   **Location Services:** Native location APIs via Expo Location module.

### 6. Security Mandates

*   **Data Privacy:** Adhere to all relevant data privacy regulations (GDPR, CCPA, etc.). Sensitive user data should be handled with utmost care.
*   **API Key Security:** Never commit API keys directly into the repository. Use environment variables or secure secrets management.
*   **Dependency Security:** Regularly scan dependencies for vulnerabilities.

</details>

---