# 🚀 Vercel Deployment Guide

This guide will help you deploy your Weather App to Vercel in just a few minutes!

## Prerequisites

- A GitHub account
- An OpenWeatherMap API key (free)

## Step 1: Get Your API Key

1. Visit [OpenWeatherMap](https://openweathermap.org/api)
2. Sign up for a free account
3. Go to your dashboard
4. Copy your API key

## Step 2: Deploy to Vercel

### Option A: Deploy from GitHub (Recommended)

1. **Fork this repository**:
   - Click the "Fork" button on GitHub
   - This creates a copy in your account

2. **Go to Vercel**:
   - Visit [vercel.com](https://vercel.com)
   - Sign up/Login with your GitHub account

3. **Create New Project**:
   - Click "New Project"
   - Import your forked repository
   - Click "Deploy"

4. **That's it!** Your app is now live at `https://your-project.vercel.app`

### Option B: Deploy with Vercel CLI

1. **Install Vercel CLI**:
   ```bash
   npm i -g vercel
   ```

2. **Clone and deploy**:
   ```bash
   git clone <your-repo-url>
   cd weather-app
   vercel
   ```

3. **Follow the prompts** and your app will be live!

## Step 3: Configure Your App

1. **Visit your deployed app**
2. **Enter your API key** when prompted
3. **Start searching** for weather information!

## Custom Domain (Optional)

1. Go to your Vercel dashboard
2. Select your project
3. Go to "Settings" → "Domains"
4. Add your custom domain
5. Follow the DNS configuration instructions

## Environment Variables (Advanced)

If you want to use environment variables instead of user input:

1. In your Vercel dashboard, go to "Settings" → "Environment Variables"
2. Add: `OPENWEATHER_API_KEY` = your API key
3. Update the code to use `process.env.OPENWEATHER_API_KEY`

## Troubleshooting

### Common Issues:

1. **"Invalid API key" error**
   - Make sure your API key is correct
   - API keys may take a few hours to activate after registration

2. **App not loading**
   - Check the Vercel deployment logs
   - Ensure all files are committed to GitHub

3. **CORS errors**
   - The app is configured to work with OpenWeatherMap API
   - No additional CORS configuration needed

## Support

- [Vercel Documentation](https://vercel.com/docs)
- [OpenWeatherMap API Docs](https://openweathermap.org/api)
- [GitHub Issues](https://github.com/your-repo/issues)

---

**Your weather app is now live and ready to use!** 🌤️ 