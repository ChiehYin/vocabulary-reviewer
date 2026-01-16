# Vocabulary Reviewer

A simple, elegant vocabulary learning tool to help you review and memorize new English words with example sentences.

## Features

- 📝 Add new words with example sentences
- 📱 Mobile-friendly responsive design
- 🔄 Daily review system (last 7 words + 5 random words)
- 💾 Automatic data persistence using localStorage
- ✏️ Edit and delete words
- 🎯 Daily review prompts

## How to Use on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in (or create an account)
2. Click the **"+"** button in the top right corner
3. Select **"New repository"**
4. Name your repository (e.g., `vocabulary-reviewer`)
5. Make sure it's set to **Public**
6. Click **"Create repository"**

### Step 2: Upload the File

1. In your new repository, click **"uploading an existing file"**
2. Drag and drop the `index.html` file
3. Click **"Commit changes"**

### Step 3: Enable GitHub Pages

1. Go to your repository **Settings**
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**, select **"main"** branch
4. Click **"Save"**
5. Wait a few minutes, then visit: `https://YOUR-USERNAME.github.io/vocabulary-reviewer/`

## Using the App

1. **Add Words**: Enter a new word and example sentence, then click "Add Word"
2. **Daily Review**: Each day you'll see a prompt to review your vocabulary
3. **Edit/Delete**: Click the edit or trash icon on any word to modify or remove it
4. **View Review**: Click "View Review" anytime to see your daily word selection

## Data Storage

Your vocabulary data is stored locally in your browser using localStorage. This means:
- ✅ Your data persists between sessions
- ✅ Works offline after first load
- ⚠️ Data is device-specific (use the same browser/device)
- ⚠️ Clearing browser data will erase your vocabulary

## Technology

- React 18
- Tailwind CSS
- Browser localStorage API

## License

Free to use and modify for personal or educational purposes.
