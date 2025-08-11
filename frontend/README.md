# 🤖 AI Chat Interface Frontend

Welcome to the **dopest** AI chat interface you've ever seen! This is a sleek, professional frontend built with Next.js that connects to your FastAPI backend for an amazing AI chat experience.

## ✨ Features

- **Real-time streaming responses** - Watch the AI think in real-time! 🧠
- **Professional UI/UX** - Clean, modern design that looks great on any device
- **Dark mode support** - Because your eyes deserve the best 🌙
- **Configurable settings** - Customize your AI experience with different models and prompts
- **Secure API key handling** - Your secrets stay safe with password-style input fields
- **Responsive design** - Works perfectly on desktop, tablet, and mobile

## 🚀 Quick Start

### Prerequisites

Make sure you have these installed:
- **Node.js** (version 18 or higher) - [Download here](https://nodejs.org/)
- **npm** or **yarn** (comes with Node.js)

### Installation

1. **Navigate to the frontend directory:**
   ```bash
   cd frontend
   ```

2. **Install the dependencies:**
   ```bash
   npm install
   # or if you're a yarn person:
   # yarn install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   # or
   # yarn dev
   ```

4. **Open your browser** and go to [http://localhost:3000](http://localhost:3000)

### 🎯 Running the Complete App

To run the full application (frontend + backend), you'll need both servers running:

#### Terminal 1 - Backend API
```bash
# From the project root
cd api
pip install -r requirements.txt
python app.py
```
Your API will be running on `http://localhost:8000`

#### Terminal 2 - Frontend
```bash
# From the project root
cd frontend
npm install
npm run dev
```
Your frontend will be running on `http://localhost:3000`

## 🔧 Configuration

### Environment Variables

Create a `.env.local` file in the frontend directory to customize the backend URL:

```env
BACKEND_URL=http://localhost:8000
```

### API Key Setup

1. Get your OpenAI API key from [OpenAI Platform](https://platform.openai.com/api-keys)
2. Click the settings icon (⚙️) in the top-right corner of the app
3. Enter your API key in the "OpenAI API Key" field
4. Choose your preferred model and customize the system prompt
5. Start chatting! 🎉

## 🎨 Customization

### Available Models
- **GPT-4.1 Mini** (default) - Fast and efficient
- **GPT-4** - Most capable model
- **GPT-3.5 Turbo** - Good balance of speed and capability

### System Prompts
Customize how the AI behaves by modifying the "Developer Message" field. Some examples:
- `"You are a helpful coding assistant that writes clean, well-documented code."`
- `"You are a creative writing coach that helps improve storytelling."`
- `"You are a friendly customer service representative."`

## 🛠️ Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

### Project Structure

```
frontend/
├── app/                    # Next.js 13+ app directory
│   ├── api/               # API routes
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Main page component
├── package.json           # Dependencies and scripts
├── tailwind.config.js     # Tailwind CSS configuration
└── tsconfig.json          # TypeScript configuration
```

## 🌟 Pro Tips

1. **Use the settings panel** to save your preferred configuration
2. **Clear chat** when starting new conversations for better context
3. **Try different models** for different use cases
4. **Customize system prompts** to get more specific responses
5. **The interface is responsive** - try it on your phone! 📱

## 🚀 Deployment

This frontend is ready for deployment on Vercel! Just connect your GitHub repository and Vercel will automatically detect it's a Next.js app.

### Vercel Deployment
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Set the `BACKEND_URL` environment variable in Vercel
4. Deploy! 🎉

## 🐛 Troubleshooting

### Common Issues

**"Failed to get response" error:**
- Make sure your backend API is running on `http://localhost:8000`
- Check that your OpenAI API key is valid
- Verify your API key has sufficient credits

**Frontend won't start:**
- Make sure you're in the `frontend` directory
- Run `npm install` to install dependencies
- Check that Node.js version is 18 or higher

**Styling issues:**
- Clear your browser cache
- Make sure Tailwind CSS is properly installed

## 🤝 Contributing

Found a bug? Want to add a feature? We'd love your help! Just:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the MIT License.

---

**Happy chatting! 🎉** If you have any questions, feel free to reach out or check the main project README for more details.