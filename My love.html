<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For My Angel | Pattuma</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&family=Playfair+Display:ital,wght@0,700;1,700&display=swap" rel="stylesheet">
    
    <style>
        :root { --primary: #ff3e8d; --bg: #030712; }
        body { background-color: var(--bg); color: white; font-family: 'Inter', sans-serif; overflow-x: hidden; margin: 0; }
        .glass { background: rgba(255, 255, 255, 0.03); backdrop-filter: blur(15px); border: 1px solid rgba(255, 255, 255, 0.08); border-radius: 28px; }
        .text-gradient { background: linear-gradient(to right, #ff3e8d, #a855f7); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .snow-container { position: fixed; top: 0; left: 0; right: 0; bottom: 0; pointer-events: none; z-index: 1; }
        .snow { position: absolute; background: white; border-radius: 50%; opacity: 0.6; animation: fall linear infinite; }
        @keyframes fall { 0% { transform: translateY(-10vh) translateX(0); } 100% { transform: translateY(110vh) translateX(20px); } }
        .hidden-step { display: none; opacity: 0; }
        .float { animation: floating 3s ease-in-out infinite; }
        @keyframes floating { 0%, 100% { transform: translateY(0); } 50% { transform: translateY(-10px); } }
    </style>
</head>
<body>

    <div class="snow-container" id="snow-container"></div>
    
    <audio id="bgMusic" loop>
        <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
    </audio>

    <section id="step-1" class="min-h-screen flex flex-col items-center justify-center p-6 text-center relative z-10">
        <div class="max-w-3xl">
            <h2 class="text-xs uppercase tracking-[0.6em] mb-6 opacity-50">December 25, 2025</h2>
            <h1 class="text-6xl md:text-8xl font-bold mb-10 font-['Playfair_Display'] leading-tight">
                A Christmas <span class="text-gradient italic">Miracle</span> for Pattuma.
            </h1>
            <button onclick="startExperience()" class="bg-white text-black px-12 py-5 rounded-full font-bold text-lg tracking-widest uppercase hover:scale-105 transition-transform">
                Open what I made ❤️
            </button>
        </div>
    </section>

    <section id="step-2" class="hidden-step min-h-screen flex flex-col items-center justify-center p-6 relative z-10">
        <div class="glass p-12 max-w-2xl text-center">
            <div class="mb-8 inline-block float text-pink-500">
                <svg width="70" height="70" viewBox="0 0 24 24" fill="currentColor"><path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"/></svg>
            </div>
            <p class="text-gray-300 text-xl italic font-light mb-8">
                "My life was like a curse, but when you came into my life, everything changed. You are my angel, Pattuma."
            </p>
            <button onclick="nextStep(3)" class="text-pink-400 font-medium tracking-widest uppercase text-sm">Next →</button>
        </div>
    </section>

    <section id="step-3" class="hidden-step min-h-screen flex flex-col items-center justify-center p-6 relative z-10">
        <div class="text-center">
            <h1 class="text-7xl md:text-[100px] font-black mb-6 text-gradient font-['Playfair_Display']">MY LOVE</h1>
            <h2 class="text-2xl mb-12 opacity-80">Merry Christmas, Pattu!</h2>
            
            <div id="date-invite" class="glass p-8 max-w-md mx-auto mb-10 border-pink-500/30">
                <p class="mb-6 font-semibold">Since you saved my world... will you be my love forever?</p>
                <div class="flex justify-center gap-4">
                    <button onclick="accepted()" class="bg-pink-600 px-8 py-2 rounded-lg hover:bg-pink-500 transition-all">Yes!</button>
                    <button onmouseover="moveNo(this)" class="bg-gray-800 px-8 py-2 rounded-lg cursor-default">No</button>
                </div>
            </div>

            <p class="mt-8 text-sm opacity-50 italic">From SPFIGHTS, with all my love. 😘</p>
        </div>
    </section>

    <script>
        // Snow Effect
        const snowContainer = document.getElementById('snow-container');
        for (let i = 0; i < 40; i++) {
            const snow = document.createElement('div');
            snow.className = 'snow';
            snow.style.width = Math.random() * 4 + 'px';
            snow.style.height = snow.style.width;
            snow.style.left = Math.random() * 100 + 'vw';
            snow.style.animationDuration = (Math.random() * 3 + 3) + 's';
            snowContainer.appendChild(snow);
        }

        function startExperience() {
            document.getElementById('bgMusic').play();
            nextStep(2);
        }

        function nextStep(step) {
            const current = document.querySelector('section:not(.hidden-step)');
            const next = document.getElementById(`step-${step}`);
            current.style.opacity = '0';
            setTimeout(() => {
                current.classList.add('hidden-step');
                next.classList.remove('hidden-step');
                setTimeout(() => { next.style.transition = 'opacity 1s'; next.style.opacity = '1'; }, 50);
            }, 600);
            if(step === 3) setTimeout(fireConfetti, 500);
        }

        function moveNo(btn) {
            btn.style.position = 'absolute';
            btn.style.left = Math.random() * 80 + '%';
            btn.style.top = Math.random() * 80 + '%';
        }

        function accepted() {
            document.getElementById('date-invite').innerHTML = "<h2 class='text-2xl font-bold text-pink-400 animate-bounce'>I LOVE YOU! PATTUMA ❤️ See you soon,MY Angel!</h2>";
            fireConfetti();
        }

        function fireConfetti() {
            confetti({ particleCount: 150, spread: 70, origin: { y: 0.6 } });
        }
    </script>
</body>
</html>
