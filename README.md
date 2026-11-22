# Hi, I'm Manomay

CS student who likes building things from scratch: terminal apps, Linux desktop tooling and ML pipelines, mostly in Java and Python.

Currently looking for **Software/ML Engineering Internships**.

## Projects

**[bloombox](https://github.com/TheyCallMePBJ/bloombox-java)** · Java
A terminal music player for Linux that searches by title, artist, album **and lyrics** as you type. The search structures (radix trie, Bloom filter, KMP) are written from scratch, unit-tested and benchmarked against simpler baselines. It also has synced lyrics, album art in the terminal, colour themes taken from the album cover (k-means++ in CIELAB), an FFT spectrum visualizer and MPRIS media-key support.

**[Krishi Saathi](https://github.com/TheyCallMePBJ/farmeradvisory)** · Python, FastAPI, Gemini
A WhatsApp chatbot that gives grape farmers in Maharashtra advice in Marathi, Hindi or English, by text or voice note. It combines live weather data with Gemini to judge disease risk and spraying conditions and give exact doses. Per-user async locks and message deduplication keep it correct under rapid messages and webhook retries.

**[Delhivery Delay Intelligence](https://github.com/TheyCallMePBJ/iitr-aiml-capstone)** · Python, scikit-learn
An end-to-end ML pipeline on synthetic parcel-delivery data: delivery-time regression (test R² 0.95), delay prediction with an alert threshold chosen for recall, and clustering of hubs. Every table and model can be regenerated from a clean clone.

**[MAL Tracker for Paperback 0.8](https://github.com/TheyCallMePBJ/paperback-mal-tracker-0.8)** · TypeScript
A fixed MyAnimeList tracker for the Paperback iOS manga reader. Logins expired after ~16 days because of an endless token-refresh loop, and MAL rejected chapter syncs. Both are fixed, along with several smaller bugs. GitHub Actions builds and publishes it, and people install it from the [project page](https://theycallmepbj.github.io/paperback-mal-tracker-0.8/).

**[Vesper](https://github.com/TheyCallMePBJ/vesper)** · QML, Quickshell
The desktop shell I use every day on Hyprland: a widget bar you arrange from a settings window, a control centre, network, Bluetooth and audio panels, its own notification daemon and on-screen displays. Settings reload live, with 8 built-in themes plus your own.

**[clipdeck](https://github.com/TheyCallMePBJ/clipdeck)** · Rust
A clipboard history popup for Wayland, built on cliphist. Fuzzy search, text and image previews, pins that survive history wipes, and live reload when the history changes. It keeps no copy of the history, so it never falls out of sync with cliphist.

**[FinTrack](https://github.com/TheyCallMePBJ/fintrack)** · Java, Spring Boot
A personal finance web app. You can log transactions in plain English ("spent 500 on food yesterday"), track goals, and see spending insights and Chart.js reports. Data is stored in MariaDB through JPA/Hibernate.

## Tech

- **Languages:** Java, Python, TypeScript, QML, Lua, SQL, Rust
- **Backend & data:** Spring Boot, FastAPI, JPA/Hibernate, MariaDB, SQLite, pandas, scikit-learn
- **Tools:** Linux, Git, GitHub Actions, Maven, Azure App Service

## Contact

[LinkedIn](https://www.linkedin.com/in/manomay-gadiyar)
