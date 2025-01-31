# Images
Images play a crucial role in web development, enhancing the visual appeal of a webpage. The <img> tag is used to insert images in HTML.

## 1️⃣ Basic Syntax of an Image
```
<img src="image.jpg" alt="Description of Image">
```
- src (Source) → Specifies the path of the image.
- alt (Alternative Text) → Provides text if the image fails to load (also improves accessibility and SEO).

## 2️⃣ Image File Paths
### 1. Absolute Path (External Image)
The image is loaded from an external source (URL).
Example:
```
<img src="https://www.example.com/image.jpg" alt="Example Image">
```
### 2. Relative Path (Internal Image)
The image is stored within the project folder.
```
<img src="images/photo.jpg" alt="Local Image">
```
- If the image is in a subfolder images/, use src="images/photo.jpg".
- If it's in the parent folder, use src="../photo.jpg".

## 3️⃣ Image Attributes
```
Attribute	                Description
src                         Specifies the image file path (local or external).
alt	                        Provides alternative text (for accessibility and SEO).
width	                    Sets the width of the image (in pixels or percentage).
height	                    Sets the height of the image (in pixels or percentage).
title	                    Displays a tooltip when hovered.
loading	                    Lazy loading (lazy, eager).
style	                    Allows inline CSS styling.
```
Example with Multiple Attributes
```
<img src="images/photo.jpg" alt="A beautiful sunset" width="400" height="300" title="Sunset View">
```
## 4️⃣ Image Resizing
### 1. Using width and height Attributes
```
<img src="photo.jpg" width="300" height="200">
```

### 2. Using CSS
```
<img src="photo.jpg" class="responsive-img">
```
```
.responsive-img {
    width: 100%;  /* Makes image fit container */
    max-width: 500px; /* Limits maximum size */
    height: auto; /* Maintains aspect ratio */
}
```

## 5️⃣ Responsive Images
To make images responsive, use CSS or Bootstrap:

### 1. Using max-width in CSS
```
img {
    max-width: 100%;
    height: auto;
}
```

### 2. Using Bootstrap
```
<img src="photo.jpg" class="img-fluid">
```

## 6️⃣ Image Links (Clickable Images)
```
<a href="https://example.com">
    <img src="image.jpg" alt="Clickable Image" width="200">
</a>
```
Clicking the image will open example.com.

## 7️⃣ Lazy Loading Images (Improves Performance)
By default, images load immediately. To improve performance, use lazy loading.
```
<img src="image.jpg" alt="Lazy Load Image" loading="lazy">
```
- lazy → Loads the image only when it comes into view.
- eager (default) → Loads immediately.

## 8️⃣ Adding Images to the <figure> Element (Semantic HTML)
The <figure> tag allows images to have captions.
```
<figure>
    <img src="nature.jpg" alt="Beautiful Nature">
    <figcaption>Nature at its best</figcaption>
</figure>
```

## 9️⃣ Background Images Using CSS
Instead of using <img>, you can set a background image using CSS:
```
.background {
    background-image: url('background.jpg');
    background-size: cover;
    height: 400px;
}
```
<div class="background"></div>

## 🔍 Summary of HTML Images
```
Feature	                        Example
Basic Image	                    <img src="photo.jpg" alt="Image">
External Image	                <img src="https://example.com/image.jpg" alt="External">
Resize Image	                <img src="photo.jpg" width="300" height="200">
Responsive Image (CSS)	        max-width: 100%; height: auto;
Lazy Load Image	                <img src="photo.jpg" loading="lazy">
Image Link	                    <a href="example.com"><img src="photo.jpg"></a>
Figure with Caption	            <figure><img src="photo.jpg"><figcaption>Caption</figcaption></figure>
```