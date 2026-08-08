# WhoUnfollowed.Me 🔍

**WhoUnfollowed.Me** is a privacy-first, client-side web application that helps you analyze your Instagram followers and following lists.

Since everything runs entirely in your web browser, **your data never leaves your device**. No servers, no databases — just quick and private insights!

## ✨ Features

- **100% Private:** Your files are processed locally on your computer.
- **Who Doesn't Follow Back:** Easily see a list of accounts you follow that don't follow you back.
- **Fans (You Don't Follow):** See who follows you that you haven't followed back.
- **Mutuals:** View the friends where the feeling is mutual!
- **Large Account Support:** Automatically supports uploading multiple `followers.json` files if Instagram split your data into several parts.

## 📥 How to Get Your Instagram Data

To use this app, you will need to request a copy of your data from Instagram.

1. Open the Instagram app or website and go to your **Profile**.
2. Tap the menu and go to **Settings and privacy > Your activity**.
3. Scroll down and select **Download your information**.
4. Request a download and make sure you select **JSON** as the format.  
   > **Note:** HTML will not work.
5. Once your data is ready, Instagram will send you an email. Download and extract the `.zip` file.
6. Look for the folder named `followers_and_following`. This is where your `.json` files are located!

## 🚀 How to Use the App

1. Open the **WhoUnfollowed.Me** web app.
2. Click the first upload box and select your `followers_1.json` file.
   > **Large accounts:** If you also have a `followers_2.json` file, click the **"+ I have a followers_2.json file"** button to add more upload slots.
3. Click the second upload box and select your `following.json` file.
4. Click **Analyze My Data** to instantly see your results!

## 🌐 How to Host on GitHub Pages

This app is built as a single `index.html` file, making it incredibly easy to host for free on GitHub Pages.

1. Create a new **public repository** on your GitHub account.
2. Upload the `index.html` file to the `main` branch of your repository.
3. Go to your repository's **Settings** tab.
4. On the left sidebar, click **Pages**.
5. Under **Build and deployment**, change the source branch from `None` to `main` (or `master`) and click **Save**.
6. Wait a minute or two, and GitHub will provide you with a live link to your new website!

## 🛠️ Built With

- **React**
- **Tailwind CSS**
- CDN-based dependencies
- No backend or database required

---

### 🔒 Privacy First

Your Instagram data is processed **entirely in your browser**. Nothing is uploaded to or stored on a server.
