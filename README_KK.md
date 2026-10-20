# MULTI POST — GitHub Pages сайты

Ішінде дайын: `index.html` (басты бет), `terms.html` (шарттар), `privacy.html` (құпиялық саясаты), `style.css`, `logo.png`, `.nojekyll`.

## 1. МІНДЕТТІ БАПТАУ

Үш HTML файлынан `YOUR_SUPPORT_EMAIL` мәтінін тауып, осы жобаға бөлек жасалған, нақты жұмыс істейтін байланыс email-іне ауыстырыңыз. Бұл email ресми сұрауларға жауап бере алуы керек. Жеке құпия мәліметтерді және API токендерін GitHub репозиторийіне салмаңыз.

`privacy.html` мазмұнын қарап, нақты Flask сервері, хостинг және дерек сақтау тәртібіне сәйкестігін тексеріңіз. Мәтін — бейімдеуді қажет ететін үлгі, заңгерлік қорытынды емес.

## 2. GitHub Pages қосу

1. https://github.com/new ашыңыз.
2. Repository name: `multi-post-site`, Visibility: **Public**, Create repository.
3. Репозиторийде `Add file` → `Upload files` таңдаңыз.
4. ZIP-ті ЖАЙМЕН ашып, сайт ішіндегі **барлық файлдарды репозиторийдің түбіріне** салыңыз (ZIP-ті тікелей салмаңыз).
5. `Commit changes` басыңыз.
6. `Settings` → `Pages` → `Build and deployment` → `Source: Deploy from a branch` → `Branch: main`, `/(root)` → `Save`.
7. Бірнеше минуттан кейін GitHub Pages парағынан **Visit site** арқылы тексеріңіз. 10 минутқа дейін уақыт кетуі мүмкін.

## 3. TikTok Developer-ге салынатын нақты мекенжайлар

`GITHUB_USERNAME` — өз GitHub логиніңіз, оны тиісті нақты логинге ауыстырыңыз:

- Official Web URL: `https://GITHUB_USERNAME.github.io/multi-post-site/`
- Terms of Service URL: `https://GITHUB_USERNAME.github.io/multi-post-site/terms.html`
- Privacy Policy URL: `https://GITHUB_USERNAME.github.io/multi-post-site/privacy.html`

Сілтемелерді TikTok-қа салмас бұрын браузерден жеке ашып, жұмыс істейтінін тексеріңіз.

## 4. TikTok URL ownership verification

2024-09-09-дан кейін құрылған TikTok қосымшаларында Terms of Service, Privacy Policy, Web URL иелігін растау талап етіледі. TikTok → **URL properties** → **Verify properties** → мүмкін болса URL prefix әдісін таңдаңыз. TikTok берген verification signature файлын жүктеп, репозиторийдің тиісті жолына сол қалпында орналастырыңыз. Беттің URL-іне сай нақты нұсқауларды орындаңыз. Егер TikTok `github.io` үшін растауға рұқсат етпесе немесе өз доменіңіз қажет болса, жеке домен алу қажет болуы мүмкін.

## 5. Шектеу

Бұл — тек сайттың көпшілікке ашық ақпараттық беттері. GitHub Pages Python/Flask бағдарламасын жүргізбейді. TikTok өндірістік App Review үшін жұмыс істейтін веб-қосымшаны, нақты жариялау ағынын көрсететін видео және URL-ді растауды талап етуі мүмкін. Статикалық үш бет TikTok-тың API мақұлдауына кепіл болмайды.
