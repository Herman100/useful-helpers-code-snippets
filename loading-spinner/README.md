/\*\*

- A customizable loading spinner component for React applications.
-
- @component
- @example
- ```tsx

  ```
- <LoadingSpinner size="md" color="primary" text="Loading..." />
- ```

  ```
-
- @param {Object} props - The component props
- @param {'sm' | 'md' | 'lg' | 'xl'} [props.size='md'] - The size of the spinner
- - 'sm': Small (16x16px)
- - 'md': Medium (24x24px)
- - 'lg': Large (32x32px)
- - 'xl': Extra Large (48x48px)
-
- @param {'primary' | 'secondary' | 'white' | 'muted'} [props.color='primary'] - The color of the spinner
- - 'primary': Blue color
- - 'secondary': Dark gray color
- - 'white': White color
- - 'muted': Light gray color
-
- @param {string} [props.text] - Optional text to display below the spinner
- @param {string} [props.className=''] - Additional CSS classes to apply to the container
-
- @returns {JSX.Element} A spinning loading indicator with optional text
-
- The component uses Tailwind CSS for styling and includes:
- - Customizable sizes and colors
- - Optional loading text
- - Smooth spinning animation
- - Dark mode support
- - Flexible layout options through className prop
    \*/
