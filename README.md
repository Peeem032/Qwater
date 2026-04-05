# 💧 Qwater

**Qwater** is a modern, full-stack artificial intelligence application built to analyze and predict water-related metrics (such as water quality, levels, or safety). It integrates advanced machine learning models directly into an interactive web platform.

## Key Components
*   **AI-Powered Backend (`backend`):** A Python-based API that hosts dual machine-learning capabilities:
    *   A deep learning computer vision model (`best.pt`, likely a PyTorch/YOLO model) for visual analysis.
    *   An XGBoost structured data model (`xgb_model.json`) for numerical predictions and predictive analytics.
*   **Modern Next.js Frontend (`frontend`):** Built with Next.js (TypeScript) and Tailwind CSS, the frontend provides a sleek and responsive user interface. It includes dedicated routing (e.g., a custom data-entry `/form` page) allowing users to easily interact with the complex AI backend.