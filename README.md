Overview

This React Native project is a shopping app with two primary screens: HomeScreen for browsing available products and CartScreen for cart management. It employs the useContext hook for state management and AsyncStorage for local data persistence.
Design Choices

    Context API: Utilized for managing cart state across various components, facilitating the addition and removal of items from the cart without needing to pass props through multiple levels.
    AsyncStorage Selected for local data storage to ensure cart items persist even when the app is closed or restarted.
    FlatList: Used for efficient rendering of product and cart item lists, ensuring smooth performance even with a large number of items.
    Modular Components: The codebase is organized with separate components for ProductCard and context management, enhancing maintainability and clarity.

Implementation

    Cart Context: A CartContext is implemented to provide methods for adding and removing items from the cart, with cart state persistence handled by AsyncStorage. HomeScreen: Displays a list of products, each with an "Add to Cart" button.
    CartScreen: Shows the items in the cart, each with a "Remove from Cart" button.
    Data Storage: Uses AsyncStorage to save and load cart items, ensuring the cart state is preserved across app sessions.

Screenshots

![WhatsApp Image 2024-07-12 at 22 04 27_cf84aecc](https://github.com/user-attachments/assets/12bca7f6-97b7-4b42-a6ad-519ca92073e1)

![WhatsApp Image 2024-07-12 at 22 05 14_9ca0470b](https://github.com/user-attachments/assets/d46f9e1e-efb5-4bcd-958c-3ce7ccb50796)

![WhatsApp Image 2024-07-12 at 22 06 33_ca823c64](https://github.com/user-attachments/assets/08203314-c486-40bf-b901-cae6c8586dda)

![WhatsApp Image 2024-07-12 at 22 11 19_3c714ce0](https://github.com/user-attachments/assets/608f0ad6-da5e-4378-bbc3-d5befc7aed0c)



