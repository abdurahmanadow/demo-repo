# Social Media Content Calendar Generator

A powerful AI-powered web application that generates 30 days of optimized social media content for LinkedIn and X (Twitter).

## Features

### Input Interface
- **Content Type Selector**: Choose from Thought leadership, Case studies, Career advice, Growth tactics, Company teardowns, or Success stories
- **Expertise Area Selector**: Select from Growth Marketing, User Acquisition, Sales, AdTech, Customer Success, or Business Development
- **Tone Selector**: Professional, Conversational, Educational, or Inspirational
- **Platform Selector**: Generate content for LinkedIn, X (Twitter), or both platforms

### Content Generation
- Generates 30 days of diverse, high-quality content
- **Content Mix**: 40% educational, 30% storytelling, 20% engagement, 10% promotional
- **LinkedIn Content**: Professional posts (1300-2000 chars), carousel topics (8-10 slides), article ideas
- **X Content**: Threads (3-7 tweets), standalone tweets (280 chars max), engagement tweets
- Includes optimal posting times for each platform

### Output Features
- **Calendar View**: Color-coded content types for easy visualization
- **Character Counts**: Real-time character counts for all posts
- **Copy to Clipboard**: One-click copying for individual posts and threads
- **Edit Mode**: Customize any generated content with built-in JSON editor
- **Export Options**: Download your calendar as CSV or PDF

### Design
- Warm, professional color palette (#F5E6D3, #FF8C42, #FFB84D, #2C3E50)
- Clean, modern UI with Inter font family
- Fully responsive design (mobile-first)
- Smooth animations and transitions

## Technical Stack

- **Frontend**: React 18 (via CDN)
- **Styling**: Tailwind CSS
- **AI Integration**: Anthropic API (Claude Sonnet 4.5)
- **State Management**: React Hooks
- **Export**: jsPDF for PDF generation
- **Build**: No build step required - runs directly in browser

## Getting Started

### 1. Open the Application

Simply open `index.html` in your web browser. No installation or build process required!

### 2. Set Up API Key

1. Get your Anthropic API key from [console.anthropic.com](https://console.anthropic.com/)
2. Enter it in the "API Configuration" section
3. Click "Save API Key" (it will be stored locally in your browser)

### 3. Generate Content

1. Select your content preferences:
   - Choose a content type that matches your focus
   - Select your area of expertise
   - Pick the tone that fits your brand
   - Choose your target platform(s)

2. Click "Generate 30-Day Calendar"

3. Wait 30-60 seconds while AI generates your content

### 4. Use Your Content

- **View**: Browse all 30 days in the color-coded calendar grid
- **Copy**: Click "Copy" buttons to copy individual posts to clipboard
- **Edit**: Click the ✏️ icon to customize any post
- **Export**: Download your entire calendar as CSV or PDF

## Content Distribution

Each generated calendar automatically includes:

- **12 Educational Posts** (40%): How-to guides, tutorials, insights
- **9 Storytelling Posts** (30%): Case studies, success stories, experiences
- **6 Engagement Posts** (20%): Questions, polls, community discussions
- **3 Promotional Posts** (10%): Product features, announcements, offers

## Platform-Specific Features

### LinkedIn
- Professional posts optimized for 1300-2000 characters
- Carousel slide outlines (8-10 slides)
- Article ideas for LinkedIn articles
- Optimal posting times

### X (Twitter)
- Multi-tweet threads (3-7 tweets per thread)
- Standalone tweets (max 280 characters)
- Engagement-focused tweets
- Platform-specific best practices

## Privacy & Security

- Your API key is stored only in your browser's local storage
- No backend server - all processing happens client-side
- API calls go directly from your browser to Anthropic's servers
- Your content is never stored on any server

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

## Troubleshooting

**"Please enter your Anthropic API key first"**
- Make sure you've entered and saved your API key in the configuration section

**"API Error: ..."**
- Check that your API key is valid
- Ensure you have credits in your Anthropic account
- Check your internet connection

**Content generation takes too long**
- Generating 30 days of content typically takes 30-60 seconds
- If it times out, try again with a stable internet connection

**Export doesn't work**
- Make sure you have generated content first
- Check that your browser allows file downloads

## Example Use Cases

1. **Content Creators**: Plan a month of content in minutes
2. **Marketing Teams**: Maintain consistent brand voice across platforms
3. **Entrepreneurs**: Build thought leadership without daily ideation
4. **Agencies**: Generate content for multiple clients efficiently
5. **Job Seekers**: Create professional content to boost visibility

## Tips for Best Results

1. **Be Specific**: Choose content types and expertise areas that closely match your niche
2. **Review & Edit**: Use the edit feature to personalize generated content
3. **Mix It Up**: Try different tone and platform combinations
4. **Schedule Smart**: Use the suggested posting times for maximum engagement
5. **Iterate**: Generate multiple calendars and cherry-pick the best content

## License

This project is open source and available for personal and commercial use.

## Support

For issues, questions, or feature requests, please open an issue on the repository.

---

**Built with ❤️ using React, Tailwind CSS, and Claude AI**
