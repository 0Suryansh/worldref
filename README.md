## Task 1: Setting Up the Project (10 points)
Initialize a new Next.js project with TypeScript configuration.
Implement a custom webpack configuration to handle asset optimization.
Set up ESLint and Prettier for code linting and formatting.
Implement CI/CD pipeline using tools like GitHub Actions or GitLab CI.

### The projext is in ts, CI/CD is setup using github and vercel, ESlint and prettier are configured and assets are also optimized while rendering.

## Task 2: Creating Components (20 points)
Create a reusable Navbar component with responsive design using CSS Grid or Flexbox.
Develop a Modal component that can be reused across the application.
Implement a Form component with client-side validation using libraries like Formik or React Hook Form.

### Reusable Navbar Component is made,(before login and after login have two different views).

![image](https://github.com/0Suryansh/worldref/assets/75418521/25eee1b4-8583-4245-812a-b612be9ed327)
![image](https://github.com/0Suryansh/worldref/assets/75418521/efac50c7-5990-418f-911a-0a4bf4735f3e)

### Modals are reused(see below)
![image](https://github.com/0Suryansh/worldref/assets/75418521/bbd1d29b-59b9-43f0-b233-f59c8c0fbb2c)
![image](https://github.com/0Suryansh/worldref/assets/75418521/eafd8ebb-e420-4f52-b839-2b1f93aa5d34)
![image](https://github.com/0Suryansh/worldref/assets/75418521/7d523ea8-c6c8-4879-ab24-21f23691136c)

### Contact form is made using React hook form, server actions and zod.
![image](https://github.com/0Suryansh/worldref/assets/75418521/6a89752a-bd72-4bcc-a591-8aa3b4018ca6)


## Task 3: State Management (10 points)
Utilize Redux or React Context API for state management. Implement middleware in Redux for asynchronous
actions. Use selectors for efficient data retrieval from the store.

### Redux is used, api data received is being stored and then useSelector is used to subscribe to it.
![image](https://github.com/0Suryansh/worldref/assets/75418521/11855626-92f4-41fe-baf1-f531a61e98de)

## Task 4: Routing (10 points)
Implement dynamic routing for blog posts, where each post has a unique URL. Use nested routing to create a
dashboard with multiple sub-pages. Implement route-level code splitting for improved performance.

### Blogs and Dasboadrd pages used dynamic and nested routing, see search bar
![image](https://github.com/0Suryansh/worldref/assets/75418521/08d274f9-c54e-460d-aae5-b7bacc4f9059)
![image](https://github.com/0Suryansh/worldref/assets/75418521/ce32690d-8ca7-405b-95ea-a63f923a947a)
![image](https://github.com/0Suryansh/worldref/assets/75418521/5deccc56-69e1-4c6b-b8ba-d99e76531ae0)
![image](https://github.com/0Suryansh/worldref/assets/75418521/80e3682c-7964-4df3-82dc-35aa5bca6f93)
![image](https://github.com/0Suryansh/worldref/assets/75418521/b6907022-3647-465c-bc2a-dd8069e7bbcf)
![image](https://github.com/0Suryansh/worldref/assets/75418521/afecd19d-8a07-41bf-8924-f636c021cf00)


## Task 5: API Integration (20 points)
Integrate a third-party API requiring OAuth authentication. Implement error handling and retry mechanisms for
API requests. Cache API responses using a caching strategy like memoization or local storage.

### Google OAuth is used and after it third-party apis are called to render quotes.
![image](https://github.com/0Suryansh/worldref/assets/75418521/bc5e31da-995f-46ec-9dc7-ba75c24950f8)
![image](https://github.com/0Suryansh/worldref/assets/75418521/a7491178-c691-4ae5-919b-ae2e8337adc3)


## Task 6: Server-side Rendering (SSR) (10 points)
Utilize getStaticProps to pre-render dynamic pages with data fetching. Implement server-side caching for
frequently accessed pages. Optimize SSR performance using techniques like incremental static regeneration.

![image](https://github.com/0Suryansh/worldref/assets/75418521/caa91e7c-1323-455e-b234-6ac80e57e9fb)
### Pre-render Blog pages with data fetching dynamically.
![image](https://github.com/0Suryansh/worldref/assets/75418521/52256342-eaed-495a-ab93-4e7d3fa7f64f)


## Task 7: Styling (10 points)
Use CSS Modules or CSS-in-JS libraries like Emotion or Styled Components. Implement a design system with
reusable UI components and consistent theming. Optimize styles for performance, including critical CSS
extraction and lazy loading.

### CSS Modules are used here in the project.
