मध्य प्रदेश असंगठित निर्माण श्रमिक संघ — वेबसाइट डेमो
फाइलें:
- index.html: सार्वजनिक होम पेज
- admin.html: स्थानीय ब्राउज़र-आधारित एडमिन पैनल डेमो
- README.txt: निर्देश

डेमो लॉगिन पासवर्ड: RamDemo6041
यह केवल UI परीक्षण के लिए है। वास्तविक डेटा न डालें। यह पासवर्ड सुरक्षित प्रमाणीकरण नहीं है।

GitHub Pages पर:
1. इन फाइलों को एक नए समर्पित public repository की root में अपलोड करें।
2. Settings → Pages → Deploy from a branch → main → /(root) → Save.
3. साइट URL होगा https://OWNER.github.io/REPOSITORY/

सीमाएँ:
- एडमिन डेटा localStorage में ही रहता है, ऑनलाइन नहीं।
- यह secure authentication या server-side authorization नहीं है।
- लाइव उपयोग से पहले Supabase Auth + database + RLS/role policies + privacy notice + consent flow जरूरी हैं।
- इस टूल सत्र में GitHub connector नया repository बनाने/Pages settings सक्षम करने का action उपलब्ध नहीं कराता; इसलिए यहाँ से सीधे publish पूरा नहीं हुआ।
- पंजीयन/अधिकार संबंधी सार्वजनिक दावों को अध्यक्ष की स्वीकृति और दस्तावेज से जाँचें।
