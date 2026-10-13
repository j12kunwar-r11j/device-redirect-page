# Device Redirect Page

A simple and responsive webpage built using HTML, CSS, and JavaScript that detects reported device information and redirects users to different websites when they click a button.

## Features

- Attractive and responsive user interface.
- Gradient button with hover and click animations.
- Device detection using JavaScript.
- Conditional redirection to different websites.
- Simple and beginner-friendly project structure.

## Device-Based Redirection

| Detected Device | Redirect Website |
|---|---|
| Android | [Yahoo](https://www.yahoo.com) |
| iPhone | [Google](https://www.google.com) |
| MacBook | [Opera](https://www.opera.com) |
| Windows | [Firefox](https://www.mozilla.org/firefox/) |
| Other Devices | [Google](https://www.google.com) |

## Technologies Used

- **HTML5** – Webpage structure.
- **CSS3** – Styling, gradient buttons, shadows, and hover animations.
- **JavaScript** – Button click events, device detection, conditional logic, and URL redirection.

## Project Structure

```text
device-redirect-page/
├── button.html
└── README.md
```

- `button.html` – Original webpage containing the device redirection logic.
- `README.md` – Project documentation.

## How to Run Locally

1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Open `button.html` in your browser.
4. Click the **Open My Page** button to test the redirection.

No additional libraries or packages are required.

## Deployment

This project can be deployed as a static website using [Render](https://render.com/).

1. Upload the project files to GitHub.
2. Create a new Static Site on Render.
3. Connect your GitHub repository.
4. Set the publish directory to `.`.
5. Deploy the website and share the generated public URL.

## Important Notes

- Device detection relies on information reported by the browser and may not identify every device accurately.
- The project redirects users to the selected website; it does not guarantee that a particular browser application, such as Opera or Firefox, will launch.
- An internet connection is required to access the external destination websites.

## Learning Objectives

This project demonstrates basic web development concepts, including:

- HTML elements and page structure.
- CSS styling and hover effects.
- JavaScript functions and event handling.
- `if / else if` conditional statements.
- `navigator.userAgent`.
- `window.location.href` for URL redirection.

## License

This project is available for learning and educational purposes. Add a license file if you want to specify formal reuse and distribution permissions.
