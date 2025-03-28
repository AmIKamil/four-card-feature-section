# Frontend Mentor – Four card feature section Solution  

This is a solution to the [Four Card Feature Section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK).  

## 🔗 Live Site  

- [Live Demo](https://amikamil.github.io/four-card-feature-section/)  

## 🛠 Built with  

- **Semantic HTML5**  
- **CSS3 with Custom Properties (CSS Variables)**  
- **CSS Grid & Flexbox**  
- **Responsive Design with Media Queries**  
- **Google Fonts (Poppins)**  

## 📝 Development Steps  

### 🖥️ Desktop-First Approach  
- Designed the layout for larger screens first, using **CSS Grid** for the card arrangement and **Flexbox** for internal alignment.  
- Structured the content with semantic HTML for better accessibility.  

### 🎨 Styling & Theming  
- Used **CSS Variables** (`:root`) for consistent colors and typography.  
- Implemented **box-shadow** and **border-radius** for clean, modern card styling.  
- Imported **Poppins (200, 400, 600 weights)** from Google Fonts for typography.  

### 📱 Responsive Adjustments  
- Applied **media queries** for:  
  - **Tablet (≤ 768px)**: Adjusted grid layout to 2 columns.  
  - **Mobile (≤ 550px)**: Stacked cards in a single column and fine-tuned spacing.  
- Optimized padding and margins for different screen sizes.  

### 🎯 Challenges & Learnings  
- **Grid Layout Complexity**: Ensuring cards aligned properly in all breakpoints required careful grid adjustments.   
- **Border Accents**: Applied dynamic top borders (`var(--Red)`, `var(--Cyan)`, etc.) for visual distinction.  

