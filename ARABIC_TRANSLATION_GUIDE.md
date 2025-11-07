# Arabic Translation Guide

## How to Add Full Arabic Translations

The translation system is now set up. Here's how to add Arabic translations for all your content:

### Method 1: Add `data-translatable` attribute (Recommended)

Add the attribute `data-translatable="key"` to any element you want to translate, then add the translation to the JavaScript object.

**Example:**

```html
<!-- In HTML -->
<p data-translatable="aboutDescription">
    Senior Construction Manager with 14+ years of experience...
</p>

<!-- In JavaScript translations object -->
aboutDescription: "مدير إنشاءات أول مع أكثر من 14 عامًا من الخبرة..."
```

### Content That Needs Translation:

#### 1. About Section
- Personal description
- Info box details (Name, Email, Phone, Location, Experience, Languages)

#### 2. Education Section
Each education item needs:
- Degree name
- Institution name
- Description
- Date range

#### 3. Experience Section  
Each job needs:
- Job title
- Company name
- Date range
- Bullet points (achievements)

#### 4. Skills Section
- Skill names
- Percentage labels

#### 5. Services Section
Each service card needs:
- Service title
- Service description

#### 6. Projects Section
Each project needs:
- Project name
- Location/Value badges
- Project description

#### 7. Testimonials Section
- Testimonial text
- Client name
- Client title
- Company name

#### 8. Contact Section
- Form labels (Name, Email, Subject, Message)
- Contact info boxes

---

## Quick Translation Template

### Experience Translations Example:

```javascript
experience: {
    job1: {
        title: "Senior Construction Manager",
        titleAr: "مدير إنشاءات أول",
        company: "Sharqawi Co. · Aramco Dammam Stadium",
        companyAr: "شركة الشرقاوي · ملعب أرامكو الدمام",
        date: "Apr 2025 — Present",
        dateAr: "أبريل 2025 — حتى الآن",
        achievements: [
            "Leading comprehensive construction management...",
            "Managing project budget of SAR 280M+..."
        ],
        achievementsAr: [
            "قيادة إدارة البناء الشاملة...",
            "إدارة ميزانية المشروع بقيمة 280 مليون ريال سعودي+"
        ]
    }
}
```

---

## Do You Want Me To:

**Option A**: Create an automated system using Google Translate API to translate all content?  
**Option B**: Provide you with a complete list of all English content that needs manual translation?  
**Option C**: Implement a simpler system that translates only the most important visible text?

**Recommended**: Option C for now (translate key sections), then gradually add more translations as needed.

---

## What's Currently Translated:

✅ Navigation menu  
✅ Hero section  
✅ Section titles and categories  
✅ Buttons (Hire Me, Download CV, Contact Me, Send Message)  
✅ Footer (headers, links, copyright)  

## What Still Needs Translation:

❌ About section detailed text  
❌ Education descriptions  
❌ Experience job details  
❌ Skills list  
❌ Service descriptions  
❌ Project descriptions  
❌ Testimonial content  
❌ Contact form placeholders  

---

## Next Steps:

1. Test the current translation (only titles/buttons work now)
2. Decide which content is most important to translate
3. I'll help you add those translations systematically

Would you like me to proceed with Option C (translate only key visible content first)?
