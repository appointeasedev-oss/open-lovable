# ARAS - AI Website Builder

Build stunning websites instantly with AI. ARAS is a powerful AI-driven website builder that lets you create React applications through natural language.

## Setup

1. **Clone & Install**
```bash
git clone <your-repo-url>
cd aras-builder
npm install
```

2. **Add `.env`**

```env
# =================================================================
# REQUIRED
# =================================================================
OPENROUTER_API_KEY=your_openrouter_api_key  # https://openrouter.ai

# =================================================================
# SUPABASE (included for data persistence)
# =================================================================
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key

# =================================================================
# SANDBOX PROVIDER - Choose ONE: Vercel (default) or E2B
# =================================================================
SANDBOX_PROVIDER=vercel  # or 'e2b'

# Option 1: Vercel Sandbox (default)
# Run `vercel link` then `vercel env pull` to get VERCEL_OIDC_TOKEN automatically
VERCEL_OIDC_TOKEN=auto_generated_by_vercel_env_pull

# Option 2: E2B Sandbox
# E2B_API_KEY=your_e2b_api_key      # https://e2b.dev
```

3. **Run**
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

## Features

- **AI-Powered**: Uses OpenRouter with multiple free AI models
- **Website Builder**: Create React applications through natural language
- **Real-time Preview**: See your changes instantly in a sandbox environment
- **Multiple Models**: Choose from DeepSeek, Llama, Gemini, Qwen, and more
- **Data Persistence**: Built-in Supabase integration for storing your projects

## License

MIT
