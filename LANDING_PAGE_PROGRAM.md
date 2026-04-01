# Landing Page Build Program — autoresearch-style

## Objective
Build 3 SEO/GEO/AEO-optimized landing pages for Das Group LLC apps on dasgroupllc.com. These pages must rank in traditional search AND get cited by AI engines (ChatGPT, Perplexity, Gemini, Copilot).

## The 3 Apps

### 1. TrackFasts — Intermittent Fasting Timer
- **iOS App** (live on App Store)
- **Category**: Health & Fitness → Intermittent Fasting
- **URL path**: `/apps/trackfasts/`
- **Target keywords**: "intermittent fasting app", "fasting timer app", "best fasting app 2026", "fasting tracker iPhone", "intermittent fasting timer"
- **Market**: $885M+ market, 8%+ CAGR growth
- **Key features to highlight**: fasting timer, multiple fasting schedules (16:8, 18:6, 20:4, OMAD), progress tracking, fasting history, on-device — no cloud required
- **App Store link**: https://apps.apple.com/us/app/fasting-timer-trackfasts-ai/id6755202734
- **Real features from App Store listing**:
  - One-tap start for any protocol (16:8, 18:6, 20:4, OMAD)
  - Beautiful progress ring
  - Smart notifications when fast is complete
  - Streak tracking
  - Weight tracking with trend charts (Pro)
  - Science-based insights on autophagy, ketosis & fat burning (Pro)
  - 100% private — no accounts, no cloud, no tracking
  - Apple Watch companion app
  - Home screen & lock screen widgets
  - Works offline, always
  - Fasting education: what happens at each stage
  - Hydration reminders
  - Pricing: Free / $2.99 monthly / $19.99 yearly / $29.99 lifetime

### 2. Receipts — Scan Receipts  
- **iOS App** (live on App Store)
- **Category**: Productivity/Finance → Receipt Management
- **URL path**: `/apps/receipts/`
- **Target keywords**: "receipt scanner app", "scan receipts app", "best receipt scanner 2026", "receipt organizer iPhone", "tax receipt scanner", "AI expense tracker"
- **App Store link**: https://apps.apple.com/us/app/ai-receipt-organizer-scanner/id6755660040
- **Real features from App Store listing**:
  - AI-powered scanning: extracts merchant, date, amount, tax, category automatically
  - 91% accuracy on-device AI OCR
  - AI spending insights (alerts on spending spikes, savings opportunities, tax deduction reminders)
  - Automatic tax categories: meals, travel, office supplies, gas, healthcare, parking
  - Search & find any receipt by merchant, amount, date, or category
  - Export to PDF & CSV for accountants
  - Business trip tracking
  - Spending analytics
  - On-device processing, privacy-first
  - Free to try

### 3. QuickScan — Document Scanner
- **iOS App** (live on App Store)
- **Category**: Productivity → Document Scanning
- **URL path**: `/apps/quickscan/`
- **Target keywords**: "document scanner app", "scan documents iPhone", "best document scanner app 2026", "PDF scanner app", "mobile document scanner", "ID scanner app"
- **App Store link**: https://apps.apple.com/us/app/doc-scanner-quickscan-ai/id6755203492
- **Real features from App Store listing**:
  - Scan any document in 3 seconds
  - AI background removal and auto-crop
  - Text clarity enhancement
  - Works completely offline
  - Export as PDF or image
  - Perfect for ID scanning (driver's licenses, passports, insurance cards, business cards, receipts)
  - Smart tags: label documents by type (receipt, contract, ID, medical, tax)
  - No ads
  - Privacy-first: scans never leave device
  - Free: 5 scans/month, no account required
  - Pro: unlimited scans, batch scanning, OCR text extraction, cloud backup, signature tools
  - Pricing: Free / $4.99 monthly / $19.99 yearly

## Brand Guidelines (MUST follow)
- **Company**: Das Group LLC
- **Domain**: dasgroupllc.com
- **Primary color**: #5C6AC4
- **Gradient**: linear-gradient(135deg, #667eea 0%, #764ba2 100%)
- **Typography**: Inter (primary), system fonts fallback
- **NO fake statistics, download counts, or fabricated social proof**
- **NO "join thousands" or unsubstantiated claims**
- **Focus on what the app DOES, not comparisons to competitors**
- **Truthful, feature-focused copy**

## SEO Requirements (Traditional)
1. Proper `<title>` tag with primary keyword + brand
2. Meta description (150-160 chars) with keyword + value prop
3. Canonical URL
4. Open Graph tags (og:title, og:description, og:image, og:url)
5. Twitter Card meta tags
6. H1 with primary keyword, H2s with secondary keywords
7. Alt text on all images
8. Internal links to main site + other app pages
9. Schema.org structured data (SoftwareApplication + FAQ)
10. Mobile-responsive design
11. Fast loading (no heavy frameworks — vanilla HTML/CSS/JS, Tailwind CDN ok)
12. Semantic HTML (header, main, section, footer)

## GEO Requirements (Generative Engine Optimization)
1. **Definition-first opening sentence**: "[App Name] is a [category] app that [differentiator]" — AI engines extract opening lines as answer snippets
2. **Quantified statistics**: 2-3 data points per 300 words (use real metrics like "supports 6+ fasting schedules" not fake user counts)
3. **FAQ schema markup**: FAQ section with 5-8 questions people actually ask AI about this category
4. **Direct-answer content blocks**: 40-60 word self-contained paragraphs that directly answer a specific question
5. **Listicle-format feature sections**: numbered lists of features/benefits (AI engines cite lists 3-5x more)
6. **dateModified signals**: include lastmod in meta tags
7. **Brand knowledge consolidation**: clear product facts, features, pricing info in one authoritative place

## AEO Requirements (Answer Engine Optimization)  
1. **Speakable schema markup** on key paragraphs
2. **How-to sections** with step-by-step instructions (HowTo schema)
3. **Comparison-ready content**: "X vs Y" sections that AI can extract (but no bashing competitors)
4. **Natural language Q&A format**: questions phrased as users would ask ChatGPT/Perplexity
5. **Entity clarity**: clearly define what the app is, who it's for, what platform, what it costs

## Page Structure (each page)
```
1. Hero Section
   - App icon/visual
   - H1 with primary keyword  
   - Definition-first tagline (40-60 words)
   - CTA: "Download on the App Store" button
   
2. Key Features (numbered list — GEO optimized)
   - 5-7 features with H3 headings
   - Each feature: icon + title + 2-3 sentence description
   
3. How It Works (HowTo schema)
   - 3-4 numbered steps
   - Simple, clear language
   
4. Use Cases / Who It's For
   - 3-4 user personas with scenarios
   - Direct-answer blocks
   
5. FAQ Section (FAQ schema)
   - 6-8 real questions people ask AI about this category
   - Concise, authoritative answers
   
6. Download CTA
   - App Store badge/button
   - "Available on iPhone and iPad" 
   
7. Footer
   - Das Group LLC branding
   - Links: Privacy Policy, Terms, Support email
   - Links to other app pages
```

## Technical Constraints
- Static HTML files (site is on Netlify via GitHub)
- Each app gets its own directory under `/apps/`
- Use Tailwind CSS via CDN for styling (consistent with existing pages)
- No build step required
- All assets (icons, images) referenced locally or via CDN
- Must work without JavaScript (progressive enhancement)
- Lighthouse performance score target: 90+

## Existing Reference
Look at `/apps/profitpulse-demo/index.html` for the current page style, but make these new pages MUCH more SEO/GEO/AEO focused than the demo pages.

## File Structure
```
apps/
  trackfasts/
    index.html
  receipts/  
    index.html
  quickscan/
    index.html
```

## Validation Checklist (run after building each page)
- [ ] Title tag contains primary keyword
- [ ] Meta description < 160 chars with keyword
- [ ] H1 contains primary keyword
- [ ] Opening paragraph is definition-first format
- [ ] FAQ section has 6+ questions with FAQ schema
- [ ] SoftwareApplication schema present
- [ ] HowTo schema present  
- [ ] Open Graph tags complete
- [ ] Mobile responsive
- [ ] No fake statistics or social proof
- [ ] App Store link correct and working
- [ ] Internal links to other pages
- [ ] All text is truthful and feature-focused
