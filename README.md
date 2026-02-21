# Emergency Protocol - Mental Health Crisis Toolkit

A personal mental health emergency response system designed for real crisis moments, not wellness blog aesthetics.

## What This Is

This is an interactive panic button/crisis management tool built specifically for someone with Complex PTSD who:
- Struggles to identify emotions in the body
- Has specific trigger patterns (like delayed reactions)
- Knows what destabilizes them vs. what helps
- Needs functional tools, not generic self-care content

## Features

### 🫀 Body Map
Interactive body diagram to identify physical sensations and connect them to emotional states. Helps when you can't name what you're feeling but can identify where you feel it.

### 🧠 State Check
Diagnostic tool to differentiate between:
- Flatline/Depression
- Dissociation
- Freeze response
- Activation/Anxiety
- Mixed/unclear states

### ⚡ Action Menu
Categorized by crisis level:
- **RED ALERT**: SI thoughts, can't think, immediate danger
- **ORANGE**: Dissociated, flatlined, numb
- **YELLOW**: Activated, angry, restless
- **GREEN**: Preventative maintenance

### 🫁 Somatic Resources
- YouTube channels (SheBreath, The Holistic Psychologist, etc.)
- Quick techniques (box breathing, butterfly hug, shaking, etc.)
- Specific exercise protocols

### 📝 Trigger Log
Track patterns over time. Records:
- Date and state
- Physical symptoms
- What happened
- When you noticed the response
- What helped

Uses localStorage so data persists on your device.

### 🚫 Don't Do This
Specific list of things that make it worse:
- Calling Samaritans (not your thing)
- Calling parents (they're triggers)
- Talking about feelings while crying
- Forcing productivity when flatlined
- etc.

## Setup Instructions

### Option 1: GitHub Pages (Recommended - Easiest)

1. Create a new repository on GitHub
2. Upload all HTML files to the repository
3. Go to Settings → Pages
4. Under "Source", select your main branch
5. Click Save
6. Your site will be live at: `https://[your-username].github.io/[repo-name]/`
7. **Bookmark this URL on your phone** for quick access

### Option 2: Local Files (Works Offline)

1. Download all HTML files to a folder on your device
2. Open `index.html` in any web browser
3. Bookmark the local file path for quick access
4. Works completely offline

### Option 3: Host Anywhere

These are static HTML files - you can host them on:
- Netlify (free, drag-and-drop)
- Vercel (free)
- Your own web server
- Any static site host

## Files Included

- `index.html` - Main dashboard/panic button
- `body-map.html` - Interactive body sensation map
- `state-check.html` - State diagnostic tool
- `actions.html` - Action menu by crisis level
- `resources.html` - Somatic exercises and YouTube links
- `log.html` - Trigger tracker (uses localStorage)
- `dont-do.html` - Things that make it worse

## Mobile Access

**THIS IS DESIGNED FOR MOBILE USE IN CRISIS.**

1. Once hosted, bookmark the URL on your phone's home screen
2. On iPhone: Safari → Share → Add to Home Screen
3. On Android: Chrome → Menu → Add to Home Screen
4. Now it's one tap away when you need it

## Data Storage

The Trigger Log uses browser localStorage, which means:
- ✅ Data stays on YOUR device only
- ✅ Works offline after first load
- ✅ Persists between sessions
- ❌ Clearing browser data will delete logs
- ❌ Data doesn't sync between devices

## Privacy & Security

- No analytics
- No tracking
- No external dependencies (except Google Fonts)
- No data sent anywhere
- Everything runs client-side in your browser
- Logs stored locally only

## Customization

The HTML is straightforward to edit:
- Change email addresses in `index.html` and `actions.html`
- Add/remove resources in `resources.html`
- Modify action lists in `actions.html`
- Update body areas in `body-map.html`

## Technical Notes

- Pure HTML/CSS/JavaScript (no frameworks)
- Mobile-responsive design
- Works in all modern browsers
- No build process required
- Brutalist/utilitarian aesthetic (intentional)

## Why This Exists

Generic mental health apps don't work when you're in crisis. They're designed for people who are "stressed," not people having SI thoughts at 4am. This is built for actual emergency moments with:

- No pastel bullshit
- No "you've got this!" platitudes
- Concrete, actionable steps
- Knowledge of what actually helps YOU
- Fast access to the right tool

## Emergency Contacts

Remember to update the email address in:
- `index.html` (emergency button)
- `actions.html` (red alert section)

Current placeholder: `anahi@therapist.com`

## Support

If you're in immediate danger:
- UK: 999 or go to A&E
- Samaritans: 116 123 (though you've noted this doesn't help you personally)
- Crisis text line: Text SHOUT to 85258

## License

This is personal toolkit. Use it, modify it, share it if it helps you. No restrictions.

---

Built with: Desperation, lived experience, and the understanding that crisis tools need to be functional, not pretty.
