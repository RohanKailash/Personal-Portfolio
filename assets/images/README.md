# Images Folder

This folder is for storing your portfolio images and photos.

## 👤 Profile Images
- **Main Profile Photo**: Add your professional headshot here
- **About Section Image**: Add a photo that represents your work or interests
- Recommended filename: `profile-photo.jpg` or `about-image.jpg`

## 🚀 Project Images
- **Project Screenshots**: Add screenshots of your projects
- **Project Thumbnails**: Create smaller versions for the project cards
- Recommended format: JPG or PNG
- Recommended size: 800x600px or similar aspect ratio

## 🎨 Image Guidelines
- **Quality**: Use high-resolution images (at least 800px wide)
- **Format**: JPG for photos, PNG for screenshots with text
- **Size**: Optimize for web (under 500KB per image)
- **Aspect Ratio**: Keep consistent ratios for better layout

## 🔄 Updating Image References
In your `index.html` file, replace the placeholder icons with actual images:

### Profile Image (Hero Section)
```html
<!-- Replace this: -->
<div class="w-80 h-80 bg-gradient-to-br from-primary to-blue-600 rounded-full flex items-center justify-center">
    <i class="fas fa-user text-white text-8xl"></i>
</div>

<!-- With this: -->
<img src="assets/images/profile-photo.jpg" alt="Rohan - AI & Robotics Specialist" 
     class="w-80 h-80 rounded-full object-cover shadow-2xl">
```

### About Section Image
```html
<!-- Replace this: -->
<div class="w-96 h-96 bg-gradient-to-br from-blue-100 to-indigo-200 rounded-2xl shadow-xl flex items-center justify-center">
    <i class="fas fa-laptop-code text-8xl text-primary"></i>
</div>

<!-- With this: -->
<img src="assets/images/about-image.jpg" alt="Rohan working on AI projects" 
     class="w-96 h-96 rounded-2xl object-cover shadow-xl">
```

### Project Images
```html
<!-- Replace the colored divs with actual project images -->
<img src="assets/images/project1-screenshot.jpg" alt="Alzheimer's Disease Diagnosis Project" 
     class="w-full h-48 object-cover rounded-t-xl">
```

## 🛠️ Image Optimization Tools
- **Online**: TinyPNG, Compressor.io
- **Desktop**: ImageOptim (Mac), FileOptimizer (Windows)
- **Photoshop**: Save for Web feature

## 📱 Responsive Images
Consider adding multiple image sizes for different screen resolutions:
- `image-small.jpg` (400px wide)
- `image-medium.jpg` (800px wide)  
- `image-large.jpg` (1200px wide)

Then use the `srcset` attribute for responsive images:
```html
<img src="assets/images/profile-photo-medium.jpg" 
     srcset="assets/images/profile-photo-small.jpg 400w,
             assets/images/profile-photo-medium.jpg 800w,
             assets/images/profile-photo-large.jpg 1200w"
     sizes="(max-width: 768px) 400px, 800px"
     alt="Rohan - AI & Robotics Specialist">
``` 