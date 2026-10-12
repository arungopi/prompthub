1. Prompt to redesign app screen  
    I need to redesign specific screens of my application while keeping the exact same underlying functionality, business logic, and backend integrations. 

    Here is the context of the project:
    * **App Description:** [Briefly describe what your app does, e.g., a food delivery app].
    * **Current Tech Stack:** [e.g., React Native, Node.js, Firebase - Optional but helpful].

    ### 🔒 What MUST Stay the Same (Core Functionality)
    The core logic, data structures, and user capabilities must not change. Specifically:
    * [Example: The user must still be able to filter by price and rating.]
    * [Example: The checkout process must still support Stripe and Apple Pay.]
    * [Example: No new data fields are being added to the database.]

    ### 🎨 What NEEDS to Change (Screen Redesigns)
    I want to update the UI/UX for the following screens. For each screen, I have outlined the desired changes:

    1. [Screen Name, e.g., User Profile Screen]
    * **Current State:** [Briefly describe what is wrong or what it looks like now].
    * **Desired Changes:** [e.g., Make it look cleaner, use a modern card layout, move the "Edit" button to the top right, improve white space].
    * **Visual Style:** [e.g., Minimalist, dark mode, vibrant, corporate].

    2. [Screen Name, e.g., Dashboard Screen]
    * **Current State:** [e.g., Too cluttered, users are getting confused].
    * **Desired Changes:** [e.g., Group metrics into collapsible sections, introduce a bottom navigation bar instead of a hamburger menu].

    ### 🚀 Deliverables Needed
    Please provide:
    * [Choose one: A step-by-step UI/UX layout description / Updated frontend code for these components / A wireframe concept].
    * Ensure that all existing API calls, state management hooks, and button actions are preserved in the new layout structure.

2. Hide the subset of features in the app  
    You are an expert software engineer. I need you to perform the following tasks on the codebase:

    1. **Hide the Current Feature:**
        - Locate and safely disable or hide the feature: [Insert Feature Name / Description here].
        - Ensure that hiding this feature does not break existing dependencies, workflows, UI layouts, or API endpoints.
        - Use clean conditional checks, feature flags, or comment blocks as appropriate, ensuring the underlying code remains stable or is cleanly deprecated.

    2. **Comprehensive Code Documentation:**
        - Add clear, descriptive docstrings and inline comments for all modified or related functions, classes, and modules following standard conventions (e.g., PEP 8 / Google style for Python, JSDoc for JavaScript/TypeScript).
        - Update any relevant project documentation (such as `README.md`, API specs, or configuration guides) to reflect that the feature is currently hidden.
        - Provide a brief summary of the changes made and instructions on how the feature can be re-enabled in the future.

    Please review the relevant files and implement these changes cleanly and efficiently.