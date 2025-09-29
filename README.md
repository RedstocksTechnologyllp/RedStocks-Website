# RedStocks - Landing Page Project

This repository contains a modern and secure landing page for "RedStocks," a personal project demonstrating a website for a conceptual quantitative investment firm that uses autonomous AI agents.

This is a static website built with vanilla HTML, CSS, and JavaScript, focusing on a clean design, strong security practices, and a professional user experience.

---

### Pages Included

1.  **`index.html`**: The main landing page that introduces the firm's concept, process, security, and includes a working contact form.
2.  **`philosophy.html`**: A secondary page that details the core principles and guiding beliefs of the firm.

---

### Key Features

* **Fully Responsive Design**: Adapts seamlessly to all screen sizes, from mobile devices to desktops.
* **Security-First Approach**: Implemented with a strong Content Security Policy (CSP), security headers (`X-Frame-Options`, etc.), and SRI checks on external libraries.
* **Static & Lightweight**: No backend required, ensuring fast load times and easy, secure hosting on platforms like GitHub Pages.
* **Functional Contact Form**: Integrated with Formspree for reliable and secure handling of form submissions.
* **Clean Codebase**: Uses vanilla technologies with no external frameworks for maximum simplicity and performance.

---

### Technology Stack

* HTML5
* CSS3 (with CSS Variables)
* Vanilla JavaScript
* [Formspree](https://formspree.io/) (for the contact form)
* [Font Awesome](https://fontawesome.com/) (for icons)
* [Google Fonts](https://fonts.google.com/) (for typography)

---

## Getting Started

To get this project running on your own, follow these steps.

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/redstocks.git](https://github.com/your-username/redstocks.git)
    ```

2.  **Configure the Contact Form:**
    The only configuration needed is to link the contact form to your own Formspree account. Open `index.html` and find the `<form>` tag. Replace the `action` URL with your own Formspree endpoint.

    ```html
    <form action="[https://formspree.io/f/xrbypvan](https://formspree.io/f/xrbypvan)" method="POST" class="contact-form">

    <form action="[https://formspree.io/f/your_unique_code](https://formspree.io/f/your_unique_code)" method="POST" class="contact-form">
    ```

3.  **Open in Browser:**
    You can now open the `index.html` file directly in your web browser to see the site.

---

### File Structure

The project uses a minimal file structure for simplicity.
