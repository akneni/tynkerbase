# Contributing to TynkerBase
Thank you for considering contributing to TynkerBase! We welcome contributions from the community to help us improve and expand our platform. Whether you're fixing bugs, adding new features, or improving documentation, your efforts are greatly appreciated.

## How to Contribute

### Reporting Issues

If you encounter any bugs or have feature requests, please open an issue on our GitHub repository. When reporting issues, please include as much detail as possible to help us understand and reproduce the problem.

### Submitting Pull Requests

1. **Fork the Repository**: Create a personal fork of the TynkerBase repository on GitHub.
2. **Clone the Fork**: Clone your forked repository to your local machine.
   ```bash
   git clone https://github.com/akneni/tynkerbase-XXX.git
   ```
3. **Create a Branch**: Create a new branch for your changes.
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make Changes**: Implement your changes in the new branch.
5. **Commit Changes**: Commit your changes with a descriptive commit message.
   ```bash
   git commit -m "Description of the feature or fix"
   ```
6. **Push Changes**: Push your changes to your fork on GitHub.
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Open a Pull Request**: Open a pull request from your branch to the `main` branch of the TynkerBase repository.

### Coding Guidelines

#### General Guidelines

- Follow the existing code style and conventions.
- Write clear, concise, and meaningful commit messages.
- Ensure your changes do not introduce new issues or break existing functionality.

#### React UI Contributions

When contributing to the React UI, please adhere to the following guidelines:

1. **Use Functional Components**: All components should be functional components.
2. **Component Organization**: Add components to one of the following files based on their complexity:
   - `organisms/organisms.tsx`
   - `molecules/molecules.tsx`
   - `atoms/atoms.tsx`
3. **Styling**: 
   - Each component should have its own separate `.module.css` file for styling.
   - Place the styling files in the corresponding directories:
     - `organisms/styles`
     - `molecules/styles`
     - `atoms/styles`

Example:
If you're adding a new button component:
- Add the component to `atoms/atoms.tsx`.
- Create a corresponding `ComponentNameStyles.module.css` file and place it in `atoms/styles`.
