# Profile Picture Instructions

## How to Replace the Profile Picture Placeholder

To replace the profile picture placeholder with your own photo:

1. **Prepare your profile picture:**
   - Resize your photo to 120x120 pixels for optimal display
   - Supported formats: JPG, PNG, SVG
   - Recommended: Square crop for best appearance in the circular frame

2. **Replace the placeholder file:**
   - Replace the file `profile-placeholder.svg` with your profile picture
   - Name your file `profile-picture.jpg` (or `.png`)

3. **Update the HTML files:**
   - Update the `src` attribute in all HTML files from `profile-placeholder.svg` to your image filename
   - Files to update:
     - `index.html`
     - `Frame3.html`
     - `Frame4.html` 
     - `Frame5.html`
     - `Frame6.html`

4. **Example:**
   ```html
   <!-- Replace this line: -->
   <img src="profile-placeholder.svg" alt="Profile Picture Placeholder" class="profile-img">
   
   <!-- With this line: -->
   <img src="profile-picture.jpg" alt="Your Name - Profile Picture" class="profile-img">
   ```

The CSS is already configured to properly display your image in a circular frame with the correct styling.