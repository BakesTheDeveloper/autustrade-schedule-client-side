# Client Deployment Guide (Vercel)

## What This Is
This is the **CLIENT-FACING** booking website where customers book appointments.

## Deployment Steps

### 1. Deploy to Vercel
- Already deployed at Vercel ✅
- This is a static site (HTML/CSS/JS only)

### 2. Update API URL
After deploying the admin service to Render, update the API URL in `js/app.js`:

Find this line:
```javascript
const API_URL = 'http://localhost:3000/api/appointments';
```

Replace with your Render admin URL:
```javascript
const API_URL = 'https://YOUR-ADMIN-SERVICE.onrender.com/api/appointments';
```

### 3. Redeploy
- Commit and push changes
- Vercel will auto-deploy

## Final URLs
- **Client Site (Vercel):** `https://your-client.vercel.app`
- **Admin API (Render):** `https://your-admin.onrender.com/api/appointments`

## Security
✅ Clients can only BOOK appointments (POST)  
✅ Clients CANNOT view, edit, or delete appointments  
✅ Only admin dashboard has full access
