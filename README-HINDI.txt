MONEY SOLUTION FINANCE SERVICES - WEBSITE UPDATE PACKAGE

Is package mein:
- agent-register.html : Referral Agent Registration
- agent-login.html : Agent Login, customer lead submit aur apni leads dekhna
- admin/index.html : Admin Login, Customer Inquiries, Agent Management aur sabhi Agent Leads
- firestore.rules : Admin/Agent data access rules
- privacy-policy.html : Hindi-English Privacy Policy, Udyam registration detail sahit
- homepage-update-snippet.txt : index.html mein exact menu, consent, Udyam aur Privacy Policy additions

IMPORTANT:
Aapki live homepage index.html ko public GitHub repository se dekha gaya tha. Usmein original design, poster, contact details aur Firebase module import hai. Is package mein original index.html ko poora replace karne ke bajay sirf homepage-update-snippet.txt ke chhote changes lagane hain, taaki design aur purana data flow na toote.

DEPLOY:
1. Repository root mein agent-register.html replace karein.
2. Repository root mein agent-login.html add/replace karein.
3. admin folder mein index.html replace karein.
4. Repository root mein privacy-policy.html add karein.
5. homepage-update-snippet.txt ke 5 changes existing index.html mein karein.
6. Firebase Console > Firestore Database > Rules mein firestore.rules review karke publish karein.
7. GitHub mein sabhi files commit karein.
8. Test: Agent register -> Admin approval -> Agent login -> test lead -> Agent apni lead dekhe -> Admin sabhi leads dekhe.

FIREBASE CONFIG:
Existing firebase-config-module.js ko replace ya edit na karein. Admin UID rules mein pehle se configured hai: mxqMPdrbN2Nmmqe6YWU3GYJM5GB3

DATA SAFETY:
Firestore ke purane inquiry documents delete nahi honge. New homepage inquiries ke liye consent checkbox mandatory hoga. Admin Agent profile delete karne se Firebase Authentication account delete nahi hota; use Firebase Console Authentication mein separately disable/delete karna hoga.

LEGAL NOTE:
Udyam number ko sirf MSME/Udyam Registration ke roop mein dikhaya gaya hai; GST registration ya bank/NBFC DSA authorization ke roop mein nahi. Privacy Policy ek practical draft hai; apne actual data-sharing aur DSA agreements ke mutabik review karayein.
