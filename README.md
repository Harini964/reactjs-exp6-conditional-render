![WhatsApp Image 2025-09-08 at 15 34 24_85223a6c](https://github.com/user-attachments/assets/66100dd8-498c-4ee6-96fd-7ae313666ff3)



## Conditional Rendering Example

This project demonstrates **conditional rendering in React with Vite**.  
A toggle button is used to show or hide a component dynamically using React state (`useState`).

### Screenshot
Below is a screenshot of the app running on `http://localhost:5173/`:

![Conditional Rendering Screenshot](./WhatsApp%20Image%202025-09-08%20at%2015.34.24_a7ace5a9.jpg)

### Explanation
- When you click **Show Component**, a new component appears.  
- When you click **Hide Component**, the component disappears.  
- This is achieved using conditional rendering:  
  ```jsx
  {isVisible && <MyComponent />}
