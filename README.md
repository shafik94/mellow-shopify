# mellow-shopify
Mellow Shopify

## Setup Instructions

- I decided to use the Dawn theme from shopify as the starter. 
- The development enviromnet was set using shopify cli on my local machine for rapid development
- Some parts of the theme where modified from the theme editor on the browser but the majority was modifying the liquid code temaples.
- This repository does not include all liquid files from the template but only the ones I modified with my own code.
- The Design is similar to the one on wordpress, using the same elements and implementing them onto the liquid code.
- Tailwind CSS framework was used again for the theme, allowing me to move rapidly and consistent with the design.


1. **Install Dependencies**  
   Navigate to the project directory and install the required dependencies:
   ```bash
   cd mellow-shopify
   npm install
   ```

3. **Setup Shopify CLI**  
   Ensure you have the Shopify CLI installed. If not, follow the [Shopify CLI installation guide](https://shopify.dev/docs/themes/tools/cli/installation).  
   Once installed, log in to your Shopify store:
   ```bash
   shopify login --store your-store-name.myshopify.com
   ```

4. **Development Server**  
   Start the development server to preview and edit your theme:
   ```bash
   shopify theme dev
   ```

5. **Build for Production**  
   To build the theme for production, run:
   ```bash
   npm run build
   ```

6. **Push to Shopify**  
   Deploy the theme to your Shopify store:
   ```bash
   shopify theme push
   ```

## Design Choices

### Why Dawn?  
We chose **Dawn**, Shopify's default theme, as the foundation for this project because:  
- **Performance**: Dawn is optimized for speed and adheres to Shopify's best practices for theme development.  
- **Flexibility**: It provides a modular structure and supports Online Store 2.0 features like sections everywhere.  
- **Accessibility**: Dawn is built with accessibility in mind, ensuring a better experience for all users.  
- **Customizability**: Its clean and minimal design makes it easy to customize and adapt to the brand's identity.

### Images  
The images used in this project were sourced from:  
- **Unsplash**: For high-quality, royalty-free stock images.  
- **Shopify's Free Image Library**: Available directly within the Shopify admin.  
- **Custom Graphics**: Designed in-house using tools like Adobe Photoshop and Figma.  

All images have been optimized for web performance using Shopify's built-in image optimization tools.

## Additional Notes

- **Styling**: TailwindCSS was used for rapid prototyping and consistent styling across the theme.  
- **Custom Features**: Features like advanced filtering, dynamic cart updates, and responsive design were implemented to enhance the user experience.  
- **Accessibility**: The theme adheres to Shopify's accessibility guidelines to ensure usability for all customers.

For any questions or contributions, feel free to open an issue or submit a pull request.