# 💕 Sorry Letter Website - Customization Guide

## Setup Instructions
# My Video tutorials : 
---> For getting the sharable link : https://youtu.be/bFCnDsQwNvA


### 1. Install Required Software

VS Code Installation:
- Download and install VS Code if you don't have it
- Tutorial: https://youtu.be/3eCmc0t6aqA?si=TkV0bVEz_95FbMmi

Node.js Installation:
- Download and install Node.js if you don't have it
- Tutorial: https://youtu.be/uCgAuOYpJd0?si=2ICwr3Ih1P_ru9KA

⚠️ Important: Both VS Code and Node.js are required!

### 2. Open the Project

1. Open the "project-sorry-2" folder in VS Code

2. Open terminal in VS Code (Terminal → New Terminal)

4. Type this command and press Enter:
   npm i

   after that, type this command: 

   npm run dev

   **If you get a script error on Windows, run this :**

   Set-ExecutionPolicy -Scope CurrentUser Unrestricted


   after that, try again the commands

5. You'll get a local view link
6. Ctrl + Click on the localhost link to view your website!


## 🎨 Customization Guide

### 📝 How to Change Main Content

Go to src folder. 
edit the text inside of textConfig.js file. 

## How to change Music 
Go to music folder. 
paste your new music there.
delete previous musics.
update your music names as music1.mp3, music2.mp3, music3.mp3

To change music names -> Go to app.tsx file, line 470


## 🌐 How to Share Your Website
Watch my tutorial:  https://youtu.be/bFCnDsQwNvA

### Vercel
1. Push your code to GitHub
2. Connect your GitHub to [vercel.com](https://vercel.com)
3. Deploy automatically


## 🆘 Common Issues & Solutions

### ❌ "Cannot find module" errors
Solution: Run `npm install` to install all dependencies

### ❌ Images not loading
Solutions:
1. Make sure images are in `src/images/` folder
2. Check the import paths match your file names
3. Supported formats: `.jpg`, `.png`, `.gif`

### ❌ Music not playing
Solutions:
1. Check if `music.mp3` is in the `src/` folder
2. Some browsers block autoplay (user needs to click music button)
3. File size should be under 10MB

### ❌ Changes not showing
Solutions:
1. Save your files (Ctrl+S)
2. The dev server should auto-reload
3. Hard refresh browser (Ctrl+Shift+R)


## 🎉 Final Tips

- Test everything before sharing the link
- Keep backups of your original content
- Personal touch - add inside jokes and special memoriest

## 📞 Need Help?

If you're stuck:
1. Check the common issues section above
2. Make sure you saved all files
3. Try restarting the development server
4. Contact if needed help still

