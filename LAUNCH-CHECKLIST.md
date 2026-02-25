# 📋 Pre-Launch Checklist - Regularízate Digital

## 🔴 Critical (Must Fix Before Launch)

- [ ] **Update WhatsApp Number**
  - Current: `34900000000` (placeholder)
  - Files: `_layouts/default.html`, `index.html`, `arraigo-likelihood-engine.html`
  - Task: Replace with your actual WhatsApp Business number

- [ ] **Update Email Address**
  - Current: `hola@regularizate.digital`
  - Verify email authentication (SPF, DKIM, DMARC)
  - Add to contact forms

- [ ] **Add Google Analytics**
  - _config.yml: Update `google_analytics_id`
  - Add tracking to layout template
  - Set up conversion goals

- [ ] **SSL/HTTPS Certificate**
  - Ensure domain has valid SSL
  - Redirect HTTP → HTTPS

- [ ] **Favicon Update**
  - Current: Inline SVG with "R"
  - Consider creating favicon.ico, apple-touch-icon.png

## 🟡 Important (Complete Before Going Live)

- [ ] **Legal Pages**
  - [ ] Privacy Policy (`/privacidad/`)
  - [ ] Terms of Service (`/terminos/`)
  - [ ] Cookie Policy (`/cookies/`)

- [ ] **Email Forms Integration**
  - Likelihood engine TODO: Connect to your API
  - Backend endpoint: `/api/capture-lead`
  - Payload: `{ email, answers, score }`

- [ ] **Calendly Integration**
  - Update Calendly link in:
    - `arraigo-likelihood-engine.html` (thank you screen)
    - Create actual Calendly account

- [ ] **WhatsApp Automation**
  - Consider WhatsApp Business API for better tracking
  - Set up auto-responses
  - Assign team members

- [ ] **Domain & DNS**
  - CNAME record points to: www.regularizate.digital
  - Verify CNAME in `_config.yml`
  - Update MX records for email

## 🟢 Recommended (Nice to Have)

- [ ] **Analytics Setup**
  - [ ] Google Analytics 4
  - [ ] Hotjar for session recording
  - [ ] Conversion funnels tracking

- [ ] **Social Media Links**
  - [ ] Instagram: `@regularizate` (in schema.org)
  - [ ] LinkedIn company page
  - [ ] TikTok (optional)

- [ ] **Email Marketing**
  - [ ] Mailchimp/ConvertKit integration
  - [ ] Welcome sequence
  - [ ] Case study emails

- [ ] **Performance Monitoring**
  - [ ] Page Speed Insights monitoring
  - [ ] Core Web Vitals tracking
  - [ ] Error tracking (Sentry)

- [ ] **Language Support**
  - [ ] Spanish ✅ (Complete)
  - [ ] English (Optional)
  - [ ] French (Optional)

## 🧪 Testing Checklist

### Desktop Testing
- [ ] Chrome (latest)
- [ ] Firefox (latest)
- [ ] Safari (latest)
- [ ] Edge (latest)
- [ ] Full page screenshot @ 1920x1080
- [ ] Zoom at 200%

### Mobile Testing
- [ ] iPhone 12/13 (iOS)
- [ ] iPhone SE (small screen iOS)
- [ ] Pixel 5 (Android)
- [ ] Tablet (iPad/Android tab)
- [ ] Touch interactions all responsive

### Accessibility Testing
- [ ] WAVE browser extension (no errors)
- [ ] Lighthouse Accessibility score ≥90
- [ ] Keyboard navigation (Tab, Enter, Escape)
- [ ] Screen reader (NVDA/JAWS on Windows, VoiceOver on Mac)

### SEO Testing
- [ ] Meta tags present and unique
- [ ] Open Graph preview (Facebook/LinkedIn)
- [ ] Twitter Card preview
- [ ] Mobile-friendly test (Google)
- [ ] Structured data (Schema.org validator)

### Forms Testing
- [ ] Email validation (valid & invalid)
- [ ] Quiz flow completion
- [ ] Likelihood calculation (all scenarios)
- [ ] Error messages display
- [ ] Success messages display

## 📝 Content Review

- [ ] Disclaimer language reviewed by lawyer
- [ ] All WhatsApp links have proper pre-fill text
- [ ] No spelling errors (Spanish spell-check)
- [ ] URLs are canonical
- [ ] All external links open in new tabs

## 🚀 Deployment

1. **Pre-Deployment**
   ```bash
   # Build Jekyll site
   bundle exec jekyll build
   
   # Test locally
   bundle exec jekyll serve
   # Visit http://localhost:4000
   ```

2. **Deploy to Production**
   - Push to main branch (if using GitHub Pages)
   - OR upload to web server
   - Verify HTTPS is active

3. **Post-Deployment Verification**
   - [ ] Site loads without errors
   - [ ] Links work (all internal & external)
   - [ ] Forms submit properly
   - [ ] WhatsApp links open
   - [ ] Mobile looks perfect
   - [ ] Analytics fires correctly

## 📞 Contact Information Update Locations

When you update your contact details, update in **ALL** these files:

1. `_config.yml` - Site email
2. `_layouts/default.html` - Footer & WhatsApp button
3. `index.html` - WhatsApp CTA
4. `arraigo-likelihood-engine.html` - WhatsApp link

**Pattern**: Search for `hola@regularizate.digital` and `34900000000`

---

## 🎯 Launch Readiness Scoring

- **Without Critical fixes**: ⚠️ **NOT READY**
- **With Critical fixes**: 🟡 **80% Ready**
- **With Important fixes**: 🟢 **95% Ready**
- **With Recommended items**: ⭐ **100% Excellent**

---

**Last Updated**: Feb 25, 2026
**Status**: Ready for Optimization | Pending Integration
