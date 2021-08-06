In this project, let's build a **Meme Generator** by applying the concepts we have learned till now.

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/meme-generator-output.gif" alt="meme-generator" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

#### Design Files

<details>
<summary>Click to view the Design Files</summary>

- [Extra Small (Size < 576px) and Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js/meme-generator-sm-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/meme-generator-lg-output.png)

</details>

### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>

### Completion Instructions

<details>
<summary>Functionality to be added</summary>
<br/>

The app must have the following functionalities

- Initially, values in the inputs elements should be empty and the selected value in the select element should be the first item in the given fontSizesOptionsList 
- When non-empty values are provided for **Image Url**, **Top Text**, **Bottom Text**, and **Font Size** and the **Generate** button is clicked,
        - The Image URL that has been given in the Image URL input should be applied as a background-image for the generated meme.
        - The given Top and Bottom text values in the respective input elements should be the top and bottom text for the generated meme.
        - The selected value in the select element should be the applied font size for both top and bottom text for the generated meme.
  </details>

<details>

<summary>Click to view the Implementation Files</summary>

Use these files to complete the implementation:
  - `src/App.js`
  - `src/components/MemeGenerator/index.js`
  - `src/components/MemeGenerator/styledComponents.js`
</details>

### Important Note

<details>
<summary>Click to view</summary>

<br/>

- The following HTML attributes are required for the HTML for the tests to pass.
 - The generated meme container should have **data-testid** as "meme".
 - In previous CPs you have used **testid**. From now when the styled Components are used **data-testid** should be used instead of **testid**.

</details>

### Resources

<details>
<summary>Colors</summary>

<br/>

<div style="background-color: #35469c; width: 150px; padding: 10px; color: black">Hex: #35469c</div>
<div style="background-color: #7e858e; width: 150px; padding: 10px; color: black">Hex: #7e858e</div>
<div style="background-color: #5a7184; width: 150px; padding: 10px; color: black">Hex: #5a7184</div>
<div style="background-color: #ffffff; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #d7dfe9; width: 150px; padding: 10px; color: black">Hex: #d7dfe9</div>
<div style="background-color: #1e293b; width: 150px; padding: 10px; color: black">Hex: #1e293b</div>
<div style="background-color: #0b69ff; width: 150px; padding: 10px; color: black">Hex: #0b69ff</div>

</details>

#### Font-families

- Open Sans

> ### _Things to Keep in Mind_
>
> - All components you implement should go in the `src/components` directory.
> - Don't change the component folder names as those are the files being imported into the tests.
> - **Do not remove the pre-filled code**
> - Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets.