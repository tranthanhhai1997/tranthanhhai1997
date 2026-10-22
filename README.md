<div align="center">

<!-- ░░ HERO — self-hosted animated vector (audio spectrum + flowing waveform) ░░ -->
<a href="https://github.com/tranthanhhai1997">
  <img src="https://raw.githubusercontent.com/tranthanhhai1997/tranthanhhai1997/main/assets/hero-banner.svg" width="100%" alt="Trần Thanh Hải — Senior Software Engineer · Audio DSP & AI Systems" />
</a>

<br/><br/>

<!-- ░░ QUICK NAV ░░ -->
<a href="#-engineering-journey"><img src="https://img.shields.io/badge/01-Journey-0EA5E9?style=for-the-badge&labelColor=0B1222" /></a>
<a href="#-flagship-architectures"><img src="https://img.shields.io/badge/02-Flagship_Builds-6366F1?style=for-the-badge&labelColor=0B1222" /></a>
<a href="#-technical-arsenal"><img src="https://img.shields.io/badge/03-Arsenal-2DD4BF?style=for-the-badge&labelColor=0B1222" /></a>
<a href="#-github-signal"><img src="https://img.shields.io/badge/04-Signal-A855F7?style=for-the-badge&labelColor=0B1222" /></a>
<a href="#-get-in-touch"><img src="https://img.shields.io/badge/05-Contact-F59E0B?style=for-the-badge&labelColor=0B1222" /></a>

</div>

<br/>

```ts
const engineer = {
  name:    "Trần Thanh Hải",
  role:    "Senior Software Engineer · Audio DSP & AI Systems",
  origin:  "PHP / Laravel enterprise backend architecture",
  now:     ["Deep-Learning Audio DSP", "Forced Alignment", "Reverse Engineering"],
  stack:   { backend: ["PHP", "Laravel", "MySQL", "Redis"],
             ai:      ["PyTorch", "Demucs v4", "MMS-FA", "Faster-Whisper"] },
  motto:   "Clean code · minimal latency · zero unnecessary dependencies",
};
```

<div align="center">

<img src="https://img.shields.io/badge/-%20-0B1222?style=flat-square" />
<b>SIGNAL ░░░▒▒▒▓▓▓ FROM BACKEND ARCHITECTURE TO APPLIED AI ▓▓▓▒▒▒░░░</b>
<img src="https://img.shields.io/badge/-%20-0B1222?style=flat-square" />

</div>

---

### 🧭 Engineering Journey

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🧱 The Foundation — Enterprise Backend</h4>
      <p>My career was forged in the core of <b>PHP &amp; Laravel backend architecture</b>. Years of hands-on building gave me:</p>
      <ul>
        <li><b>Enterprise Architecture</b> — modular, scalable systems with <b>Laravel &amp; modern design patterns</b>.</li>
        <li><b>Data Integrity &amp; Scale</b> — relational modeling, indexing &amp; query tuning in <b>MySQL</b>.</li>
        <li><b>API Systems</b> — high-throughput REST, async job queues, webhook consumers, multi-tier auth.</li>
      </ul>
      <p><i>"This backend discipline set my standards: code modularity, minimal latency, zero wasted resources."</i></p>
    </td>
    <td width="50%" valign="top">
      <h4>🚀 The Frontier — AI Audio DSP</h4>
      <p>On those fundamentals I went deep into <b>Applied AI, Machine Learning &amp; Digital Signal Processing</b>:</p>
      <ul>
        <li><b>Stem Separation</b> — studio-grade 4-stem isolation with <b>Meta Demucs v4</b>.</li>
        <li><b>Forced Alignment</b> — sub-millisecond phoneme-to-audio sync via <b>Meta MMS-FA (CTC)</b> &amp; <b>Faster-Whisper</b>.</li>
        <li><b>Acoustic Fingerprinting</b> — pitch/tempo-resilient copyright detection with <b>Chroma-12 FFT</b>.</li>
        <li><b>Protocol Engineering</b> — session analysis &amp; pure-stdlib <b>RSA PKCS#1 v1.5</b> crypto.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 💎 Flagship Architectures

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>🎤 <a href="https://github.com/tranthanhhai1997/auto-karaoke-maker">Auto-Karaoke Maker</a></h4>
      <p>End-to-end engine turning raw song audio into studio-grade 1080p karaoke video with millisecond syllable highlighting.</p>
      <ul>
        <li><b>Dual Alignment</b> — MMS-FA (CTC) for Vietnamese syllables + Faster-Whisper for international lyrics.</li>
        <li><b>Acoustic Isolation</b> — Demucs v4 HTDemucs stem extraction.</li>
        <li><b>Standards-Compliant</b> — ASS subtitles with <code>{\k}</code> karaoke tags for Aegisub, VLC, CapCut, Premiere.</li>
      </ul>
      <img src="https://img.shields.io/badge/MMS--FA-CTC-0EA5E9?style=flat-square&labelColor=0B1222" />
      <img src="https://img.shields.io/badge/Demucs_v4-Stems-2DD4BF?style=flat-square&labelColor=0B1222" />
      <img src="https://img.shields.io/badge/FFmpeg-1080p-F59E0B?style=flat-square&labelColor=0B1222" />
    </td>
    <td width="50%" valign="top">
      <h4>🔍 <a href="https://github.com/tranthanhhai1997/music-copyright-hunter">Music Copyright &amp; Re-upload Hunter</a></h4>
      <p>High-speed audio copyright &amp; re-upload scanner, resilient to pitch shifts and speed changes.</p>
      <ul>
        <li><b>Chroma-12 FFT</b> — 12-D harmonic chromagram (80Hz–4kHz) with prefix-sum Pearson correlation.</li>
        <li><b>Pitch &amp; Tempo Invariant</b> — survives −5…+6 semitones and 0.88×–1.15× stretch.</li>
        <li><b>No Full Download</b> — direct 40s stream slicing via FFmpeg pipe.</li>
      </ul>
      <img src="https://img.shields.io/badge/Chroma--12-FFT-A855F7?style=flat-square&labelColor=0B1222" />
      <img src="https://img.shields.io/badge/Invariant-Key_%26_Tempo-EC4899?style=flat-square&labelColor=0B1222" />
      <img src="https://img.shields.io/badge/Stream-40s_Slice-0EA5E9?style=flat-square&labelColor=0B1222" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🎵 <a href="https://github.com/tranthanhhai1997/suno-master-prompt-builder">Suno Master Prompt Studio</a></h4>
      <p>Full-stack AI songwriting &amp; prompt studio for Suno AI (v5 / v6 / v6-wild), zero external dependencies.</p>
      <ul>
        <li><b>Rhyming Engine</b> — raw text → natural Vietnamese poetry (Intro → Verse → Hook → Outro).</li>
        <li><b>V6 Producer Briefs</b> — Identity → Pulse → Players → Performance → Arc → Mix.</li>
        <li><b>Zero-Dependency UI</b> — modern dark-mode web UI on the Python standard library.</li>
      </ul>
      <img src="https://img.shields.io/badge/Suno-v5_%7C_v6-EAB308?style=flat-square&labelColor=0B1222" />
      <img src="https://img.shields.io/badge/Rhyme-Vietnamese-EF4444?style=flat-square&labelColor=0B1222" />
      <img src="https://img.shields.io/badge/Zero_Pip-Built--in_Web-0EA5E9?style=flat-square&labelColor=0B1222" />
    </td>
    <td width="50%" valign="top">
      <h4>🎬 <a href="https://github.com/tranthanhhai1997/ai-video-translator-and-dubbing">AI Video Translator &amp; Dubbing</a></h4>
      <p>Autonomous pipeline for multi-platform video download, transcription, translation and AI voice dubbing.</p>
      <ul>
        <li><b>Multi-Source Ingestion</b> — clean MP4s from TikTok, Douyin, YouTube, Facebook, Bilibili via <code>yt-dlp</code>.</li>
        <li><b>Speech &amp; Timing</b> — contextual subtitle segmentation + FFmpeg <code>atempo</code> stretching.</li>
        <li><b>Studio Ducking</b> — background-music sidechaining (−14dB) under voiceover.</li>
      </ul>
      <img src="https://img.shields.io/badge/yt--dlp-Clean_MP4-EF4444?style=flat-square&labelColor=0B1222" />
      <img src="https://img.shields.io/badge/Whisper-ASR-0EA5E9?style=flat-square&labelColor=0B1222" />
      <img src="https://img.shields.io/badge/Ducking--14dB-2DD4BF?style=flat-square&labelColor=0B1222" />
    </td>
  </tr>
</table>

<details>
  <summary><b>🧪 Deep-tech case study — Audio protocol reverse engineering</b></summary>
  <br/>
  <blockquote>
    <b>🗣️ <a href="https://github.com/tranthanhhai1997/capcut-elevenlabs-tts">Desktop TTS Protocol Reverse Engineering</a></b><br/>
    A research project analysing a desktop client's signed-request protocol and re-implementing its signing scheme from scratch:
    <ul>
      <li><b>Zero-Dependency RSA PKCS#1 v1.5 Signer</b> — 2048-bit RSA in the pure Python standard library, no PyCryptodome / OpenSSL.</li>
      <li><b>Drop-in Microservice</b> — OpenAI <code>/v1/audio/speech</code>-compatible local endpoint.</li>
      <li><b>Millisecond Timestamps</b> — word-level start/end times for real-time captioning.</li>
    </ul>
  </blockquote>
</details>

---

### ⚡ Technical Arsenal

<div align="center">

<table width="100%">
  <tr>
    <td width="33%" align="center" valign="top">
      <h4>🧩 Core Backend</h4>
      <img src="https://skillicons.dev/icons?i=php,laravel,python,ts,mysql&perline=5" /><br/><br/>
      <code>PHP 8.x · OOP &amp; Patterns</code><br/>
      <code>Laravel / Lumen</code><br/>
      <code>Python 3.10+ · AsyncIO / Ctypes</code><br/>
      <code>TypeScript · Node.js</code><br/>
      <code>MySQL · Redis · REST / MVC</code>
    </td>
    <td width="33%" align="center" valign="top">
      <h4>🧠 AI &amp; Audio DSP</h4>
      <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,fastapi&perline=5" /><br/><br/>
      <code>PyTorch · Torchaudio</code><br/>
      <code>Meta Demucs v4 (HTDemucs)</code><br/>
      <code>Meta MMS-FA (CTC Trellis)</code><br/>
      <code>Faster-Whisper (CTranslate2)</code><br/>
      <code>Chroma-12 FFT Spectrograms</code>
    </td>
    <td width="33%" align="center" valign="top">
      <h4>⚙️ Systems &amp; Media</h4>
      <img src="https://skillicons.dev/icons?i=docker,git,bash,linux,vscode&perline=5" /><br/><br/>
      <code>FFmpeg Audio/Video Filters</code><br/>
      <code>yt-dlp Extraction</code><br/>
      <code>RSA Crypto &amp; Protocols</code><br/>
      <code>Docker · Microservices</code><br/>
      <code>Git · GitHub Actions CI/CD</code>
    </td>
  </tr>
</table>

</div>

---

### 📡 GitHub Signal

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=tranthanhhai1997&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=05070E&title_color=38BDF8&icon_color=2DD4BF&text_color=94A3B8" />
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tranthanhhai1997&layout=compact&theme=tokyonight&hide_border=true&bg_color=05070E&title_color=38BDF8&text_color=94A3B8&langs_count=8" />

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=tranthanhhai1997&theme=tokyonight&hide_border=true&background=05070E&ring=38BDF8&fire=2DD4BF&currStreakLabel=38BDF8" />

</div>

---

<div align="center">

### 📬 Get in Touch

<a href="https://github.com/tranthanhhai1997"><img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0B1222" /></a>
&nbsp;
<a href="https://www.facebook.com/profile.php?id=100004022911152"><img src="https://img.shields.io/badge/Facebook-Connect-1877F2?style=for-the-badge&logo=facebook&logoColor=white&labelColor=0B1222" /></a>
&nbsp;
<a href="mailto:tranthanhhai1997@gmail.com"><img src="https://img.shields.io/badge/Email-Direct_Inquiry-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0B1222" /></a>

<br/><br/>

<img src="https://raw.githubusercontent.com/tranthanhhai1997/tranthanhhai1997/main/assets/footer-banner.svg" width="100%" alt="From backend architecture to the frontier of AI audio" />

</div>
