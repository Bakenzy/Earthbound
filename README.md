# Earthbound
Bakenne Farouq
Earthbound Marketing Page
Project Overview
This project involves designing and implementing a marketing page for Earthbound to showcase the impact of their solar energy installations and encourage companies to purchase carbon credits.
Design Choices
Approach
* Data Visualization: We used infographics, charts, and icons to represent the impact of Earthbond's solar energy projects visually. These visuals help convey the achievements clearly and make the information more engaging.
* Color Scheme: We utilized Earthbond's brand colors (greens, browns, and natural tones) to emphasize the company's environmental and sustainable focus.
* Typography: We chose modern and clean fonts for headlines and subheadlines to ensure readability while maintaining a professional look.
* Call-to-Action (CTA): We placed a clear, prominent CTA button inviting users to contact Earthbond to purchase carbon credits, making it easy for potential customers to engage.
Assumptions
* Data Availability: We assumed that the total solar energy generated, tCO2 offset, and other relevant data points are available and can be updated periodically.
* Interactive Elements: The charts and graphs were designed with the assumption that they would have interactive features such as hover states or tooltips to provide more detailed information.
* Backend Integration: We assumed that the "Contact Us" form and data fetching for statistics may require backend support, which is outside the current scope of this project.
Components Requiring Further Engineering Support
1. Interactive Charts and Graphs
* Current State: We have included static versions of illustrations and would intend for graphs or additional visual representation to be added
2. Contact Form
* Current State: A basic contact form has been included with placeholder fields.
* Ideal Functionality: The form should be connected to a backend service (like a serverless function or an API) that handles submissions and sends data to the Earthbound team. Integration with a service like SendGrid or similar would be ideal.
3. Data Fetching
* Current State: Data is hardcoded in the page for demo purposes.
* Ideal Functionality: Ideally, the data (e.g., total tCO2 offset, number of solar installations) would be dynamically fetched from a database or API to ensure it stays up-to-date.
Instructions for Running the Page Locally
Prerequisites
* A web browser (preferably Chrome or Firefox)
* Basic knowledge of HTML, CSS, and JavaScript
* (Optional) A code editor like VSCode
Steps to Run Locally
Clone the Repository
bash
Copy code
git clone https://github.com/bakenzy/earthbound-marketing-page.git
1. 2. Open the HTML File
   * Locate the index.html file in the project folder.
   * Open the file in your web browser by double-clicking it or right-clicking and selecting "Open with" -> "Browser."
3. View in Browser
   * The page should display correctly in modern browsers. It is currently displayed in 1920px width and responsiveness isnt added yet
