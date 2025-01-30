# Lists
In HTML, lists are used to group items in a structured way. There are three main types of lists:

- Unordered List `(<ul>)`
- Ordered List `(<ol>)`
- Description List `(<dl>)`

## 1️⃣ Unordered List `(<ul>)`
An unordered list is used when the order of the items doesn't matter. The list items are displayed with bullet points by default.
```
<ul>
    <li>Apples</li>
    <li>Bananas</li>
    <li>Cherries</li>
</ul>
```
Output:
- Apples
- Bananas
- Cherries

## Customizing the Bullets:
You can customize the bullet style using CSS:
```
ul {
    list-style-type: square; /* Square bullets */
    list-style-type: circle; /* Hollow bullets */
    list-style-type: none; /* No bullets */
}
```

## 2️⃣ Ordered List `(<ol>)`
An ordered list is used when the order of the items does matter. The list items are numbered by default.
```
<ol>
    <li>Step 1: Preheat the oven.</li>
    <li>Step 2: Mix the ingredients.</li>
    <li>Step 3: Bake for 30 minutes.</li>
</ol>
```
Output:
```
1. Step 1: Preheat the oven.
2. Step 2: Mix the ingredients.
3. Step 3: Bake for 30 minutes.
```

## Customizing the Numbering:
You can change the numbering style using CSS:
```
ol {
    list-style-type: upper-roman; /* I, II, III */
    list-style-type: decimal; /* 1, 2, 3 */
    list-style-type: lower-alpha; /* a, b, c */
}
```

## 3️⃣ Description List `(<dl>)`
A description list is used to define a list of terms and their descriptions. It uses `<dt>` for the term and `<dd>` for the description.
```
<dl>
    <dt>HTML</dt>
    <dd>HyperText Markup Language, used to structure web pages.</dd>
    <dt>CSS</dt>
    <dd>Cascading Style Sheets, used to style web pages.</dd>
</dl>
```
Output:
- **HTML:** HyperText Markup Language, used to structure web pages.
- **CSS:** Cascading Style Sheets, used to style web pages.

## Nested Lists
You can create lists inside other lists (nested lists). You can nest `<ul>`, `<ol>`, or `<dl>` inside each other.
```
<ul>
    <li>Fruits
        <ul>
            <li>Apples</li>
            <li>Bananas</li>
        </ul>
    </li>
    <li>Vegetables
        <ul>
            <li>Carrots</li>
            <li>Spinach</li>
        </ul>
    </li>
</ul>
```
Output:

- Fruits
    - Apples
    - Bananas
- Vegetables
  - Carrots
  - Spinach

## Additional List Styling Using CSS
You can style the lists to make them more visually appealing:
- **1.Remove Bullets from Unordered List:**
```
ul {
    list-style-type: none; /* No bullets */
    padding-left: 0; /* Remove indentation */
}
```

- **2. Indent Lists:**
```
ul {
    padding-left: 20px; /* Indent items */
}
```

- **3. Custom Bullet Points:** 
You can add custom images as list bullets
```
ul {
    list-style-image: url('bullet.png');
}
```

- **4. Numbering Styles:** 
You can use Roman numerals, letters, or decimals for ordered lists
```
ol {
    list-style-type: upper-roman; /* I, II, III */
}
```
## Summary Table
<table>
<thead>
    <tr>
        <th> List Type </th>
        <th> Tag </th>
        <th> Use Case </th>
        <th> Default Style </th>
    </tr>
</thead>
<tbody>
    <tr>
        <th> Unordered List </th>
        <td> `<`ul`>` </th>
        <td> When the order doesn't matter </th>
        <td> Bullets </th>
    </tr>
    <tr>
        <th> Ordered List </th>
        <td> `<`ol`>` </th>
        <td> When the order does matter </th>
        <td> Numbered </th>
    </tr>
    <tr>
        <th> Descrpition List </th>
        <td> `<`dl`>` </th>
        <td>Used for terms and definitions </th>
        <td> None (formatted in terms of terms and descriptions) </th>
    </tr>
</tbody>
</table>
