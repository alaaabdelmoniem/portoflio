# How to Add Your Developer Photo

Your portfolio now has a dedicated space for your developer photo with beautiful parallax animation!

## Steps to Add Your Photo:

1. **Prepare Your Photo**
   - Recommended size: 280px × 320px
   - Format: PNG, JPG, or WEBP
   - Make sure it's a professional headshot or portrait

2. **Add Photo to Assets**
   - Save your photo as `developer.png` (or any name)
   - Place it in the `assets/` folder

3. **Update HTML**
   - Open `portfolio (1).html`
   - Find this line (around line 1255):
   ```html
   <div class="developer-photo" id="devPhoto">
     <div class="photo-placeholder">
       📸<br>Add Your Photo
     </div>
   </div>
   ```
   - Replace it with:
   ```html
   <div class="developer-photo" id="devPhoto">
     <img src="assets/developer.png" alt="Developer Photo">
   </div>
   ```

## Animation Features:
- ✨ **Parallax effect** - Photo rotates and scales as you scroll
- 🎯 **3D perspective** - Smooth rotation on both X and Y axes
- 🔄 **Smooth transitions** - Scales up on hover
- 📱 **Responsive** - Adapts to mobile devices

The photo will automatically animate when users scroll up and down the page!
