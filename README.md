# Making Sense of Change Detection in Angular

This project delves into Angular's change detection mechanism, providing a thorough understanding of how it works and how to optimize it for efficient performance. It explores strategies and tools to manage change detection effectively, ensuring responsive and scalable applications.

### Key Features:

- **Understanding Change Detection**:
  - Analyze how Angular performs change detection and how it updates the DOM efficiently.
  - Learn to identify and resolve common issues such as `ExpressionChangedAfterChecked` errors during development.

- **Optimizing Template Bindings**:
  - Write efficient template bindings to minimize unnecessary change detection cycles and improve application performance.

- **Avoiding Zone Pollution**:
  - Explore strategies to prevent zone pollution, which can lead to performance bottlenecks in large applications.

- **OnPush Strategy**:
  - Understand and implement the `OnPush` strategy to reduce change detection overhead by limiting checks to specific components.
  - Learn to work with `OnPush` and signals to optimize cross-component data sharing.

- **Advanced Change Detection Techniques**:
  - Use RxJS subjects to trigger change detection manually for greater control.
  - Introduce the `async` pipe for handling observable data streams efficiently within templates.

- **Going Zoneless**:
  - Explore the concept of going "zoneless" to eliminate Angular's reliance on zones and further optimize performance.

By the end of this project, the application is optimized with a deep understanding of Angular's change detection system, leveraging advanced techniques and strategies to build high-performance and scalable applications.

## Deployment

The project is deployed and accessible online. You can view it at the following link:

**[Deployed Site](https://ralucaspt.github.io/change-detection/)**
