# Historical Vessels - Hong Kong Maritime Collection

A static website showcasing the history of Hong Kong's maritime vessels through interactive timelines.

## Project Structure

- `hk-vessels-museum-homepage.html` - Main homepage
- `so-fung-timeline.html` - So Fong vessel timeline
- `star-ferry-timeline-elegant.html` - Star Ferry timeline (elegant version)
- `star-ferry-timeline-ultimate.html` - Star Ferry timeline (ultimate version)
- `timeline-img/` - Image assets for timelines
- `worldmap.png` - World map background image

## Deployment to Vercel

### Option 1: Deploy via Vercel CLI (Recommended)

1. **Install Vercel CLI** (if you haven't already):
   ```bash
   npm install -g vercel
   ```

2. **Login to Vercel**:
   ```bash
   vercel login
   ```

3. **Deploy the project**:
   ```bash
   vercel
   ```
   
   Follow the prompts:
   - Set up and deploy? **Yes**
   - Which scope? (select your account)
   - Link to existing project? **No** (for first deployment)
   - Project name? (press Enter for default or enter a custom name)
   - Directory? (press Enter for current directory)
   - Override settings? **No**

4. **For production deployment**:
   ```bash
   vercel --prod
   ```

### Option 2: Deploy via GitHub + Vercel Dashboard

1. **Push your code to GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin <your-github-repo-url>
   git push -u origin main
   ```

2. **Connect to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Click "Add New Project"
   - Import your GitHub repository
   - Vercel will auto-detect it as a static site
   - Click "Deploy"

### Option 3: Drag & Drop (Quick Test)

1. Go to [vercel.com](https://vercel.com)
2. Sign in to your account
3. Click "Add New Project"
4. Use the "Upload" option and drag your project folder

## Accessing Your Pages

Once deployed, your pages will be accessible at:
- Homepage: `https://your-project.vercel.app/`
- So Fong Timeline: `https://your-project.vercel.app/so-fung`
- Star Ferry Timeline: `https://your-project.vercel.app/star-ferry`
- Star Ferry Ultimate: `https://your-project.vercel.app/star-ferry-ultimate`

You can also access pages directly:
- `https://your-project.vercel.app/so-fung-timeline.html`
- `https://your-project.vercel.app/star-ferry-timeline-elegant.html`
- etc.

## Sharing Your Site

After deployment, Vercel will provide you with:
- **Production URL**: `https://your-project.vercel.app` (permanent, updates on each deploy)
- **Preview URLs**: Generated for each deployment (great for sharing specific versions)

Simply share the production URL with anyone you want to show the site to!

## Notes

- This is a static site, so no build process is required
- All images and assets are included in the repository
- Vercel automatically handles HTTPS, CDN, and global distribution
- Free tier includes unlimited deployments and bandwidth

