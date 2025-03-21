# SafeScan - Food Allergy Scanner  

SafeScan is a mobile app that scans ingredient labels to detect allergens using AI-powered OCR. Users set up allergy profiles, and the app alerts them if a scanned product contains harmful ingredients.  

## Features  
- 📷 **OCR scanning**: Extracts ingredient text from packaging.  
- 🤖 **AI-powered allergen detection**.  
- 👥 **Multiple user profiles** (for different family members).  
- ⚠️ **Real-time warnings** when allergens are detected.  

## Tech Stack  
- **Frontend:** Flutter (Dart)  
- **AI & Backend:** Python (FastAPI) + Google ML Kit (OCR)  
- **Database:** Firebase (user profiles, allergy lists)  

## Project Plan  
### **Phase 1: MVP**  
✅ Set up Flutter app & camera scanner  
✅ Implement **OCR text extraction**  
✅ Store user profiles & allergens in Firebase  

### **Phase 2: AI Integration**  
- Train AI model to recognise allergens  
- Highlight dangerous ingredients in scanned text  

### **Phase 3: Testing & Deployment**  
- Optimize scanning speed & accuracy  
- Publish on Google Play Store  
