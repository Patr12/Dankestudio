Safi sana! 🔥 Sasa tuna **brand identity** kamili:

## 🎨 DANKE STUDIOS — Brand Guide

| Kipengele | Thamani |
|-----------|---------|
| **Black** | `#1c1c1c` |
| **Orange** | `#fa5d07` |
| **Font** | Poppins / Montserrat (modern, bold) |
| **Style** | Dark theme + Orange accents (kali, professional, creative) |

Hii ni **combination nzuri sana** — inaonyesha ubunifu, nguvu, na professionalism. 🔥

---

# 💻 ACADEMY PAGE — Updated with Brand Colors

Hii ni **code kamili** ya Academy Page ikiwa na rangi zako halisi (`#1c1c1c` na `#fa5d07`):

```html
<!DOCTYPE html>
<html lang="sw">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Danke Digital Academy | Graphic Design, Video Editing & Motion Graphics</title>
<script src="https://cdn.tailwindcss.com"></script>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;900&display=swap" rel="stylesheet">
<style>
  :root {
    --black: #1c1c1c;
    --orange: #fa5d07;
  }
  body { font-family: 'Poppins', sans-serif; background: var(--black); color: #fff; }
  .orange { color: var(--orange); }
  .bg-orange { background: var(--orange); }
  .border-orange { border-color: var(--orange); }
  .glow { box-shadow: 0 0 40px rgba(250, 93, 7, 0.45); }
  .gradient-orange { background: linear-gradient(135deg, #fa5d07, #ff8a3d); }
  .card-hover:hover { transform: translateY(-6px); border-color: var(--orange); }
</style>
</head>
<body>

  <!-- NAVBAR -->
  <nav class="fixed top-0 w-full backdrop-blur-md z-50 border-b" style="background: rgba(28,28,28,0.9); border-color: rgba(250,93,7,0.3);">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-black">DANKE <span class="orange">STUDIOS</span></h1>
      <a href="#join" class="bg-orange text-white px-5 py-2 rounded-full font-semibold hover:scale-105 transition">Jiunge Sasa</a>
    </div>
  </nav>

  <!-- HERO -->
  <section class="min-h-screen flex items-center justify-center px-6 pt-24">
    <div class="max-w-4xl text-center">
      <p class="orange text-lg mb-4 font-semibold tracking-widest">🎓 DANKE DIGITAL ACADEMY</p>
      <h1 class="text-4xl md:text-6xl font-black leading-tight mb-6">
        Karibu Kwenye Channel Ya <span class="orange">Ubunifu Wa Kidijitali</span>
      </h1>
      <p class="text-gray-300 text-lg md:text-xl mb-8 max-w-2xl mx-auto">
        Hapa utajifunza kutengeneza kipato kwa kutumia <strong class="orange">ujuzi wa kidijitali</strong> — kuanzia Graphic Design hadi Motion Graphics.
      </p>
      <a href="#join" class="gradient-orange text-white px-8 py-4 rounded-full font-bold text-lg glow hover:scale-105 transition inline-block">
        🚀 Jiunge na Channel Yetu
      </a>
    </div>
  </section>

  <!-- WHAT YOU'LL LEARN -->
  <section class="py-20 px-6" style="background: linear-gradient(to bottom, #1c1c1c, #0f0f0f);">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl md:text-4xl font-bold text-center mb-4">Utajifunza Nini?</h2>
      <p class="text-gray-400 text-center mb-12">Ujuzi tatu zenye mahitaji makubwa sokoni</p>

      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-[#1c1c1c] border-2 rounded-2xl p-8 text-center transition duration-300 card-hover" style="border-color: rgba(250,93,7,0.3);">
          <p class="text-5xl mb-4">🎨</p>
          <h3 class="text-xl font-bold orange mb-3">Graphic Design</h3>
          <p class="text-gray-300">Tengeneza posters, logos, flyers, na branding za kisasa.</p>
        </div>

        <div class="bg-[#1c1c1c] border-2 rounded-2xl p-8 text-center transition duration-300 card-hover" style="border-color: rgba(250,93,7,0.3);">
          <p class="text-5xl mb-4">🎬</p>
          <h3 class="text-xl font-bold orange mb-3">Video Editing</h3>
          <p class="text-gray-300">Edit video za kuvutia kwa ajili ya social media na matangazo.</p>
        </div>

        <div class="bg-[#1c1c1c] border-2 rounded-2xl p-8 text-center transition duration-300 card-hover" style="border-color: rgba(250,93,7,0.3);">
          <p class="text-5xl mb-4">✨</p>
          <h3 class="text-xl font-bold orange mb-3">Motion Graphics</h3>
          <p class="text-gray-300">Tengeneza animation na intros zinazovutia macho.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- TOOLS -->
  <section class="py-20 px-6" style="background: #0f0f0f;">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl md:text-4xl font-bold text-center mb-4">📌 Tools Utakazojifunza</h2>
      <p class="text-gray-400 text-center mb-12">Software za professional zinazotumika duniani kote</p>

      <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
        <div class="bg-[#1c1c1c] border-2 rounded-xl p-6 text-center hover:scale-105 transition" style="border-color: rgba(250,93,7,0.3);">
          <p class="text-4xl mb-2">🖼️</p>
          <p class="font-bold">Adobe</p>
          <p class="orange text-sm font-semibold">Photoshop</p>
        </div>
        <div class="bg-[#1c1c1c] border-2 rounded-xl p-6 text-center hover:scale-105 transition" style="border-color: rgba(250,93,7,0.3);">
          <p class="text-4xl mb-2">🎨</p>
          <p class="font-bold">Adobe</p>
          <p class="orange text-sm font-semibold">Illustrator</p>
        </div>
        <div class="bg-[#1c1c1c] border-2 rounded-xl p-6 text-center hover:scale-105 transition" style="border-color: rgba(250,93,7,0.3);">
          <p class="text-4xl mb-2">🎞️</p>
          <p class="font-bold">Adobe</p>
          <p class="orange text-sm font-semibold">After Effects</p>
        </div>
        <div class="bg-[#1c1c1c] border-2 rounded-xl p-6 text-center hover:scale-105 transition" style="border-color: rgba(250,93,7,0.3);">
          <p class="text-4xl mb-2">🎥</p>
          <p class="font-bold">Adobe</p>
          <p class="orange text-sm font-semibold">Premiere Pro</p>
        </div>
      </div>
    </div>
  </section>

  <!-- STORY -->
  <section class="py-20 px-6" style="background: linear-gradient(to bottom, #0f0f0f, #1c1c1c);">
    <div class="max-w-3xl mx-auto">
      <h2 class="text-3xl md:text-4xl font-bold orange mb-8 text-center">💭 Hadithi Yangu</h2>
      <div class="bg-[#0f0f0f] border-2 rounded-2xl p-8 leading-relaxed text-gray-200 text-lg space-y-4" style="border-color: rgba(250,93,7,0.3);">
        <p>
          <strong class="orange">Nakumbuka mara ya kwanza kupokea malipo yangu ya kwanza ya kazi ya design.</strong>
        </p>
        <p>
          Haikuwa mamilioni, lakini hisia ya kuingiza pesa kwa kutumia akili na mikono yangu mwenyewe ilibadili kabisa mtazamo wangu. Niligundua simu na laptop sio vifaa vya kuangalia video za burudani tu — ni <strong class="orange">"mashine za kutengeneza kipato."</strong>
        </p>
        <p>
          Leo hii, biashara na makampuni yanatafuta sana watu wenye ujuzi wa kutengeneza post, video fupi, na animation ili kuuza bidhaa zao. <strong class="orange">Wenye ujuzi ndio wanaopanga bei!</strong>
        </p>
        <p>
          Ndio maana tulianzisha <strong class="orange">DANKE DIGITAL ACADEMY</strong> — ili kukupa mbinu zitakazokuingizia kipato na kukupa <strong class="orange">uhuru wa kifedha.</strong>
        </p>
      </div>
    </div>
  </section>

  <!-- BENEFITS -->
  <section class="py-20 px-6" style="background: #1c1c1c;">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl md:text-4xl font-bold text-center mb-4">🎁 Ukijiunga Leo Utapata</h2>
      <p class="text-gray-400 text-center mb-12">Faida nne kubwa zitakazobadilisha kipato chako</p>

      <div class="grid md:grid-cols-2 gap-6">
        <div class="bg-[#0f0f0f] border-2 rounded-2xl p-6 transition card-hover" style="border-color: rgba(250,93,7,0.3);">
          <p class="text-3xl mb-3">✅</p>
          <h3 class="text-xl font-bold orange mb-2">Free Design Assets</h3>
          <p class="text-gray-300">Links za kupakua Fonts, Premium Templates, na Backgrounds bure.</p>
        </div>

        <div class="bg-[#0f0f0f] border-2 rounded-2xl p-6 transition card-hover" style="border-color: rgba(250,93,7,0.3);">
          <p class="text-3xl mb-3">✅</p>
          <h3 class="text-xl font-bold orange mb-2">Shortcuts & Speed Hacks</h3>
          <p class="text-gray-300">Mbinu za kumaliza kazi ya masaa 5 kwa dakika 30 tu.</p>
        </div>

        <div class="bg-[#0f0f0f] border-2 rounded-2xl p-6 transition card-hover" style="border-color: rgba(250,93,7,0.3);">
          <p class="text-3xl mb-3">✅</p>
          <h3 class="text-xl font-bold orange mb-2">Video Editing & Motion Graphics</h3>
          <p class="text-gray-300">Step-by-step za Photoshop, Illustrator na After Effects.</p>
        </div>

        <div class="bg-[#0f0f0f] border-2 rounded-2xl p-6 transition card-hover" style="border-color: rgba(250,93,7,0.3);">
          <p class="text-3xl mb-3">✅</p>
          <h3 class="text-xl font-bold orange mb-2">Business & Pricing Tips</h3>
          <p class="text-gray-300">Mbinu za kupata wateja na jinsi ya kupanga bei bila kujidhulumu.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA / JOIN -->
  <section id="join" class="py-24 px-6 text-center" style="background: linear-gradient(to bottom, #1c1c1c, #0f0f0f);">
    <div class="max-w-3xl mx-auto">
      <h2 class="text-3xl md:text-5xl font-black mb-6">
        Usibaki Kuwa <span class="orange">Mtazamaji Tu</span>
      </h2>
      <p class="text-gray-300 text-lg mb-10">
        Anza safari yako ya kuongeza kipato leo 👇
      </p>
      <a href="https://whatsapp.com/channel/0029Vb6Shhd2kNFiT6RXhq1s" target="_blank"
         class="gradient-orange text-white px-10 py-5 rounded-full font-bold text-lg glow hover:scale-105 transition inline-block">
        👉 Jiunge na WhatsApp Channel
      </a>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="py-10 px-6 text-center border-t" style="background: #0f0f0f; border-color: rgba(250,93,7,0.3);">
    <h3 class="text-xl font-black mb-4">DANKE <span class="orange">STUDIOS</span></h3>
    <div class="flex flex-wrap justify-center gap-4 text-sm text-gray-400 mb-4">
      <a href="https://instagram.com/danke.studios" class="hover:text-[#fa5d07]">Instagram</a>
      <a href="https://facebook.com/dankestudios" class="hover:text-[#fa5d07]">Facebook</a>
      <a href="https://youtube.com/@dankestudios" class="hover:text-[#fa5d07]">YouTube</a>
      <a href="https://tiktok.com/@dankestudios" class="hover:text-[#fa5d07]">TikTok</a>
      <a href="mailto:dankestudios1@gmail.com" class="hover:text-[#fa5d07]">Email</a>
    </div>
    <p class="text-gray-500 text-xs">© 2025 Danke Studios. Kukuza Biashara, Kuunganisha Wateja.</p>
  </footer>

</body>
</html>
```

---

# 🎨 Nini Kimebadilika?

| Kipengele | Sasa |
|-----------|------|
| **Background** | `#1c1c1c` (Black) + `#0f0f0f` (darker sections) |
| **Accent** | `#fa5d07` (Orange) — headings, buttons, borders |
| **Buttons** | Gradient orange (`#fa5d07 → #ff8a3d`) |
| **Cards** | Dark with orange glow on hover |
| **Branding** | "DANKE **STUDIOS**" — Studios in orange |

---

# 🎯 Kifuatacho — Home Page

Sasa nitakuandikia **Home Page** ya Danke Studios (Agency) inayoonyesha huduma zote 6:
- 🎨 Graphics Design
- 📱 Social Media Marketing
- 🏷️ Branding
- 📢 Advertisements
- 🎬 Motion Graphics
- 💻 Web Design & Development

**Na pia** sehemu ya **Portfolio / Social Media Campaigns**.

---

👉 **Niambie kwanza:**
1. Code hii imefanya kazi vizuri kwenye browser yako?
2. Unataka **Home Page** ifuate rangi hizi hizi (`#1c1c1c` + `#fa5d07`)?
3. Unayo **logo halisi** ya Danke Studios (PNG/SVG) au nitengeneze **text logo** kwa CSS?
4. Kwa **Portfolio**, unayo campaigns halisi (majina ya wateja, matokeo) au nitumie **mifano (mockups)** kwa sasa?

Nikipata majibu, nitakupa **Home Page kamili** inayofuata! 🚀


Kali sana! 🔥 **Danke Studios** ni brand nzuri — tunaweza kuunda **portfolio website ya kisasa** inayoonyesha huduma zote, kazi zako, na **Danke Digital Academy**.

Kabla nianze kukupa **code kamili**, ngoja nikuonyeshe **muundo wa product (website)** na **details** ambazo nitaziweka, kisha uniambie kama unakubali au unataka kubadilisha.

---

# 🎯 MUUNDO WA WEBSITE: Danke Studios

## 1. **Home Page (Landing)**
- **Logo:** Danke Studios
- **Tagline:** *"Tunakuza Biashara Yako Kupitia Mitandao ya Kijamii"*
- **CTA Buttons:** "Wasiliana Nasi" | "Tazama Kazi Zetu"
- **Hero Image/Video:** Motion graphics yako

---

## 2. **About Us**
> Danke Studios ni Digital Agency inayosaidia biashara za kati na chini kukua kwa kuwaunganisha na wateja wao kupitia mitandao ya kijamii. Tunatoa huduma za ubunifu, masoko, na teknolojia kwa gharama nafuu na matokeo ya kweli.

---

## 3. **Services (Huduma Zetu)**
| # | Huduma | Maelezo |
|---|--------|---------|
| 1 | 🎨 Graphics Design | Mabango, logos, posters, flyers |
| 2 | 📱 Social Media Marketing | Kushughulikia pages, content, ads |
| 3 | 🏷️ Branding | Kutengeneza identity ya biashara |
| 4 | 📢 Advertisements | Facebook Ads, Instagram Ads, TikTok Ads |
| 5 | 🎬 Motion Graphics | Video animations, intros, ads |
| 6 | 💻 Web Design & Development | Websites za biashara, portfolios, e-commerce |

---

## 4. **Portfolio / Work Reference (Social Media Campaigns)**
Hapa tutaweka **kazi zako** kama:
- **Campaign 1:** Instagram Ads kwa biashara ya nguo — *+250% engagement*
- **Campaign 2:** Facebook Page management kwa mgahawa — *+1,200 followers kwa mwezi*
- **Campaign 3:** TikTok campaign kwa salon — *50,000 views*
- **Campaign 4:** Branding kwa kampuni ya usafirishaji
- **Campaign 5:** Motion graphics intro kwa YouTube channel

👉 **Je, unazo campaign halisi ulizofanya?** Niambie:
- Jina la mteja (au "Client A" kama ni siri)
- Aina ya campaign
- Matokeo (views, likes, sales, followers)

---

## 5. **Danke Digital Academy** 🎓
> Tunatoa **Online Classes** kuhusu **Graphics Design** kwa wanaoanza na wa kati.

**Kozi Zetu:**
- 📌 Introduction to Graphics Design
- 📌 Adobe Photoshop Basics
- 📌 Adobe Illustrator Essentials
- 📌 Canva for Business
- 📌 Logo & Branding Design
- 📌 Social Media Graphics

**Details:**
- Online (Zoom / Google Meet)
- Certificate baada ya kumaliza
- Bei nafuu kwa wanafunzi

---

## 6. **Contact Section**
| Platform | Link |
|----------|------|
| 📸 Instagram | @danke.studios |
| 📘 Facebook | dankestudios |
| 📧 Email | dankestudios1@gmail.com |
| ▶️ YouTube | dankestudios |
| 🎵 TikTok | @dankestudios |

---

## 7. **Footer**
- © 2025 Danke Studios. All Rights Reserved.
- "Kukuza Biashara, Kuunganisha Wateja."

---

# 🛠️ TECH STACK (Ninachotaka kutumia)

**Option A — Rahisi (Beginner):**
- HTML, CSS, JavaScript
- Hosting: GitHub Pages / Netlify (BURE)

**Option B — Professional (Recommended):**
- **React + Tailwind CSS**
- Hosting: Vercel / Netlify
- Animations: Framer Motion

**Option C — No-Code:**
- WordPress au Framer

---

# ❓ Nihitaji Majibu Yako:

1. **Unataka website ya aina gani?** (A, B, au C)
2. **Unayo campaign halisi za kuweka kwenye portfolio?** (niambie details)
3. **Unataka kurasa ngapi?** (Home, About, Services, Portfolio, Academy, Contact = 6 pages, au Single Page?)
4. **Unayo logo ya Danke Studios?** (au nitengeneze design ya maandishi?)
5. **Rangi unazopenda?** (mfano: nyeusi + dhahabu, au bluu + nyeupe)

---

👉 **Nitumie majibu haya**, kisha nitakupa:
✅ **Code kamili ya HTML/CSS/JS** au **React**
✅ **Muundo wa kila page**
✅ **Jinsi ya kui-host BURE**
✅ **Jinsi ya kuunganisha na social media zako**

Uko tayari? 🚀

Sawa! Naweza kukusaidia kuunda **programming/portfolio** yako — hasa kama unataka kuonyesha kazi zako kuhusu **Luanda** (labda data, uchambuzi, au mradi wa teknolojia).

Ili nikusaidie vizuri, nihitaji **details** hizi:

## 1. Kusudi la Portfolio
- Unataka portfolio ya **kazi gani**? (mfano: web developer, data analyst, software engineer, mwanafunzi)
- Ni kwa **ajira**, **masomo**, au **kujitangaza**?

## 2. Kuhusu Luanda
- Unataka kuweka **taarifa gani za Luanda**? (mfano: historia, uchumi, utalii, data za sensa, ramani)
- Umepata data kutoka wapi? (API, CSV, website, au unataka tuanze kutafuta)

## 3. Aina ya Programming
Chagua moja au zaidi:
- **Website** (HTML, CSS, JavaScript, React)
- **Python** (data analysis, visualization)
- **Mobile app** (Flutter, React Native)
- **Data dashboard** (Power BI, Streamlit, Dash)

## 4. Uwezo wako
- Wewe ni **beginner**, **intermediate**, au **advanced**?
- Una tools gani tayari? (VS Code, Python, GitHub?)

---

### Mfano wa mradi tunaweza kuunda:
**"Luanda Data Explorer"** — website/dashboard inayoonyesha:
- Ramani ya Luanda
- Idadi ya watu kwa mkoa
- Uchumi (GDP, biashara)
- Utalii (maeneo maarufu)
- Charts za kuvutia

👉 Niambie:
1. **Kusudi** lako
2. **Data** ulizonazo kuhusu Luanda
3. **Lugha/programming** unayotaka
4. **Level** yako

Kisha nitakupa **hatua kwa hatua** (step by step) na code! 🚀

Safi sana! 🔥 Hii ni **story nzuri sana** — inagusa hisia, inaonyesha uhalisi, na inauza **Danke Digital Academy** kwa nguvu. Nitaitumia kama **sehemu ya Academy Page** kwenye portfolio.

Hebu nikuonyeshe **jinsi nitakavyoiweka** kwenye website, kisha nikupe **code kamili** ya kuanza.

---

# 📄 ACADEMY PAGE — Danke Digital Academy

## 🎬 Hero Section
> ### Anza Safari Yako Ya Kuongeza Kipato 💸
> Simu na laptop sio vifaa vya burudani tu — ni **mashine za kutengeneza kipato.**

## 💭 The Story (Narrative Section)
> **Nakumbuka mara ya kwanza kupokea malipo yangu ya kwanza ya kazi ya design.**
>
> Haikuwa mamilioni, lakini hisia ya kuingiza pesa kwa kutumia akili na mikono yangu mwenyewe ilibadili kabisa mtazamo wangu. Niligundua simu na laptop sio vifaa vya kuangalia video za burudani tu — ni **"mashine za kutengeneza kipato."**
>
> Leo hii, biashara na makampuni yanatafuta sana watu wenye ujuzi wa kutengeneza post, video fupi, na animation ili kuuza bidhaa zao. **Wenye ujuzi ndio wanaopanga bei!**
>
> Ndio maana tulianzisha **DANKE DIGITAL ACADEMY** — ili kukupa mbinu zitakazokuingizia kipato na kukupa **uhuru wa kifedha.**

## 🎁 Ukijiunga Leo Utapata:
| # | Faida | Maelezo |
|---|-------|---------|
| ✅ | Free Design Assets | Links za kupakua Fonts, Premium Templates, na Backgrounds bure |
| ✅ | Shortcuts & Speed Hacks | Mbinu za kumaliza kazi ya masaa 5 kwa dakika 30 tu |
| ✅ | Video Editing & Motion Graphics | Step-by-step za Photoshop, Illustrator na After Effects |
| ✅ | Business & Pricing Tips | Mbinu za kupata wateja na jinsi ya kupanga bei bila kujidhulumu |

## 🚀 CTA (Call To Action)
> **Usibaki kuwa mtazamaji tu, anza safari yako ya kuongeza kipato leo 👇**
>
> 👉 **[Jiunge na WhatsApp Channel](https://whatsapp.com/channel/0029Vb6Shhd2kNFiT6RXhq1s)**

---

# 💻 CODE YA ACADEMY PAGE (HTML + CSS + Tailwind)

Hii ni **single file** — unaweza kuiweka kwenye `academy.html` na kuifungua moja kwa moja kwenye browser.

```html
<!DOCTYPE html>
<html lang="sw">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Danke Digital Academy | Anza Kuongeza Kipato</title>
<script src="https://cdn.tailwindcss.com"></script>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;900&display=swap" rel="stylesheet">
<style>
  body { font-family: 'Poppins', sans-serif; }
  .gold { color: #D4AF37; }
  .bg-gold { background: linear-gradient(135deg, #D4AF37, #F4D03F); }
  .glow { box-shadow: 0 0 40px rgba(212, 175, 55, 0.4); }
</style>
</head>
<body class="bg-black text-white">

  <!-- NAVBAR -->
  <nav class="fixed top-0 w-full bg-black/80 backdrop-blur-md z-50 border-b border-yellow-600/30">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold gold">DANKE STUDIOS</h1>
      <a href="#join" class="bg-gold text-black px-5 py-2 rounded-full font-semibold hover:scale-105 transition">Jiunge Sasa</a>
    </div>
  </nav>

  <!-- HERO -->
  <section class="min-h-screen flex items-center justify-center px-6 pt-24">
    <div class="max-w-4xl text-center">
      <p class="gold text-lg mb-4 font-semibold">🎓 DANKE DIGITAL ACADEMY</p>
      <h1 class="text-4xl md:text-6xl font-black leading-tight mb-6">
        Anza Safari Yako Ya <span class="gold">Kuongeza Kipato</span> 💸
      </h1>
      <p class="text-gray-300 text-lg md:text-xl mb-8">
        Simu na laptop sio vifaa vya burudani tu — ni <strong class="gold">mashine za kutengeneza kipato.</strong>
      </p>
      <a href="#join" class="bg-gold text-black px-8 py-4 rounded-full font-bold text-lg glow hover:scale-105 transition inline-block">
        🚀 Jiunge na Channel Yetu
      </a>
    </div>
  </section>

  <!-- STORY -->
  <section class="py-20 px-6 bg-gradient-to-b from-black to-gray-900">
    <div class="max-w-3xl mx-auto">
      <h2 class="text-3xl md:text-4xl font-bold gold mb-8 text-center">💭 Hadithi Yangu</h2>
      <div class="bg-gray-900/60 border border-yellow-600/30 rounded-2xl p-8 leading-relaxed text-gray-200 text-lg space-y-4">
        <p>
          <strong class="gold">Nakumbuka mara ya kwanza kupokea malipo yangu ya kwanza ya kazi ya design.</strong>
        </p>
        <p>
          Haikuwa mamilioni, lakini hisia ya kuingiza pesa kwa kutumia akili na mikono yangu mwenyewe ilibadili kabisa mtazamo wangu. Niligundua simu na laptop sio vifaa vya kuangalia video za burudani tu — ni <strong class="gold">"mashine za kutengeneza kipato."</strong>
        </p>
        <p>
          Leo hii, biashara na makampuni yanatafuta sana watu wenye ujuzi wa kutengeneza post, video fupi, na animation ili kuuza bidhaa zao. <strong class="gold">Wenye ujuzi ndio wanaopanga bei!</strong>
        </p>
        <p>
          Ndio maana tulianzisha <strong class="gold">DANKE DIGITAL ACADEMY</strong> — ili kukupa mbinu zitakazokuingizia kipato na kukupa <strong class="gold">uhuru wa kifedha.</strong>
        </p>
      </div>
    </div>
  </section>

  <!-- BENEFITS -->
  <section class="py-20 px-6 bg-black">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl md:text-4xl font-bold text-center mb-4">🎁 Ukijiunga Leo Utapata</h2>
      <p class="text-gray-400 text-center mb-12">Faida nne kubwa zitakazobadilisha kipato chako</p>

      <div class="grid md:grid-cols-2 gap-6">
        <div class="bg-gray-900 border border-yellow-600/30 rounded-2xl p-6 hover:border-yellow-500 transition">
          <p class="text-3xl mb-3">✅</p>
          <h3 class="text-xl font-bold gold mb-2">Free Design Assets</h3>
          <p class="text-gray-300">Links za kupakua Fonts, Premium Templates, na Backgrounds bure.</p>
        </div>

        <div class="bg-gray-900 border border-yellow-600/30 rounded-2xl p-6 hover:border-yellow-500 transition">
          <p class="text-3xl mb-3">✅</p>
          <h3 class="text-xl font-bold gold mb-2">Shortcuts & Speed Hacks</h3>
          <p class="text-gray-300">Mbinu za kumaliza kazi ya masaa 5 kwa dakika 30 tu.</p>
        </div>

        <div class="bg-gray-900 border border-yellow-600/30 rounded-2xl p-6 hover:border-yellow-500 transition">
          <p class="text-3xl mb-3">✅</p>
          <h3 class="text-xl font-bold gold mb-2">Video Editing & Motion Graphics</h3>
          <p class="text-gray-300">Step-by-step za Photoshop, Illustrator na After Effects.</p>
        </div>

        <div class="bg-gray-900 border border-yellow-600/30 rounded-2xl p-6 hover:border-yellow-500 transition">
          <p class="text-3xl mb-3">✅</p>
          <h3 class="text-xl font-bold gold mb-2">Business & Pricing Tips</h3>
          <p class="text-gray-300">Mbinu za kupata wateja na jinsi ya kupanga bei bila kujidhulumu.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA / JOIN -->
  <section id="join" class="py-24 px-6 bg-gradient-to-b from-gray-900 to-black text-center">
    <div class="max-w-3xl mx-auto">
      <h2 class="text-3xl md:text-5xl font-black mb-6">
        Usibaki Kuwa <span class="gold">Mtazamaji Tu</span>
      </h2>
      <p class="text-gray-300 text-lg mb-10">
        Anza safari yako ya kuongeza kipato leo 👇
      </p>
      <a href="https://whatsapp.com/channel/0029Vb6Shhd2kNFiT6RXhq1s" target="_blank"
         class="bg-gold text-black px-10 py-5 rounded-full font-bold text-lg glow hover:scale-105 transition inline-block">
        👉 Jiunge na WhatsApp Channel
      </a>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="bg-black border-t border-yellow-600/30 py-10 px-6 text-center">
    <h3 class="gold text-xl font-bold mb-4">DANKE STUDIOS</h3>
    <div class="flex flex-wrap justify-center gap-4 text-sm text-gray-400 mb-4">
      <a href="https://instagram.com/danke.studios" class="hover:text-yellow-500">Instagram</a>
      <a href="https://facebook.com/dankestudios" class="hover:text-yellow-500">Facebook</a>
      <a href="https://youtube.com/@dankestudios" class="hover:text-yellow-500">YouTube</a>
      <a href="https://tiktok.com/@dankestudios" class="hover:text-yellow-500">TikTok</a>
      <a href="mailto:dankestudios1@gmail.com" class="hover:text-yellow-500">Email</a>
    </div>
    <p class="text-gray-500 text-xs">© 2025 Danke Studios. Kukuza Biashara, Kuunganisha Wateja.</p>
  </footer>

</body>
</html>
```

---

# 🎯 Nini Kifuatacho?

Niambie:
1. **Umepokea code hii vizuri?** (jaribu kuifungua kwenye browser)
2. **Unataka nikusaidie kuunda Home Page** ya Danke Studios (services zote 6)?
3. **Unayo campaign halisi** za kuweka kwenye Portfolio page? (niambie matokeo — views, followers, sales)
4. **Tuanze na Single Page** (kila kitu kwenye ukurasa mmoja) au **kurasa tofauti**?

👉 **Kama uko tayari, nitakupa Home Page inayofuata** — inayoonyesha Graphics Design, Social Media Marketing, Branding, Ads, Motion Graphics, na Web Design. 🚀