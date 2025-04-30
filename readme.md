 * [About](#about)
  * [Work Experience](#work-experience)
    * [Brightcove (acquired) - brightcove.com (Nov 2022 - March 2025)](#brightcove-acquired---brightcovecom-nov-2022---march-2025)
      * [Staff Software Engineer (Nov 2022 - March 2025, Los Angeles/New York)](#staff-software-engineer-nov-2022---march-2025-los-angelesnew-york)
        * [Highlights](#highlights)
        * [Environment](#environment)
    * [EPAM - epam.com (Sep 2017 - Nov 2022)](#epam---epamcom-sep-2017---nov-2022)
      * [Senior Software Engineer (Nov 2021 - Nov 2022, Los Angeles)](#senior-software-engineer-nov-2021---nov-2022-los-angeles)
        * [Highlights](#highlights-1)
        * [Environment](#environment-1)
      * [Senior Software Engineer (Aug 2020 - Nov 2021, Minsk)](#senior-software-engineer-aug-2020---nov-2021-minsk)
        * [Highlights](#highlights-2)
        * [Environment](#environment-2)
      * [Software Engineer (Jun 2018 - Aug 2020, Minsk)](#software-engineer-jun-2018---aug-2020-minsk)
        * [Highlights](#highlights-3)
        * [Environment](#environment-3)
      * [Software Engineer (March 2019 - May 2019, Minsk)](#software-engineer-march-2019---may-2019-minsk)
        * [Highlights](#highlights-4)
        * [Environment](#environment-4)
      * [Junior Software Engineer (Sep 2017 - Jun 2018, Minsk)](#junior-software-engineer-sep-2017---jun-2018-minsk)
        * [Highlights](#highlights-5)
        * [Environment](#environment-5)
  * [Community Involvement](#community-involvement)
    * [Rolling Scopes](#rolling-scopes)
      * [Mentor (Jan 2019 - Sep 2019)](#mentor-jan-2019---sep-2019)
        * [Highlights](#highlights-6)
  * [Education](#education)
    * [Diploma, Minsk State Power Engineering College (Sep 2009 — Jul 2013)](#diploma-minsk-state-power-engineering-college-sep-2009--jul-2013)
    * [No Degree, Belarusian State Economic University (Sep 2013 — Jun 2016)](#no-degree-belarusian-state-economic-university-sep-2013--jun-2016)

---

### About

```dotenv
EMAIL='dzianis.dashkevich.us@gmail.com'
LOCATION='New York'
```

Experienced Software Engineer with `8+` years of building high-performance, scalable web media players used by _millions_ worldwide.\
A recognized contributor to the video.js ecosystem with deep expertise in streaming protocols (HLS, DASH), DRM, and web player frameworks like video.js, hls.js, dash.js and Shaka Player. \
Led the development of production-grade playback SDKs for Smart TVs, mobile apps, and the web. \
While web media tech is my core specialty, I bring a generalist mindset—comfortable owning features end-to-end, building responsive frontend interfaces and backend APIs and optimizing CI/CD pipelines. \
Proven ability to adapt quickly, deliver robust solutions across domains, and mentor teammates while fostering engineering excellence.

---

### Work Experience

#### Brightcove (acquired) - brightcove.com (Nov 2022 - March 2025)

##### Staff Software Engineer (Nov 2022 - March 2025, Los Angeles/New York)

###### Highlights
- Planned and led development of Web/Smart TV SDK, written in TypeScript, enabling customers to implement media playback across traditional browsers and Smart TVs (Tizen and WebOS).
- Improved on Brightcove Player in key time-to-first-frame metric by an average of 25%
- Acted as the go-to engineer for live debugging sessions and ad-hoc meetings with enterprise clients.
- Delivered fixes for critical playback issues in a web media player powering over 4 billion streams per month that improved stream stability and preserved revenue for major B2B partners.
- Managed Player releases with a canary deployment strategy: A/B testing using in-house analytics piped into Graphite/Grafana database to detect anomalies only present in production traffic
- Proposed and authored a formal RFC for the new playback engine in video.js.
- Actively contributed to the video.js open-source ecosystem improving core playback features used on over 750,000 websites, starred by 38,000 developers on GitHub.
- Overhauled CI/CD (TeamCity) pipelines to reduce duplication and increase reliability
- Built an automated PR aggregation tool across 100+ internal/open-source repos, reducing code review delays by half.
- Founded and led an internal Web Player Discussion Club, fostering a culture of continuous learning and cross-team knowledge sharing around video tech, playback performance, and web media standards.

###### Environment
- Team Size: Dev: 8+, QA: 3
- Key languages, frameworks and tools I used extensively during my work on this project:
    - javascript/typescript, nodejs
    - express.js, video.js, dash.js, hls.js, shaka-player
    - nx, typedoc, grunt, rollup, vite, babel, aslant, jest, vitest, webdriver.io
    - ffmpeg, ffprobe, gpac mp4box, bento4, TSDuck
    - gitHub-actions, teamcity, jenkins, aws, grafana, docker, browserstack
    - plantuml, lucid

#### EPAM - epam.com (Sep 2017 - Nov 2022)

##### Senior Software Engineer (Nov 2021 - Nov 2022, Los Angeles)

###### Highlights
- Consulted on custom Chromium-based SmartTV media stack—troubleshot critical video rendering issues.
- Implemented in-house QoE metrics reporting within existing AWS and Grafana infrastructure.
- Improved player in key time-to-first-frame metric by an average of 15%
- Delivered ABR optimization and playback stability fixes, reducing buffering by 30% on low performance TVs

###### Environment
- Customer: Big US SmartTV manufacturer
- Team Size: Dev 15+, QA: 7+
- Key languages, frameworks and tools I used extensively during my work on this project:
  - javascript/typescript
  - vue2, vuex, vue-router, svelte, svelte-kit, video.js, dash.js, hls.js, shaka-player
  - webpack, vite, postCSS, babel, eslint, jest, semantic-release, conventional-changelog, lighthouse, cypress, playwrite
  - ffmpeg, ffprobe, gpac mp4box, bento4, TSDuck
  - github-actions, was,  grafana, docker, terraform
  - plantuml, lucid

##### Senior Software Engineer (Aug 2020 - Nov 2021, Minsk)

###### Highlights
- Implemented reusable Flutter widgets UI Kit for our cross-platform media app.
- Built a multi-platform Google Cast Sender library (Web, iOS, Android), integrated across the Flutter app.
- Developed Dart-JS interop module for web video player.
- Significantly improved CI/CD performance leading to faster release cycles
- Led cross-platform feature team (1 Android Dev, 1 iOS Dev, 1 Web Dev, 1QA)

###### Environment
- Customer: Europe's leading streaming, broadband, and communication company.
- Team Size: Dev 100+, QA: 20+
- Key languages, frameworks and tools I used extensively during my work on this project:
    - dart, Javascript/typescript, nodejs, swift, kotlin, groovy
    - flutter, flutter-bloc, react, redux, ramdajs, rxjs, avplayer, exoplayer, shaka-player
    - pub, make, gradle, webpack, babel, eslint
    - jenkins, sonar, swagger, nginx, docker

##### Software Engineer (Jun 2018 - Aug 2020, Minsk)

###### Highlights
- Added EME persistent license flow and license renewal mechanism. This significantly reduced requests to license servers during high load (eg: Formula 1)
- Spearheaded the modularization of Web Media Player, introducing plugin-based architecture.
- Integrated peer-to-peer solutions based on WebRTC (Teltoo and Streamroot) to reduce CDN overhead.
- Integrated complex Web Player Watermarking solution with module obfuscation and DOM changes detection.
- Developed Chromecast Receiver App & Web Sender—supporting features like pin codes, bookmarks, rent, restrictions, device registration, visual scrubbing and binge viewing

###### Environment
- Customer: Europe's leading streaming, broadband, and communication company.
- Team Size: Dev 10+, QA: 4+
- Key languages, frameworks and tools I used extensively during my work on this project:
  - javascript, nodejs, python
  - react, redux, rxjs, ramdajs, lodash, react-motion, conviva, omniture, shaka-player, silverlight
  - webpack, babel, storybook, eslint, jest, lerna

##### Software Engineer (March 2019 - May 2019, Minsk)

###### Highlights
- Designed and built an internal web app for training voice models using WebAudio API, Web Workers for Opus encoding and Nuance WebSocket API.
- Managed project solo, delivering on time with full roadmap and stakeholder alignment.

###### Environment
- Customer: Europe's leading streaming, broadband, and communication company.
- Team Size: Dev 1
- Key languages, frameworks and tools I used extensively during my work on this project:
  - javascript, nodejs
  - strapi, materialUI, React, redux, rxjs, ramdajs, lib-opus, nuance
  - webpack, babel, eslint, jest

##### Junior Software Engineer (Sep 2017 - Jun 2018, Minsk)

###### Highlights
- Developed a reusable package of Presentational React components for our
  media applications (UI Kit).
- Significantly improved performance (~50% faster) of channels switching in the
  application's Web Player UI.

###### Environment
- Customer: Europe's leading streaming, broadband, and communication company.
- Team Size: Dev 1
- Key languages, frameworks and tools I used extensively during my work on this project:
    - javascript, nodejs
    - react, redux, rxjs, ramdajs, lodash, react-motion, jQuery, jQuery-mobile
    - webpack, babel, storybook, eslint, jest, lerna

---

### Community Involvement

#### Rolling Scopes

##### Mentor (Jan 2019 - Sep 2019)

###### Highlights
- Mentored people who wants to become software engineers and conducted technical discussions.

---

### Education

#### Diploma, Minsk State Power Engineering College (Sep 2009 — Jul 2013)
- Course of Study: Electric Power Plants

#### No Degree, Belarusian State Economic University (Sep 2013 — Jun 2016)
- Course of Study: Commercial Activity