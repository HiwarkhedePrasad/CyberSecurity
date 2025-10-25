# 🖼️ Image Steganography Web App

A simple browser-based **image steganography** project that lets you **hide and reveal secret messages inside images** using JavaScript and HTML5 Canvas.

---

## 📂 Project Structure

```
├── index.html   # Main web page UI
├── style.css    # Basic styling
├── script.js    # Core encoding/decoding logic
```

---

## ⚙️ How It Works

1. **Upload an image** using the file input.
2. **Type a secret message** into the text box.
3. Click **“Encode Message”** — the message is hidden inside the image’s pixel data.
4. Click **“Download Image”** to save the encoded image.
5. To retrieve the hidden text, upload the encoded image and click **“Decode Message.”**

---

## 🧠 Technical Overview

* Uses the **Least Significant Bit (LSB)** method on the **red channel** of each pixel to store message bits.
* The message ends with a `|` character as a termination marker.
* Encoding and decoding are handled entirely in the browser via **HTML Canvas API**.
* No external libraries required.

---

## 🚀 How to Run

1. Download or clone the project folder.
2. Open `index.html` in any modern browser.
3. Use the buttons to encode and decode messages.

---

## 🧩 Example Workflow

1. Upload an image.
2. Enter message: `Hello World`.
3. Encode → Download image.
4. Upload encoded image → Decode → Output:

   ```
   🕵️‍♀️ Hidden Message: Hello World
   ```

---

## 📜 License

Free to use for educational and personal projects. No warranty or liability implied.
