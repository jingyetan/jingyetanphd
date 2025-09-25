# Photo Upload Instructions 📸

This directory structure is set up for organizing your personal photos:

## Directory Structure

- **photography/** - Your photography work and travel shots
- **figures/** - Action figure builds, collections, and workspace photos
- **food/** - Foodie adventures, restaurant discoveries, and culinary experiences

## Adding Photos

1. **Resize images** to web-friendly dimensions (recommended: 800-1200px width for gallery images)
2. **Optimize file sizes** to keep the website loading fast
3. **Use descriptive filenames** (e.g., `sunset-kyoto-2025.jpg`, `gundam-custom-build-01.jpg`)

## Updating the Website

Once you add photos to these directories:

1. **Edit the homepage** (`index.markdown`) to replace placeholder images:
   ```html
   <div class="hobby-placeholder">
   <!-- Replace this with: -->
   <img src="{{ '/assets/images/photography/your-photo.jpg' | relative_url }}" alt="Description">
   ```

2. **Update captions and descriptions** to match your actual photos

3. **Add new blog posts** about your adventures in the `_posts/` directory

## Photo Suggestions

### Photography Tab
- Landscape shots from travels
- Street photography from different cities
- Conference/work travel photos
- Your favorite photography subjects

### Figures Tab
- Completed action figure builds
- Work-in-progress shots
- Your workspace/building setup
- Collection displays

### Food Tab
- Great meals from travels
- Local restaurant discoveries
- Conference dining experiences
- Street food adventures
- Craft coffee and drinks

## Tips

- Keep the original high-resolution photos elsewhere as backup
- Consider adding EXIF data removal for privacy
- Use consistent image ratios for better gallery appearance
- Add alt text for accessibility

Have fun personalizing your website! 🎉
