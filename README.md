# 💫 About Me:
## 👨‍💻 About Me<br><br>Hey there! I’m **Krishna Semwal**, also known as **KrixyBhai** —  <br>a passionate **student developer**, **digital creator**, and **tech explorer**.  <br><br>I enjoy turning ideas into fully functional web apps using **HTML, CSS, and JavaScript**,  <br>and love experimenting with **modern UI design, animations, and API integration**.  <br><br>My goal is to build web experiences that are not just powerful,  <br>but also fast, beautiful, and fun — just like **KrixyBhai Smart Intent Search**.  <br><br>---<br><br>### 🧠 Skills & Interests<br>- 💻 Frontend Development (HTML, CSS, JS)<br>- 🎮 Game Development (Wordle, 2048, Flappy Bird, Tic Tac Toe)<br>- ⚙️ SEO & YouTube Algorithm Optimization<br>- 🎨 UI/UX Design & Animation<br>- 🔍 AI-based Search Systems & Smart Tools<br>- 📹 Video Editing & Creative Content  <br><br>---<br><br>### 🌱 Currently Working On<br>- Expanding **KrixyBhai Smart Intent Search** <br><br>---<br><br>### 🚀 Vision<br>> “To create digital tools that make learning, searching, and exploring smarter, faster, and more fun — for everyone.”<br><br>---<br><br>### 📫 Connect with Me<br>- 💬 **Email:** Krixybhaigaming@gmail.com<br>- 🕹️ **Project:** [KrixyBhai Smart Intent Search](#)<br><br>---<br><br>⭐ _Thanks for checking out my project!_  <br>If you like it, **star this repo** — it motivates me to keep building awesome things! 🚀


## 🌐 Socials:
[![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:Krixybhaigaming@gmail.com) 

# 💻 Tech Stack:
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=Krixybhai&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=Krixybhai&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Krixybhai&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=Krixybhai&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->                        card: '#ffffff',
                    },
                    dark: {
                        bg: '#0d0d0d',
                        text: '#ffffff',
                        card: '#1a1a1a',
                    }
                },
                boxShadow: {
                    'accent': '0 0 15px var(--accent-color)',
                    'accent-lg': '0 0 25px var(--accent-color)',
                },
                keyframes: {
                    glow: {
                        '0%, 100%': { textShadow: '0 0 5px var(--accent-color)' },
                        '50%': { textShadow: '0 0 20px var(--accent-color)' },
                    },
                    popIn: {
                        '0%': { transform: 'scale(0.9)', opacity: '0' },
                        '100%': { transform: 'scale(1)', opacity: '1' },
                    },
                    wave: {
                        '0%': { transform: 'scale(1)', opacity: 0.7 },
                        '100%': { transform: 'scale(2.5)', opacity: 0 },
                    }
                },
                animation: {
                    glow: 'glow 2s ease-in-out infinite',
                    popIn: 'popIn 0.5s ease-out forwards',
                    wave: 'wave 1.5s infinite cubic-bezier(0.4, 0, 0.2, 1)',
                }
            },
        },
    }
    </script>

    <!-- Custom Styles -->
    <style>
        :root {
            --accent-color: hsl(168, 100%, 50%);
        }
        html:not(.dark) {
            --accent-color: hsl(200, 100%, 43%);
        }
        .text-accent { color: var(--accent-color); }
        .border-accent { border-color: var(--accent-color); }
        .bg-accent { background-color: var(--accent-color); }
        .shadow-accent { box-shadow: 0 0 15px var(--accent-color); }
        .shadow-accent-lg { box-shadow: 0 0 25px var(--accent-color); }
        .hover\:shadow-accent:hover { box-shadow: 0 0 15px var(--accent-color); }
        .focus\:border-accent:focus { border-color: var(--accent-color); }
        .hover\:text-accent:hover { color: var(--accent-color); }
    </style>

    <!-- React and Babel for running JSX in the browser -->
    <script src="https://unpkg.com/react@18/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
</head>
<body class="bg-light-bg dark:bg-dark-bg text-light-text dark:text-dark-text transition-colors duration-300">
    <div id="root"></div>

    <!-- Application Logic (All JS/TSX files combined) -->
    <script type="text/babel">
        const { useState, useEffect, useCallback, useRef } = React;

        // --- Audio Service ---
        const sounds = {
            click: 'data:audio/wav;base64,UklGRigAAABXQVZFZm10IBIAAAABAAEARKwAAIhYAQACABAAAABkYXRhAgAAAAEA',
            swoosh: 'data:audio/wav;base64,UklGRiQAAABXQVZFZm10IBAAAAABAAEARKwAAIhYAQACABAAAABkYXRhAAAAAIA/Pz78/PXs6uXg08zEyLiwq6iYlY+Ae3JsZWFdVEtBPTw2MSsnJiQiHhwbGhgYGRkWFhYWFhUVFRQUExMSEhEREBEQDg4NDA0MDAsLCwoKCgkJBwcGBgUFBAQDAwEBAAAA',
            micOn: 'data:audio/wav;base64,UklGRjwAAABXQVZFZm10IBAAAAABAAEARKwAAIhYAQACABAAAABkYXRhJAAAADw/P/768uXh3NrY1s/Ozs3Nzs3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3N-AQ==',
            micOff: 'data:audio/wav;base64,UklGRjwAAABXQVZFZm10IBAAAAABAAEARKwAAIhYAQACABAAAABkYXRhJAAAADw/P/768uXh3NrY1s/Ozs3Nzs3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3Nzc3N-AQ==',
        };

        const playSound = (name) => {
            try {
                const audio = new Audio(sounds[name]);
                audio.play().catch(e => console.error("Audio play failed:", e));
            } catch (error) {
                console.error(`Error playing sound: ${name}`, error);
            }
        };

        // --- API Service ---
        async function searchWikipedia(query) {
            if (!query) return [];
            const url = `https://en.wikipedia.org/w/api.php?origin=*&action=query&list=search&srsearch=${encodeURIComponent(query)}&format=json`;
            const response = await fetch(url);
            if (!response.ok) throw new Error('Wikipedia API request failed');
            const data = await response.json();
            return data.query ? data.query.search : [];
        }

        // --- Icons ---
        const SearchIcon = () => (
            <svg xmlns="http://www.w3.org/2000/svg" className="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
            </svg>
        );

        const HistoryIcon = () => (
            <svg xmlns="http://www.w3.org/2000/svg" className="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
        );

        const ThemeIcon = () => (
            <svg xmlns="http://www.w3.org/2000/svg" className="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M20.354 15.354A9 9 0 018.646 3.646 9.003 9.003 0 0012 21a9.003 9.003 0 008.354-5.646z" /></svg>
        );

        const ClearIcon = () => (
            <svg xmlns="http://www.w3.org/2000/svg" className="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M19 7l-.867 12.142A2 2 0 0116.138 21H7.862a2 2 0 01-1.995-1.858L5 7m5 4v6m4-6v6m1-10V4a1 1 0 00-1-1h-4a1 1 0 00-1 1v3M4 7h16" /></svg>
        );

        const MenuIcon = ({ isOpen }) => (
            <svg xmlns="http://www.w3.org/2000/svg" className={`h-8 w-8 transition-transform duration-300 ${isOpen ? 'rotate-90' : ''}`} fill="none" viewBox="0 0 24 24" stroke="currentColor">
                {isOpen ? <path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M6 18L18 6M6 6l12 12" /> : <path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M4 6h16M4 12h16M4 18h16" />}
            </svg>
        );

        const MicIcon = () => (
            <svg xmlns="http://www.w3.org/2000/svg" className="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" strokeWidth={2}>
                <path strokeLinecap="round" strokeLinejoin="round" d="M19 11a7 7 0 01-7 7m0 0a7 7 0 01-7-7m7 7v4m0 0H8m4 0h4m-4-8a3 3 0 01-3-3V5a3 3 0 116 0v6a3 3 0 01-3 3z" />
            </svg>
        );

        // --- Sub-Components ---
        const SearchForm = ({ mode, onModeChange, searchTerm, onSearchTermChange, onSearchSubmit, isListening, onVoiceSearch, isVoiceSupported }) => {
            const placeholders = {
                wikipedia: 'Search Wikipedia (live)...',
                google: 'Search Google...',
            };
            const modeButtonClasses = (buttonMode) => 
                `search-mode-btn px-4 py-2 text-sm font-semibold rounded-t-lg transition-all duration-300 ${
                mode === buttonMode 
                ? 'bg-accent text-dark-bg' 
                : 'bg-light-card/50 dark:bg-dark-card/50 text-gray-500 hover:bg-accent/20'}`;

            return (
                <div id="search-container" className="w-full mb-8">
                    <div className="flex justify-center space-x-1">
                        <button onClick={() => onModeChange('wikipedia')} className={modeButtonClasses('wikipedia')}>Wikipedia</button>
                        <button onClick={() => onModeChange('google')} className={modeButtonClasses('google')}>Google</button>
                    </div>
                    <form onSubmit={onSearchSubmit} className="relative">
                        <input 
                            type="text" 
                            value={searchTerm}
                            onChange={(e) => onSearchTermChange(e.target.value)}
                            placeholder={placeholders[mode]} 
                            className="w-full p-4 pl-5 pr-24 text-base text-light-text dark:text-dark-text bg-light-card dark:bg-dark-card border-2 border-transparent focus:border-accent focus:ring-0 outline-none rounded-b-lg rounded-tr-lg shadow-lg transition-all" />
                        <div className="absolute inset-y-0 right-0 flex items-center pr-4 space-x-2">
                            <button 
                                type="button" 
                                onClick={onVoiceSearch}
                                disabled={!isVoiceSupported}
                                title={isVoiceSupported ? "Start voice search" : "Voice search is not supported by your browser"}
                                className="relative text-gray-400 hover:text-accent disabled:text-gray-600 disabled:cursor-not-allowed transition-colors p-2" 
                                aria-label="Start voice search">
                                {isListening && (
                                    <React.Fragment>
                                        <span className="absolute inset-0.5 rounded-full bg-accent/20 animate-wave"></span>
                                        <span className="absolute inset-0.5 rounded-full bg-accent/20 animate-wave" style={{ animationDelay: '0.5s' }}></span>
                                    </React.Fragment>
                                )}
                                <MicIcon />
                            </button>
                            <button type="submit" className="text-gray-400 hover:text-accent transition-colors" aria-label="Submit search">
                                <SearchIcon />
                            </button>
                        </div>
                    </form>
                </div>
            );
        };

        const ResultsList = ({ results, isLoading, error, mode }) => {
            if (isLoading) {
                return <div className="flex justify-center items-center py-10"><div className="w-16 h-16 border-4 border-dashed rounded-full animate-spin border-accent"></div></div>;
            }
            if (error) {
                return <div className="text-center py-10 text-red-500">{error}</div>;
            }
            if (!results || results.length === 0) return null;

            const cardBaseClass = `bg-light-card/80 dark:bg-dark-card/80 backdrop-blur-sm p-5 rounded-xl shadow-lg hover:shadow-accent transition-all duration-300 animate-popIn`;

            return (
                <div id="results-display" className="space-y-4">
                    {results.map((result, index) => {
                        if (mode === 'wikipedia' && 'pageid' in result) {
                            return (
                                <div key={result.pageid} className={`cursor-pointer ${cardBaseClass}`} style={{animationDelay: `${index * 50}ms`}} onClick={() => window.open(`https://en.wikipedia.org/?curid=${result.pageid}`, '_blank')}>
                                    <h3 className="text-lg font-bold text-accent">{result.title}</h3>
                                    <p className="text-sm mt-1" dangerouslySetInnerHTML={{ __html: result.snippet + '...' }} />
                                </div>
                            );
                        }
                        if (mode === 'google' && 'query' in result) {
                            return (
                                <div key={result.query} className={`cursor-pointer ${cardBaseClass}`} onClick={() => window.open(`https://www.google.com/search?q=${encodeURIComponent(result.query)}`, '_blank')}>
                                    <h3 className="text-lg font-bold text-accent">Search on Google</h3>
                                    <p className="text-sm mt-1">Click here to see Google search results for "{result.query}"</p>
                                </div>
                            );
                        }
                        return null;
                    })}
                </div>
            );
        };

        const FloatingActionButton = ({ isOpen, onToggle, onClear, onToggleTheme, onShowHistory }) => (
            <div className="fixed bottom-6 right-6 z-50">
                {isOpen && (
                    <div className="flex flex-col items-end gap-4 mb-4">
                        <div className="flex items-center justify-end gap-3 animate-popIn" style={{animationDelay: '0ms'}}>
                            <span className="bg-dark-card/80 text-white px-3 py-1 rounded-md text-sm shadow-md">History</span>
                            <button onClick={onShowHistory} className="w-12 h-12 rounded-full bg-accent text-dark-bg flex items-center justify-center shadow-accent-lg hover:bg-accent-dark transition-transform hover:scale-110" aria-label="Show history"><HistoryIcon /></button>
                        </div>
                        <div className="flex items-center justify-end gap-3 animate-popIn" style={{animationDelay: '50ms'}}>
                            <span className="bg-dark-card/80 text-white px-3 py-1 rounded-md text-sm shadow-md">Theme</span>
                            <button onClick={onToggleTheme} className="w-12 h-12 rounded-full bg-accent text-dark-bg flex items-center justify-center shadow-accent-lg hover:bg-accent-dark transition-transform hover:scale-110" aria-label="Toggle theme"><ThemeIcon /></button>
                        </div>
                        <div className="flex items-center justify-end gap-3 animate-popIn" style={{animationDelay: '100ms'}}>
                            <span className="bg-dark-card/80 text-white px-3 py-1 rounded-md text-sm shadow-md">Clear</span>
                            <button onClick={onClear} className="w-12 h-12 rounded-full bg-accent text-dark-bg flex items-center justify-center shadow-accent-lg hover:bg-accent-dark transition-transform hover:scale-110" aria-label="Clear search"><ClearIcon /></button>
                        </div>
                    </div>
                )}
                <button onClick={onToggle} className="w-16 h-16 rounded-full bg-accent text-dark-bg flex items-center justify-center shadow-accent-lg hover:bg-accent-dark transition-transform duration-300 hover:scale-110 focus:outline-none" aria-label="Toggle menu">
                    <MenuIcon isOpen={isOpen} />
                </button>
            </div>
        );

        const HistoryPopup = ({isOpen, history, onClose, onClear, onItemClick}) => {
            if(!isOpen) return null;

            return (
                <div id="history-popup-container">
                    <div id="history-popup-overlay" className="fixed inset-0 bg-black/50 z-40" onClick={onClose}></div>
                    <div className="fixed bottom-24 right-6 w-full max-w-sm bg-light-card/80 dark:bg-dark-card/80 backdrop-blur-md text-light-text dark:text-dark-text border-2 border-accent/50 rounded-lg shadow-accent-lg z-50 animate-popIn">
                        <div className="p-4 border-b border-accent/30 flex justify-between items-center">
                            <h3 className="font-bold text-accent">Search History</h3>
                            {history.length > 0 && <button onClick={onClear} className="px-3 py-1 text-sm bg-accent/80 hover:bg-accent text-dark-bg rounded-md transition-colors">Clear</button>}
                        </div>
                        <ul id="history-list" className="p-4 max-h-60 overflow-y-auto">
                            {history.length === 0 ? (
                                <li className="text-gray-500">No history found.</li>
                            ) : (
                                history.map(item => (
                                    <li key={item} className="py-1">
                                        <button onClick={() => onItemClick(item)} className="w-full text-left hover:text-accent transition-colors truncate">{item}</button>
                                    </li>
                                ))
                            )}
                        </ul>
                    </div>
                </div>
            );
        };

        const ParticleCanvas = () => {
            const canvasRef = useRef(null);

            useEffect(() => {
                const canvas = canvasRef.current;
                if (!canvas) return;

                const ctx = canvas.getContext('2d');
                if (!ctx) return;

                let w = canvas.width = window.innerWidth;
                let h = canvas.height = window.innerHeight;
                let particles = [];

                const createParticles = () => {
                    particles = [];
                    const particleCount = window.innerWidth < 768 ? 50 : 100;
                    for (let i = 0; i < particleCount; i++) {
                        particles.push({
                            x: Math.random() * w, y: Math.random() * h,
                            radius: Math.random() * 2 + 1,
                            speedX: (Math.random() - 0.5) * 0.8,
                            speedY: (Math.random() - 0.5) * 0.8
                        });
                    }
                };
                
                let animationFrameId;
                const drawParticles = () => {
                    if(!ctx) return;
                    ctx.clearRect(0, 0, w, h);
                    const accentColor = getComputedStyle(document.documentElement).getPropertyValue('--accent-color');
                    ctx.fillStyle = accentColor.trim();
                    
                    particles.forEach(p => {
                        ctx.beginPath();
                        ctx.arc(p.x, p.y, p.radius, 0, Math.PI * 2);
                        ctx.fill();
                        p.x += p.speedX;
                        p.y += p.speedY;
                        if (p.x < 0 || p.x > w) p.speedX *= -1;
                        if (p.y < 0 || p.y > h) p.speedY *= -1;
                    });
                    animationFrameId = requestAnimationFrame(drawParticles);
                };
                
                const handleResize = () => {
                    w = canvas.width = window.innerWidth;
                    h = canvas.height = window.innerHeight;
                    createParticles();
                };

                createParticles();
                drawParticles();
                window.addEventListener('resize', handleResize);

                return () => {
                    window.removeEventListener('resize', handleResize);
                    cancelAnimationFrame(animationFrameId);
                }
            }, []);

            return <canvas ref={canvasRef} id="particle-canvas" className="fixed top-0 left-0 z-0"></canvas>;
        }

        // --- Main App Component ---
        const App = () => {
            const [theme, setTheme] = useState('dark');
            const [searchHistory, setSearchHistory] = useState([]);
            const [searchMode, setSearchMode] = useState('wikipedia');
            const [isFabOpen, setIsFabOpen] = useState(false);
            const [isHistoryOpen, setIsHistoryOpen] = useState(false);
            const [searchTerm, setSearchTerm] = useState('');
            const [results, setResults] = useState([]);
            const [isLoading, setIsLoading] = useState(false);
            const [error, setError] = useState(null);
            const [isListening, setIsListening] = useState(false);
            const [isVoiceSupported, setIsVoiceSupported] = useState(true);
            const recognitionRef = useRef(null);
            
            // --- State and LocalStorage Effects ---
            useEffect(() => {
                const storedTheme = localStorage.getItem('theme');
                const storedHistory = JSON.parse(localStorage.getItem('searchHistory') || '[]');
                if (storedTheme === 'light' || storedTheme === 'dark') {
                  setTheme(storedTheme);
                }
                setSearchHistory(storedHistory);
            }, []);

            useEffect(() => {
                if (theme === 'dark') {
                    document.documentElement.classList.add('dark');
                } else {
                    document.documentElement.classList.remove('dark');
                }
                localStorage.setItem('theme', theme);
            }, [theme]);
            
            useEffect(() => {
                localStorage.setItem('searchHistory', JSON.stringify(searchHistory));
            }, [searchHistory]);

            const addToHistory = (term) => {
                setSearchHistory(prev => [term, ...prev.filter(item => item !== term)].slice(0, 20));
            };

            // --- Search Logic ---
            const performSearch = useCallback(async (query) => {
                const trimmedQuery = query.trim();
                if (!trimmedQuery) {
                    setResults([]);
                    return;
                }

                setIsLoading(true);
                setError(null);
                addToHistory(trimmedQuery);

                try {
                    let searchResults = [];
                    if (searchMode === 'wikipedia') {
                        searchResults = await searchWikipedia(trimmedQuery);
                    } else if (searchMode === 'google') {
                        searchResults = [{ query: trimmedQuery }];
                    }
                    setResults(searchResults);
                    if(searchResults.length > 0) playSound('swoosh');
                } catch (err) {
                    setError('An error occurred. Please try again.');
                    console.error(err);
                } finally {
                    setIsLoading(false);
                }
            }, [searchMode]);
            
            // Debounced search for Wikipedia
            useEffect(() => {
                if (searchMode !== 'wikipedia' || !searchTerm || isListening) {
                    return;
                }
                const handler = setTimeout(() => {
                    performSearch(searchTerm);
                }, 500);

                return () => {
                    clearTimeout(handler);
                };
            }, [searchTerm, searchMode, performSearch, isListening]);

            // --- Speech Recognition ---
            useEffect(() => {
                const SpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;
                if (!SpeechRecognition) {
                    console.warn("Speech Recognition API not supported in this browser.");
                    setIsVoiceSupported(false);
                    return;
                }

                const recognition = new SpeechRecognition();
                recognition.continuous = false;
                recognition.interimResults = true;
                recognition.lang = 'en-US';

                recognition.onstart = () => {
                    setIsListening(true);
                    playSound('micOn');
                };
                recognition.onend = () => {
                    setIsListening(false);
                    playSound('micOff');
                };
                recognition.onerror = (event) => {
                    console.error('Speech recognition error:', event.error);
                    if (event.error === 'not-allowed' || event.error === 'service-not-allowed') {
                        setError("Microphone access denied. Please enable it in your browser settings.");
                    } else {
                        setError(`Voice search error: ${event.error}`);
                    }
                    setIsListening(false);
                };

                recognition.onresult = (event) => {
                    setError(null);
                    let finalTranscript = '';
                    for (let i = event.resultIndex; i < event.results.length; ++i) {
                        if (event.results[i].isFinal) {
                            finalTranscript += event.results[i][0].transcript;
                        } else {
                            // you can use the interim transcript for live feedback if needed
                        }
                    }
                    
                    const currentTranscript = event.results[event.results.length - 1][0].transcript;
                    setSearchTerm(currentTranscript);

                    if (finalTranscript) {
                       performSearch(finalTranscript);
                    }
                };
                
                recognitionRef.current = recognition;
            }, [performSearch]);

            // --- Event Handlers ---
            const handleSearchSubmit = (e) => {
                e.preventDefault();
                performSearch(searchTerm);

            };

            const handleModeChange = (mode) => {
                playSound('click');
                setSearchMode(mode);
                setSearchTerm('');
                setResults([]);
                setError(null);
            };

            const handleFabToggle = () => {
                playSound('swoosh');
                if(isHistoryOpen) setIsHistoryOpen(false);
                setIsFabOpen(prev => !prev);
            };

            const handleClearSearch = () => {
                playSound('click');
                setSearchTerm('');
                setResults([]);
                setIsFabOpen(false);
            };

            const handleToggleTheme = () => {
                playSound('click');
                setTheme(prev => prev === 'dark' ? 'light' : 'dark');
                setIsFabOpen(false);
            };
            
            const handleShowHistory = () => {
                playSound('click');
                setIsHistoryOpen(prev => !prev);
                setIsFabOpen(false);
            }
            
            const handleClearHistory = () => {
                playSound('click');
                setSearchHistory([]);
            }
            
            const handleHistoryItemClick = (query) => {
                playSound('click');
                setSearchTerm(query);
                setIsHistoryOpen(false);
                performSearch(query);
            }
            
            const handleVoiceSearch = () => {
                if (!isVoiceSupported) {
                    setError("Sorry, your browser doesn't support voice search.");
                    return;
                }
                
                if (isListening) {
                    recognitionRef.current?.stop();
                } else {
                    setError(null); // Clear errors before starting
                    recognitionRef.current?.start();
                }
            };

            return (
                <React.Fragment>
                    <ParticleCanvas />
                    <div className="relative z-10 flex flex-col items-center min-h-screen p-4 sm:p-6 md:p-8 overflow-x-hidden">
                        <header className="text-center my-8">
                            <h1 className="text-4xl sm:text-5xl md:text-6xl font-bold text-accent animate-glow">
                                Krixybhai
                            </h1>
                            <p className="text-sm sm:text-base text-gray-400 dark:text-gray-500 mt-2">
                                Your Smart Intent Search Engine
                            </p>
                        </header>

                        <main className="w-full max-w-2xl flex-grow">
                            <SearchForm 
                                mode={searchMode}
                                onModeChange={handleModeChange}
                                searchTerm={searchTerm}
                                onSearchTermChange={setSearchTerm}
                                onSearchSubmit={handleSearchSubmit}
                                isListening={isListening}
                                onVoiceSearch={handleVoiceSearch}
                                isVoiceSupported={isVoiceSupported}
                            />
                            <ResultsList
                                results={results}
                                isLoading={isLoading}
                                error={error}
                                mode={searchMode}
                            />
                        </main>
                        
                        <HistoryPopup 
                            isOpen={isHistoryOpen}
                            history={searchHistory}
                            onClose={() => setIsHistoryOpen(false)}
                            onClear={handleClearHistory}
                            onItemClick={handleHistoryItemClick}
                        />
                        
                        <FloatingActionButton 
                            isOpen={isFabOpen}
                            onToggle={handleFabToggle}
                            onClear={handleClearSearch}
                            onToggleTheme={handleToggleTheme}
                            onShowHistory={handleShowHistory}
                        />
                    </div>
                </React.Fragment>
            );
        };

        const rootElement = document.getElementById('root');
        const root = ReactDOM.createRoot(rootElement);
        root.render(
          <React.StrictMode>
            <App />
          </React.StrictMode>
        );
    </script>
</body>
</html>
