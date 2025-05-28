# Project Title
Art Creation | Custom Paintings Made Easy

# Description
This project is a web application that allows users to order custom paintings. Users can fill out a form with their details, specify their desired painting style (portrait, landscape, abstract, or custom), choose a canvas size (A2, A3, A4, A5, or custom dimensions), provide a description of their idea, and upload reference images. The application then processes this information, uploads the reference image to ImgBB, and sends an order confirmation email to the user and the service provider using EmailJS. A confirmation popup is displayed to the user upon successful submission.

# Features
- User-friendly form to collect order details for custom paintings.
- Options for various painting types (Portrait, Landscape, Abstract, Custom).
- Selection of standard canvas sizes (A4, A3, A2, A5) and an option for custom dimensions.
- Image uploader with drag-and-drop functionality and preview for reference images.
- Reference images are uploaded to ImgBB to generate a shareable link.
- Automated email notifications for order confirmation using EmailJS.
- Interactive confirmation popup upon successful form submission.
- Responsive design for use on different devices.

# Getting Started
1. Clone the repository: `git clone <repository-url>`
2. Open `index.html` in your web browser.
3. To enable email notifications:
    - Sign up for an account at [EmailJS](https://www.emailjs.com/).
    - Create a new service and connect your email provider.
    - Create a new email template.
    - In `script.js`, replace the placeholder values for `SERVICE_ID`, `TEMPLATE_ID`, and `PUBLIC_KEY` with your actual EmailJS credentials.
4. To enable image uploading:
    - Sign up for an account at [ImgBB](https://imgbb.com/).
    - Get your API key.
    - In `script.js`, in the `uploadToImgBB` function, replace the placeholder API key in the fetch URL (`https://api.imgbb.com/1/upload?key=YOUR_API_KEY`) with your actual ImgBB API key.

# Usage
1. Open the `index.html` file in a web browser.
2. Fill in your full name, contact email, and phone number.
3. Provide your shipping address details: apartment/flat number, nearby landmark, street address, state, and PIN code.
4. Select the desired painting type (Portrait, Landscape, Abstract, or Custom Design).
5. Choose a canvas size from the predefined options (A4, A3, A2, A5) or select "Custom Size" and enter the width and height in millimeters.
6. Write a description of your painting idea.
7. Optionally, upload reference images by dragging and dropping them onto the designated area or by clicking to browse your files. You can upload multiple images.
8. Click the "Create My Painting" button.
9. A confirmation popup will appear if the order is successfully submitted, and an email will be sent to you and the service provider.
