# r1n Personal Website

A stylish personal link page with background music.

## Setup Instructions

1. **Add your images:**
   - Place your profile picture as `pfp.jpg` in this folder
   - Place your background image as `bg.jpg` in this folder
   - Supported formats: .jpg, .png, .webp

2. **Customize content:**
   - Edit `index.html` to change:
     - Username (line ~223)
     - Bio (line ~226)
     - Discord link (line ~233)
     - YouTube link (line ~241)
     - Song title/artist (line ~361-362)
     - YouTube video ID (line ~345)

3. **Host on GitHub:**
   - Create a new GitHub repository
   - Upload all files to the repository
   - Go to Settings > Pages
   - Select "main" branch as source
   - Your site will be live at `https://yourusername.github.io/repository-name`

## Features

- Animated profile avatar with glow effect
- Social links with hover effects
- Background music (starts muted, unmutes on click)
- "Click to enter" overlay for browser autoplay compliance
- Responsive design
- Dark theme with red accent colors

## Music

The music plays from YouTube. To change the song:
1. Find your YouTube video ID (the part after `v=` in the URL)
2. Replace `N5ab9IUSiOM` on line 345 with your video ID
3. Update the song title and artist on lines 361-362
