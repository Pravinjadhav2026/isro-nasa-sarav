# इस्रो नासा सहल परीक्षा — GitHub Pages पॅकेज

या पॅकेजमध्ये GitHub Pages वर प्रकाशित करण्यासाठी आवश्यक फाइल्स आहेत.

## पॅकेजमधील फाइल्स

- `index.html` — मुख्य पान; येथून दोन्ही सराव चाचण्या उघडता येतात.
- `sarav-chachani-1.html` — सराव चाचणी १.
- `sarav-chachani-2.html` — सराव चाचणी २.
- `.nojekyll` — GitHub Pages साठी स्थिर फाइल.

दोन्ही चाचण्यांमध्ये प्रत्येकी ७५ प्रश्न आहेत: विज्ञान व अंतराळ २५, गणित २५, वैज्ञानिक बुद्धिमत्ता व अभियोग्यता २५. उत्तर निवडल्यानंतर लगेच पडताळणी आणि स्पष्टीकरण दिसते. शेवटी गुणपत्रक, प्रश्ननिहाय पुनरावलोकन आणि प्रमाणपत्र प्रिंट/PDF करता येते.

## GitHub वर प्रकाशित करण्याची पद्धत

1. GitHub मध्ये साइन इन करा.
2. **New repository** निवडा.
3. Repository name म्हणून `isro-nasa-sarav` वापरा.
4. Repository **Public** ठेवा आणि repository तयार करा.
5. या ZIP मधील फाइल्स Extract करा. सर्व चार फाइल्स (`index.html`, दोन्ही चाचणी HTML फाइल्स आणि `.nojekyll`) repository च्या मुख्य/root भागात Upload करा. `README_MR.md` देखील Upload करा.
6. **Commit changes** दाबा.
7. Repository मध्ये **Settings → Pages** उघडा.
8. **Build and deployment** विभागात **Deploy from a branch** निवडा.
9. Branch `main` आणि folder `/(root)` निवडून **Save** करा.
10. काही मिनिटांनी Pages विभागात दिसणारी वेबसाइट लिंक उघडा.

## वेबसाइट लिंक

सामान्यतः URL असेल:

`https://YOUR-GITHUB-USERNAME.github.io/isro-nasa-sarav/`

`YOUR-GITHUB-USERNAME` ऐवजी तुमचे खरे GitHub username वापरा. URL प्रत्यक्ष प्रकाशित झाल्यानंतर Settings → Pages मधील लिंक हीच अधिकृत समजा.

## महत्त्वाच्या सूचना

- ही वेबसाइट static HTML/CSS/JavaScript वर आधारित आहे; Google Apps Script किंवा server लागत नाही.
- विद्यार्थी गुण वेबसाइटवर कायमस्वरूपी साठवले जात नाहीत आणि शिक्षकांकडे आपोआप पाठवले जात नाहीत.
- प्रकाशित करण्यापूर्वी प्रत्यक्ष मोबाईलवर दोन्ही चाचण्या उघडून तपासा.
