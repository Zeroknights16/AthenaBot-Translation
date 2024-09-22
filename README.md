# Translation Files for Athena Bot

Welcome to the official repository for **translation files** for AthenaBot! This repository contains JSON files with English sentences that need to be translated into other languages. You can contribute translations directly using GitHub’s built-in editor without needing any special tools or software.

## Table of Contents

1. [Overview](#overview)
2. [How to Contribute Using GitHub's Editor](#how-to-contribute-using-githubs-editor)
3. [Pull Request Guidelines](#pull-request-guidelines)

---

## Current State
* 🇬🇧 English Translation: 100% complete (Default language)
* 🇵🇱 Polish Translation: 100% complete
* 🇩🇪 German Translation: 75% complete
* 🇪🇸 Spanish Translation: 1% complete
* 🇫🇷 French Translation: 0% complete
* 🇳🇱 Dutch Translation: 0% complete
* 🇹🇷 Turkish Translation: 0% complete
* 🇵🇹 Portugese Translation: 0% complete

---

## Contributors
* werdykt (1047891236901630092) » Polish Translation **100%**
* EinfachMaiki (1211700590271266867) » German Translation **75%**
* neurological. (741947344379183184) » Spanish Translation **1%**

---

## Overview

This repository contains **JSON** files with strings written in English that are used by the bot. The goal is for contributors to translate these English strings into other languages directly using GitHub's web interface.

- **File Format**: All files are in `.json` format.
- **Goal**: Translate the English sentences inside the JSON files while keeping the file structure intact.


## How to install one of the translation packages?

Download the latest language pack at the releases tab. Unzip the directory and drop it into your "lang" directory of Athena. Set "enable_translations" in your common.json file to true and restart. If you have any questions please create a ticket.


## How to Contribute Using GitHub's Editor

You don’t need any special software to contribute; you can use GitHub's built-in editor to translate the JSON files directly in your browser. Here's how:

### Step 1: Fork the Repository
1. Navigate to the top right corner of this page and click on the `Fork` button. This will create a copy of this repository in your own GitHub account.

### Step 2: Open Your Fork
1. After forking, go to your GitHub account and find the forked repository. It should have the same name as this repository, but under your username.
2. Click on the repository to open it.

### Step 3: Find the File You Want to Translate
1. In the repository, navigate to the `translations` folder where you will find the JSON files.

### Step 4: Edit the File in the GitHub Editor
1. Click on the name of the JSON file to open it.
2. In the file view, click on the small pencil icon at the top right to enter **edit mode**.

### Step 5: Translate the English Sentences
1. Inside the file, you'll see key-value pairs like this:
    ```json
    {
        "greeting": "Hello",
        "farewell": "Goodbye",
    }
    ```
    The text on the right (in quotes) is the **English** text that you will be translating.
    
2. Replace the **English** text on the right side with your translation, while keeping the structure (the keys on the left) the same. For example, if you're translating into Spanish, it would look like this:
    ```json
    {
        "greeting": "Hola",
        "farewell": "Adiós",
    }
    ```

3. Do **not** change the keys on the left (e.g., `"greeting"`, `"farewell"`), only the text on the right (e.g., `"Hello"`, `"Goodbye"`).

### Step 6: Commit Your Changes
1. Once you've finished translating, scroll down to the bottom of the page.
2. You will see a section called **Commit changes**. Add a short message describing your changes (e.g., "Translated greeting and farewell to Spanish").
3. Select the option **"Create a new branch for this commit"** and name the branch something descriptive like `spanish-translation`.
4. Click **Propose changes** to save your work.

### Step 7: Open a Pull Request
1. After proposing changes, GitHub will prompt you to open a **pull request**. This is where you ask the maintainers to review and merge your translation into the main project.
2. Click **Create pull request**, provide a brief description, and submit it.

That’s it! The maintainers will review your contribution and, once approved, your translation will be added to the project.

---

## Pull Request Guidelines

- **Accuracy**: Make sure the translations are accurate and contextually correct.
- **Do Not Change Structure**: Do not alter the JSON keys or the structure of the file, only the text values.

---