# Links
Links (also known as hyperlinks) are used to navigate between different web pages, sections within a page, or external websites. Links are created using the <a> (anchor) tag.

## 1️⃣ Basic Syntax of a Link
<a href="https://example.com">Click Here</a>
- href (Hyperlink Reference) → Specifies the URL to navigate to when clicked.
- Text between <a> and </a> → The clickable text.

## 2️⃣ Types of Links
### 1. Absolute Links (External Links)
These links point to an external website.
```
<a href="https://www.google.com">Go to Google</a>
```
Clicking this link will take the user to Google's homepage.

### 2. Relative Links (Internal Links)
Used to link to another page within the same website.
```
<a href="about.html">About Us</a>
```
This assumes that about.html exists in the same directory as the current page.

### 3. Linking to a Specific Section on the Same Page (Anchor Links)
Useful for navigating within a single page.
```
<a href="#contact">Go to Contact Section</a>
<h2 id="contact">Contact Us</h2>
<p>Email: example@example.com</p>
```
The id="contact" is a fragment identifier, allowing the link to scroll to that section.

### 4. Opening Links in a New Tab
Use the **target="_blank"** attribute to open a link in a new tab.
Example:
```
<a href="https://www.wikipedia.org" target="_blank">Open Wikipedia</a>
```

### 5. Adding nofollow to Links (SEO Purpose)
The rel="nofollow" attribute tells search engines not to follow the link (useful for untrusted links).
Example:
```
<a href="https://spammywebsite.com" rel="nofollow">Suspicious Link</a>
```

### 6. Linking to an Email Address (mailto)
Clicking this link opens the user’s default email client to send an email.
Example:
```
<a href="mailto:someone@example.com">Email Me</a>
```

### 7. Linking to a Phone Number (tel)
Clicking this on a mobile device will open the dialer.
Example:
```
<a href="tel:+1234567890">Call Us</a>
```

## 3️⃣ Link Attributes
```
Attribute 	 Description
href	     Specifies the URL the link points to.
target	     Defines where to open the link (_blank for a new tab, _self for the same tab).
rel	         Defines the relationship between the current document and linked document (nofollow, noopener, noreferrer).
title	     Displays a tooltip when the user hovers over the link.
```
Example with Multiple Attributes
```
<a href="https://example.com" target="_blank" rel="noopener noreferrer" title="Go to Example">
    Visit Example
</a>
```

## 4️⃣ Styling Links with CSS
### Default Link States
CSS provides different states for styling links:
```
a:link { color: blue; }    /* Normal link */
a:visited { color: purple; } /* After visiting */
a:hover { color: red; }      /* On hover */
a:active { color: green; }   /* While clicking */
```
Example
```
<a href="https://example.com" class="custom-link">Custom Styled Link</a>
```
```
.custom-link {
    text-decoration: none; /* Removes underline */
    color: blue;
    font-weight: bold;
}

.custom-link:hover {
    color: red;
}
```

## 5️⃣ Button as a Link
You can make a button behave like a link.
```
<a href="https://example.com">
    <button>Go to Example</button>
</a>
```
Alternatively, you can use CSS:
```
<button onclick="window.location.href='https://example.com'">
    Visit Example
</button>
```
## 6️⃣ Downloadable Links
Use the download attribute to allow file downloads.
Example:
```
<a href="document.pdf" download>Download PDF</a>
```

## 7️⃣ Disabled Links
If you want to disable a link using CSS:
```
<a href="#" class="disabled-link">Disabled Link</a>
```
```
.disabled-link {
    pointer-events: none;
    color: gray;
    text-decoration: none;
}
```

# 🔍 Summary of HTML Links
```
Link Type	            Example
Basic Link	            <a href="https://example.com">Visit Example</a>
Open in New Tab	        <a href="https://example.com" target="_blank">New Tab</a>
Internal Link	        <a href="about.html">About Us</a>
Anchor Link	            <a href="#section">Go to Section</a>
Email Link	            <a href="mailto:someone@example.com">Email</a>
Phone Link	            <a href="tel:+1234567890">Call Us</a>
Downloadable File	    <a href="file.pdf" download>Download</a>
```









