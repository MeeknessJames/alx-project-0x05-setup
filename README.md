# Custom Hook for Data Fetching

This project, `alx-project-0x13`, introduces a custom React hook to manage asynchronous data fetching. The primary goal is to improve code reusability and maintain state management (loading, error, and data) in a clean, centralized way.

## Implementation Details

* **Custom Hook:** The `useFetchData.ts` hook handles API calls, sets loading states, captures errors, and stores both the current response and a history of generated images. This allows the main component to remain focused on its UI logic.

* **Homepage:** The `pages/index.tsx` file has been refactored to consume the `useFetchData` hook. It now uses the state and functions provided by the hook to generate and display images, creating a more organized and maintainable codebase.
