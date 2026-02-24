# Chef Claude: Advanced AI-Driven Gastronomic Synthesis

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-19-blue.svg)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-7.1-646CFF.svg)](https://vitejs.dev/)

Chef Claude is an enterprise-grade web application designed to optimize culinary outputs through the integration of Large Language Models (LLMs). The platform serves as a sophisticated interface between fragmented household inventories and structured, professional-grade recipe documentation.

---

## Table of Contents
- [Executive Summary](#executive-summary)
- [System Capabilities](#system-capabilities)
- [Technical Architecture](#technical-architecture)
- [Visual Documentation](#visual-documentation)
- [Installation & Deployment](#installation--deployment)
- [Technical Specification](#technical-specification)
- [Contributing](#contributing)

---

## Executive Summary
Chef Claude addresses the challenge of resource-constrained meal planning. By utilizing a multi-agent AI architecture (Mistral-7B and Claude-3), the system processes natural language ingredient lists to synthesize unique, instructionally dense recipes. The application focuses on reducing cognitive overhead for the user while maximizing the utility of existing gastronomic resources.

## System Capabilities
*   **Predictive Recipe Synthesis**: Dynamically generates recipes tailored to specific ingredient constraints.
*   **Stochastic Output Variance**: Ensures diverse culinary suggestions even with identical input parameters.
*   **Semantic Rendering**: Implements high-fidelity Markdown parsing for professional instructional formatting.
*   **Reactive UI/UX**: Features a highly responsive state-management system and automated viewport optimization (smooth-scroll logic).

## Technical Architecture

The application is built on a modular, component-based framework designed for scalability and high-performance rendering.

| Layer | Technology | Function |
| :--- | :--- | :--- |
| **View Layer** | React 19 / Vite | Component architecture and optimized build-cycle |
| **Logic Layer** | Redux-style State Management | Handling asynchronous data flows and UI state |
| **AI Engine** | Anthropic / Mistral (HF) | Large Language Model processing and inference |
| **Style Layer** | Modular CSS / Bootstrap 5 | Responsive design and consistent visual tokens |

---

## Visual Documentation

### I. Primary Portal Interface
A minimalist landing experience designed to minimize user friction during the initial engagement phase.

<p align="center">
  <img src="src/assets/project_screenshots/Screenshot (1227).png" width="90%" alt="Landing Interface" />
</p>

### II. Data Entry & Validation
User-driven ingredient indexing featuring real-time state synchronization.

<p align="center">
  <img src="src/assets/project_screenshots/Screenshot (1228).png" width="90%" alt="Input Interface" />
</p>

### III. Inventory Aggregation
Structural representation of gathered data points prior to synthesis.

<p align="center">
  <img src="src/assets/project_screenshots/Screenshot (1229).png" width="90%" alt="Inventory View" />
</p>

### IV. Inference & Synthesis Engine
The transitional state where LLM models process the aggregated ingredient vector.

<p align="center">
  <img src="src/assets/project_screenshots/Screenshot (1230).png" width="90%" alt="Processing State" />
</p>

### V. Culinary Output Analysis (Phase A)
Rendering of the primary recipe output with full semantic hierarchy.

<p align="center">
  <img src="src/assets/project_screenshots/Screenshot (1231).png" width="90%" alt="Recipe Output 1" />
</p>

### VI. Culinary Output Analysis (Phase B)
Demonstration of system variance and alternate recipe structures.

<p align="center">
  <img src="src/assets/project_screenshots/Screenshot (1232).png" width="90%" alt="Recipe Output 2" />
</p>

---

## Installation & Deployment

### Environment Configuration
The system requires valid API credentials from **Anthropic** and **Hugging Face**.

1.  **Clone Source**:
    ```bash
    git clone https://github.com/thenurinethangi/Chef-Claude-React.git
    cd react-project-two
    ```

2.  **Dependency Resolution**:
    ```bash
    npm install
    ```

3.  **Environment Setup**:
    Initialize a `.env` file in the project root with the following secret keys:
    ```env
    VITE_ANTHROPIC_API_KEY=your_key_here
    VITE_HF_TOKEN=your_token_here
    ```

4.  **Launch Process**:
    ```bash
    npm run dev
    ```

## Technical Specification
*   **Asynchronous Handling**: Custom hook-like patterns for managing AI model latency.
*   **Accessibility**: ARIA-compliant naming and semantic HTML5 implementation.
*   **Build Optimization**: Tree-shaking and module pre-loading via Vite 7.

---

## Contributing
Professional contributions are welcome. Please ensure that all pull requests follow the established architectural patterns and maintain ESLint compliance.

**Contact**: [Nurine Thangi](https://github.com/thenurinethangi)
