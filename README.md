# Dr. Take Profit CRM

High-performance CRM for trading education businesses. Built for Meta Ads integration with scalable architecture for unlimited lead sources.

## 🚀 Quick Deploy

### Option 1: One-Click Vercel Deploy (Frontend)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/dr-take-profit-crm&env=NEXT_PUBLIC_API_URL,JWT_SECRET&project-name=dr-take-profit-crm&repository-name=dr-take-profit-crm)

### Option 2: Railway Deploy (Backend + Database)
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/your-template-id)

### Option 3: Local Development

```bash
# 1. Clone repository
git clone https://github.com/yourusername/dr-take-profit-crm.git
cd dr-take-profit-crm

# 2. Install dependencies
npm install

# 3. Set up environment
cp .env.example .env
# Edit .env with your credentials

# 4. Start database and redis
docker-compose up -d

# 5. Run migrations
npm run db:migrate

# 6. Start development
npm run dev
