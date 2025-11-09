# Focus.io - A Creative Pomodoro Timer

A clean, creative, and responsive Pomodoro timer designed to help you focus. This app is built with **React** and **TailwindCSS** but runs as a **single `index.html` file**, requiring no installation or build steps.





##  How to Run

This project is a single, self-contained file. No `npm install` or build tools are needed.

1.  **Download:** Get the `index.html` file.
2.  **Open:** Double-click the `index.html` file to open it in your favorite web browser (like Chrome, Firefox, or Edge).

That's it! The app will run.

> **Note on Permissions:** The app uses:
> * **Desktop Notifications:** To alert you when a timer finishes.
> * **Audio:** To play the alarm and ambient sounds.
>
> Your browser will likely ask you to "Allow" these features. Please do so for the best experience.



##  Features

* **Dynamic Gradient Themes:** The UI beautifully changes color based on your mode.
    * **Focus:** A warm, encouraging "sunset" gradient.
    * **Break:** A calm, refreshing "ocean" gradient.
* **Full Pomodoro Logic:** Standard 25/5/15-minute cycles (Focus, Short Break, Long Break).
* **Custom Settings:** Click the **`⚙️` (gear)** icon to change the duration of all timers and the number of sessions before a long break. All settings are saved in your browser.
* **Ambient Sounds:** Click the **`🎵` (music)** icon to open the sound menu.
    * Play four different background sounds (Rain, Forest, Coffee Shop, White Noise).
    * Control the volume with the built-in slider.
* **Desktop Notifications:** Get a native OS notification when your timer is up, even if the window is minimized.
* **Fully Responsive:** The design looks great on both large desktop screens and small mobile phones.
* **Zero Installation:** Runs 100% in the browser from a single file.



##  Technology Stack

This app runs without a build step by loading all necessary libraries from a CDN:

* **React:** For the UI and state management.
* **React-DOM:** To mount the React app to the DOM.
* **Babel (Standalone):** To transpile the modern JSX and React code live in the browser.
* **TailwindCSS (CDN):** For all styling and the responsive layout.
* **Font Awesome:** For all icons.



##  File Structure

The entire application is contained in one file: