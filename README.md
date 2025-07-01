# 🏦 Credit Union Bank - Frozen Account Dashboard  

**A responsive banking interface mockup demonstrating a high-value frozen account scenario with security verification workflows.**

## ✨ Key Features  
- 🧊 **Frozen Account State**  
  - Visual indicators for frozen status ($1.5B balance)  
  - Ice-blue UI accents and lock icons  

- ⚠️ **Blocked Transaction**  
  - Highlighted $5.5M transfer attempt to "Carolyn M Wood"  
  - Pending security verification alert  

- 🛡️ **Security Protocols**  
  - 2FA status display  
  - Authentication alerts for suspicious activity  

- 📱 **Responsive Design**  
  - Adapts to mobile/desktop (media queries at 768px)  

## 🧰 Technical Implementation  
```plaintext
tech-stack/
├── HTML5          # Semantic structure
├── CSS3           # Flexbox/Grid layout
├── Font Awesome   # Icons (via CDN)
└── Google Fonts   # Roboto typography
```

## 📂 Project Structure  
```plaintext
.
├── index.html     # Dashboard skeleton
├── style.css      # Banking UI styles
└── README.md      # Project documentation
```

## 🚀 Deployment Options  
1. **GitHub Pages** (Free):  
   ```bash
   # Push to main branch → Enable in Settings → Pages
   ```

2. **Local Preview**:  
   ```bash
   open index.html  # Works on all OSes
   ```

## 🛠️ Customization  
To modify:  
1. Edit CSS variables in `:root`  
   ```css
   :root {
     --primary-blue: #0056b3;  /* Brand color */
     --frozen-accent: #a8d8ea; /* Frozen state */
   }
   ```
2. Update transaction details in `index.html`  

## 📜 License  
MIT Licensed - See [LICENSE](LICENSE) for full terms.  
