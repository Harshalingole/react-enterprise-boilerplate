# React Enterprise Boilerplate

React Enterprise Boilerplate is a starter template for building scalable and maintainable React applications for enterprise-level projects. This boilerplate provides a well-organized and optimized project structure with pre-configured tools.

## Features

- Well-organized and optimized project structure
- Separation of concerns, with clear division between components, constants, hooks, layouts, pages, routes, store, and utils
- Sample implementation of various features, including authentication, dashboard, and posts
- Built on top of the latest version of React, with full support for TypeScript

## Methodology Behind Organizing React Project Directory Structure
Creating a scalable and maintainable codebase in React can be challenging, but by following a few key principles, we can make the process much smoother. Here are three principles that I've used in this React Enterprise Boilerplate:
### Composability: 
    Reusing code between components is a powerful concept in React. By creating small, reusable building blocks, you can combine them to form more complex components. For example, a "Button" component can be used in multiple places throughout your application.
### Local first:
    Keep the code that pertains only to a specific component, local. Avoid breaking out code into separate directories unless necessary. For example, an authentication feature with an auth-form component and utility functions should be kept in the same directory as the feature itself.
### Flatter is better:
     Every time you nest a component, it becomes harder to understand its local code. Keeping your directory structure as flat as possible makes it easier to find and modify the files you need. However, if you have a large "Features" directory with multiple components, it's okay to nest components by their functionality or the page they're used on.
It is important to note that while the principles outlined above can be incredibly helpful in creating a scalable and maintainable React codebase, they are not hard and fast rules. Ultimately, the best directory structure for your project will depend on its specific requirements and needs.

That said, the principles of composability, local-first development, and flat directory structures are powerful tools that can make your development process smoother and more efficient. By organizing your codebase in a way that promotes reusability, keeps related code together, and minimizes nesting, you can create a more organized and manageable project.

In the end, the key is to use these principles as a starting point, and to be willing to adjust and adapt your directory structure as needed to best suit your project's unique needs. By keeping an open mind and remaining flexible, you can build a codebase that is not only scalable and maintainable, but also perfectly tailored to your project's requirements.

## Folder Structure

The folder structure of the project is as follows:

### assets
The assets folder contains various asset files that are used throughout the application, such as images, fonts, documents, and styles. These files are organized into subfolders based on their type, making it easy to find and manage them.

### components
The components folder contains common, shared, and UI components that are used throughout the application. These components are organized into subfolders based on their purpose or functionality, making it easy to find and manage them. This folder follows the Atomic Design methodology.

### constants
The constants folder contains constant values that are used throughout the application, such as API endpoints and error messages. This helps to centralize and organize these values, making them easier to manage and update.

### features
The features folder contains feature-specific code, including components, hooks, services, slices, and utils. Each feature is organized into a separate subfolder, making it easy to find and manage the code related to each feature.

### hooks
The hooks folder contains various custom hooks that are used throughout the application. These hooks are organized into subfolders based on their functionality, making it easy to find and manage them.

### layouts
The layouts folder contains layout components that are used to structure the overall layout of the application. This includes components such as the header and footer. These components are designed to be reusable across the application and can be easily customized.

### pages
The pages folder contains the top-level pages for the application, organized into subfolders based on their feature. Each page typically consists of a combination of components and hooks, and is responsible for handling the business logic and rendering of the page.

### routes
The routes folder contains routing components that are used to handle navigation within the application. This includes components such as private and public routes, and routes with layout. These components are designed to provide a consistent and intuitive navigation experience for the user.

### store
The store folder contains Redux store-related code, including slices, services, and rtkQuery. These components are used to manage the state of the application and communicate with external APIs.

### utils
The utils folder contains various utility functions that are used throughout the application, such as date formatting and email validation. These functions are organized into subfolders based on their functionality, making it easy to find and manage them.
# Getting Started

To get started with the project, follow these steps:

1. Clone the repository: `[git clone https://github.com/{your-repository-name}.git] (https://github.com/Harshalingole/react-enterprise-boilerplate.git)`
2. Install the dependencies using `npm install`.
3. Start the development server using `npm run dev`.

## Contributing

I welcome contributions and suggestion from the community. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/bugfix using `git checkout -b <branchname>`.
3. Make your changes and commit them using `git commit -m "<commit message>"`.
4. Push your changes to your fork using `git push origin <branchname>`.
5. Create a pull request on the main repository and describe your changes.

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.

## Acknowledgements

This project was inspired by folder structure i personally implemented in building ardev erp software,various enterprise-level React open source application,blogs,and best industry practices.

## Conclusion
React Enterprise Boilerplate provides a solid foundation for building scalable and maintainable React applications for enterprise-level projects. Its well-organized and optimized project structure, along with pre-configured tools and libraries, will help you to get up and running quickly and efficiently.Ultimately, the best directory structure for your project will depend on its specific requirements and needs.