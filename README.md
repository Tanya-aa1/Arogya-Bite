# Arogya-Bite

The Arogyabite system integrates several algorithms to provide allergen detection, food label scanning, and personalized diet recommendations:

Users enter details like age, weight, allergies, and preferences to create a profile. Food labels are scanned or uploaded, processed with OpenCV, and text is extracted using Tesseract OCR. NLP techniques match ingredients to a trained allergen database for detection. Machine learning models (e.g., KNN, Random Forest) then generate personalized, allergen-free diet plans, factoring in nutritional content like calories, protein, and carbs to align with user goals.

**PROPOSED METHODOLOGY**

**User Profile Creation:** Users input personal details like allergies, dietary preferences, and health goals, which are stored in MongoDB for customization.

**OCR-based Food Label Reading:** Users upload images of food labels. The Tesseract OCR engine extracts text, which is pre-processed for accuracy.

**Personalized Diet Recommendations:** The system uses machine learning models to recommend foods and diets based on user preferences, allergies, and health goals.

**Natural Language Processing (NLP):** SpaCy processes ingredients and nutritional info, ensuring accurate extraction and understanding of food labels.

**Statistical Representation:** The system generates graphs and charts using Matplotlib to visualize users' dietary intake and allergens exposure.

**User Interface:** Built with React.js and Tailwind CSS, the interface allows easy interaction, while the backend, powered by Flask and Django REST Framework, manages data and APIs.

**Continuous Improvement:** User feedback helps refine machine learning models, improving allergen detection and dietary recommendations.

**LANGUAGES AND TOOLS USED**
**Frontend:**

**React.js:** For building a dynamic, user-friendly interface.

**Tailwind CSS:** For modern, responsive styling.

**Tesseract OCR:** Open-source OCR engine used to extract text from food label images.

**Backend:**

**Python:** Used for backend development, specifically for integrating machine learning models.

**Flask:** A lightweight Python framework for building the backend and handling API requests.

**Django REST Framework:** For building robust APIs to manage the data flow between frontend and backend.

**Express.js:** A fast, minimal web framework for building the backend in JavaScript.

**Node.js:** A JavaScript runtime used for the backend development.

**Database:**

**MongoDB:** A NoSQL database used for storing user profiles, food information, and allergy-related data.
