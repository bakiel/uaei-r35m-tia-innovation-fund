# 🎬 CINEMATIC PRESENTATION REBUILD PLAN
## **Stunning Animated Visuals + Magazine Design**

> **Mission**: Transform functional slides into **cinematic storytelling experiences** using surreal Midjourney art, epic photography, and breakthrough animations

**Status**: 🚀 Ready to Build
**Aesthetic**: **Magazine × Cinema × Surrealism**
**Animation Level**: **MAXIMUM**

---

## 🎨 Visual Asset Library

### **Category 1: Surreal Midjourney Art** (4 EPIC pieces)
Used for breakthrough moments, transformation, vision

```
1. judah6864_..._6f8dcb3d_1.png
   → Golden/orange shattering cosmic head with sparkles
   💡 USE FOR: Innovation reveals, breakthrough moments, transformation

2. judah6864_..._da35b6bb_0.png
   → Purple galaxy silhouette head (cosmic dreams)
   💡 USE FOR: Vision slides, future potential, scale-up dreams

3. judah6864_..._60ce14f0_1.png
   → Black/white starry minimalist head
   💡 USE FOR: Data/analytics, precision, sophistication

4. judah6864_..._720fd52f_3.png
   → Exploding light burst head (breakthrough!)
   💡 USE FOR: Success reveals, impact moments, final triumph
```

### **Category 2: Epic UAEI Covers** (9 cinematic shots)
```
01_african_woman_farmer_field.jpg       → Hero portraits, personal stories
02_tractor_plowing_sunset_silhouette.jpg → Operations, scale, machinery
03_farmer_crops_sunset_golden.jpg       → Harvest success, abundance
04_man_horse_rural_sunset.jpg           → Heritage, tradition, roots
05_harvest_field_sunset_golden.jpg      → Achievement, results
06_wheat_agriculture_sunset_dramatic.jpg → Growth, nature's beauty
07_african_giraffe_sunset_epic.jpg      → Conservation, wildlife moat
08_african_woman_farming_bright.jpg     → Optimism, bright future
09_african_farmers_field_work.jpg       → Teamwork, community, swarm
```

### **Category 3: Business Case Images** (60+ organized by theme)
```
People_Farmers/          → Portraits, groups, hands, markets
Technology_Innovation/   → Smartphones, IoT sensors, modern tech
Agriculture_Crops/       → Hands in soil, wheat, compost, macro
Landscape_Aerial/        → Savanna views, rolling farmland
Wildlife_Environment/    → Conservation, nature
Produce_Products/        → Organic nuts, arranged produce
Challenges_Problems/     → Dry land, old tractors, deterioration
```

---

## 🎥 CINEMATIC SLIDE-BY-SLIDE PLAN

### 📽️ **R15M PILOT PRESENTATION** (8 Slides)

#### **SLIDE 1: EXPLOSIVE HERO OPENING**
**Visual**: Surreal Midjourney #4 (Exploding Light Head) with dramatic parallax
**Animation**: Ken Burns zoom into light burst + particle explosion

```html
<div class="slide hero-cinematic active">
    <div class="parallax-bg" style="background-image: url('assets/midjourney_exploding_light.png')"></div>
    <div class="particle-overlay"></div>
    <div class="slide-overlay gradient-dramatic"></div>

    <div class="hero-content-cinematic">
        <div class="logo-entrance animate-scale-rotate">
            <img src="assets/UAEI Logo for dark BG.png" class="logo-glow-intense">
        </div>

        <h1 class="title-explosive">
            <span class="word-stagger" data-delay="0.1">R15M</span>
            <span class="word-stagger gradient-shimmer" data-delay="0.3">PILOT</span>
        </h1>

        <p class="subtitle-cinematic typewriter">
            100 Farmers • 6 Months • Breakthrough Validation
        </p>

        <div class="metrics-cinematic">
            <div class="metric-burst" data-delay="0.8">
                <span class="value-enormous counter-animate">R15M</span>
                <span class="label-glow">Investment</span>
            </div>
            <div class="arrow-pulse">→</div>
            <div class="metric-burst" data-delay="1.0">
                <span class="value-enormous counter-animate">6</span>
                <span class="label-glow">Months</span>
            </div>
            <div class="arrow-pulse">→</div>
            <div class="metric-burst" data-delay="1.2">
                <span class="value-enormous counter-animate">R508.6M</span>
                <span class="label-glow">Scale-Up</span>
            </div>
        </div>
    </div>

    <div class="scroll-indicator pulse-infinite">
        <i class="fas fa-chevron-down"></i>
    </div>
</div>
```

**CSS Magic**:
```css
.hero-cinematic {
    position: relative;
    overflow: hidden;
}

.parallax-bg {
    position: absolute;
    top: -10%;
    left: -10%;
    width: 120%;
    height: 120%;
    background-size: cover;
    background-position: center;
    animation: parallaxZoom 20s ease-in-out infinite alternate;
    filter: blur(2px);
}

@keyframes parallaxZoom {
    0% { transform: scale(1) translateY(0); }
    100% { transform: scale(1.15) translateY(-20px); }
}

.particle-overlay::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: radial-gradient(circle at 50% 50%,
        rgba(255,255,255,0.02) 0%,
        transparent 50%);
    animation: particleFloat 8s ease-in-out infinite;
}

.gradient-dramatic {
    background: linear-gradient(
        135deg,
        rgba(0,0,0,0.85) 0%,
        rgba(46,125,50,0.3) 50%,
        rgba(0,0,0,0.85) 100%
    );
}

.title-explosive {
    font-size: clamp(4rem, 12vw, 10rem);
    font-weight: 900;
    letter-spacing: -4px;
    line-height: 0.85;
    text-shadow:
        0 0 20px rgba(76,175,80,0.5),
        0 0 40px rgba(76,175,80,0.3),
        0 10px 60px rgba(0,0,0,0.8);
}

.word-stagger {
    display: inline-block;
    opacity: 0;
    transform: translateY(50px) rotateX(-90deg);
    animation: wordExplode 0.8s cubic-bezier(0.34, 1.56, 0.64, 1) forwards;
}

.word-stagger[data-delay="0.1"] { animation-delay: 0.1s; }
.word-stagger[data-delay="0.3"] { animation-delay: 0.3s; }

@keyframes wordExplode {
    0% {
        opacity: 0;
        transform: translateY(50px) rotateX(-90deg) scale(0.5);
    }
    60% {
        transform: translateY(-10px) rotateX(10deg) scale(1.1);
    }
    100% {
        opacity: 1;
        transform: translateY(0) rotateX(0) scale(1);
    }
}

.gradient-shimmer {
    background: linear-gradient(
        90deg,
        #4CAF50 0%,
        #8BC34A 25%,
        #4CAF50 50%,
        #2E7D32 75%,
        #4CAF50 100%
    );
    background-size: 200% auto;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: shimmerMove 3s linear infinite;
}

@keyframes shimmerMove {
    to { background-position: 200% center; }
}

.metric-burst {
    opacity: 0;
    transform: scale(0) rotate(-180deg);
    animation: burstIn 0.6s cubic-bezier(0.68, -0.55, 0.265, 1.55) forwards;
}

.metric-burst[data-delay="0.8"] { animation-delay: 0.8s; }
.metric-burst[data-delay="1.0"] { animation-delay: 1.0s; }
.metric-burst[data-delay="1.2"] { animation-delay: 1.2s; }

@keyframes burstIn {
    0% {
        opacity: 0;
        transform: scale(0) rotate(-180deg);
    }
    50% {
        transform: scale(1.2) rotate(10deg);
    }
    100% {
        opacity: 1;
        transform: scale(1) rotate(0);
    }
}

.value-enormous {
    font-size: clamp(3rem, 6vw, 5rem);
    font-weight: 900;
    color: #4CAF50;
    text-shadow:
        0 0 30px rgba(76,175,80,0.8),
        0 0 60px rgba(76,175,80,0.4);
}

.counter-animate {
    display: inline-block;
}

.scroll-indicator {
    position: absolute;
    bottom: 5vh;
    left: 50%;
    transform: translateX(-50%);
    font-size: 2rem;
    color: #4CAF50;
    opacity: 0.6;
}

.pulse-infinite {
    animation: pulseGlow 2s ease-in-out infinite;
}

@keyframes pulseGlow {
    0%, 100% {
        opacity: 0.4;
        transform: translateX(-50%) translateY(0);
    }
    50% {
        opacity: 1;
        transform: translateX(-50%) translateY(10px);
        text-shadow: 0 0 20px #4CAF50;
    }
}
```

**JavaScript Counter Animation**:
```javascript
function animateCounter(element, target, duration = 2000) {
    const start = 0;
    const increment = target / (duration / 16);
    let current = start;

    const timer = setInterval(() => {
        current += increment;
        if (current >= target) {
            element.textContent = target.toLocaleString();
            clearInterval(timer);
        } else {
            element.textContent = Math.floor(current).toLocaleString();
        }
    }, 16);
}

// Trigger on slide active
document.querySelectorAll('.counter-animate').forEach(el => {
    const target = parseFloat(el.textContent.replace(/[^0-9.]/g, ''));
    animateCounter(el, target);
});
```

---

#### **SLIDE 2: INVESTMENT LANDSCAPE REVEAL**
**Visual**: `02_tractor_plowing_sunset_silhouette.jpg` with cinematic widescreen treatment
**Animation**: Horizontal wipe reveal + data points fade in sequentially

```html
<div class="slide landscape-cinematic">
    <div class="widescreen-frame">
        <img class="bg-cinematic" src="assets/02_tractor_sunset.jpg">
        <div class="cinematic-bars"></div>
        <div class="vignette-overlay"></div>
    </div>

    <div class="content-over-cinema">
        <h2 class="slide-in-left">Investment Overview</h2>

        <div class="grid-landscape">
            <div class="data-card reveal-sequence" data-order="1">
                <div class="card-icon pulse-subtle">
                    <i class="fas fa-users"></i>
                </div>
                <h3>100 Farmers</h3>
                <p>Carefully selected smallholders</p>
                <div class="progress-bar">
                    <div class="progress-fill" data-width="100"></div>
                </div>
            </div>

            <div class="data-card reveal-sequence" data-order="2">
                <div class="card-icon pulse-subtle">
                    <i class="fas fa-calendar-alt"></i>
                </div>
                <h3>6 Months</h3>
                <p>Full season validation</p>
                <div class="progress-bar">
                    <div class="progress-fill" data-width="50"></div>
                </div>
            </div>

            <div class="data-card reveal-sequence" data-order="3">
                <div class="card-icon pulse-subtle">
                    <i class="fas fa-flask"></i>
                </div>
                <h3>5 Success Criteria</h3>
                <p>Pass ≥4 to unlock R508.6M</p>
                <div class="progress-bar">
                    <div class="progress-fill" data-width="80"></div>
                </div>
            </div>

            <div class="data-card reveal-sequence" data-order="4">
                <div class="card-icon pulse-subtle">
                    <i class="fas fa-rocket"></i>
                </div>
                <h3>R508.6M Ready</h3>
                <p>Conditional scale-up deployment</p>
                <div class="progress-bar">
                    <div class="progress-fill" data-width="100"></div>
                </div>
            </div>
        </div>
    </div>
</div>
```

**CSS Cinematic Treatment**:
```css
.widescreen-frame {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    overflow: hidden;
}

.bg-cinematic {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
    filter: brightness(0.4) contrast(1.2);
    animation: slowPan 30s ease-in-out infinite alternate;
}

@keyframes slowPan {
    0% { transform: scale(1.1) translateX(-20px); }
    100% { transform: scale(1.2) translateX(20px); }
}

.cinematic-bars::before,
.cinematic-bars::after {
    content: '';
    position: absolute;
    left: 0;
    width: 100%;
    height: 8vh;
    background: #000;
    z-index: 1;
}

.cinematic-bars::before { top: 0; }
.cinematic-bars::after { bottom: 0; }

.vignette-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: radial-gradient(
        ellipse at center,
        transparent 20%,
        rgba(0,0,0,0.7) 100%
    );
    pointer-events: none;
}

.grid-landscape {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: clamp(20px, 3vw, 40px);
    padding: clamp(30px, 5vh, 60px);
}

.data-card {
    background: rgba(0,0,0,0.85);
    border: 2px solid rgba(76,175,80,0.3);
    border-radius: 15px;
    padding: clamp(25px, 4vh, 40px);
    backdrop-filter: blur(20px);
    opacity: 0;
    transform: translateX(-50px) rotateY(-15deg);
    transition: all 0.5s cubic-bezier(0.34, 1.56, 0.64, 1);
}

.data-card.visible {
    opacity: 1;
    transform: translateX(0) rotateY(0);
}

.data-card:hover {
    border-color: #4CAF50;
    transform: translateY(-10px) scale(1.05);
    box-shadow: 0 20px 50px rgba(76,175,80,0.4);
}

.reveal-sequence[data-order="1"].visible { transition-delay: 0.1s; }
.reveal-sequence[data-order="2"].visible { transition-delay: 0.3s; }
.reveal-sequence[data-order="3"].visible { transition-delay: 0.5s; }
.reveal-sequence[data-order="4"].visible { transition-delay: 0.7s; }

.card-icon {
    width: 60px;
    height: 60px;
    background: linear-gradient(135deg, #4CAF50, #2E7D32);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.8rem;
    color: #fff;
    margin-bottom: 15px;
    box-shadow: 0 10px 25px rgba(76,175,80,0.3);
}

.pulse-subtle {
    animation: pulseSubtle 3s ease-in-out infinite;
}

@keyframes pulseSubtle {
    0%, 100% {
        transform: scale(1);
        box-shadow: 0 10px 25px rgba(76,175,80,0.3);
    }
    50% {
        transform: scale(1.05);
        box-shadow: 0 15px 35px rgba(76,175,80,0.5);
    }
}

.progress-bar {
    width: 100%;
    height: 6px;
    background: rgba(255,255,255,0.1);
    border-radius: 3px;
    overflow: hidden;
    margin-top: 15px;
}

.progress-fill {
    height: 100%;
    background: linear-gradient(90deg, #4CAF50, #8BC34A);
    border-radius: 3px;
    width: 0;
    transition: width 1.5s cubic-bezier(0.65, 0, 0.35, 1);
    box-shadow: 0 0 10px #4CAF50;
}

.data-card.visible .progress-fill {
    width: var(--target-width, 100%);
}

.progress-fill[data-width="100"] { --target-width: 100%; }
.progress-fill[data-width="80"] { --target-width: 80%; }
.progress-fill[data-width="50"] { --target-width: 50%; }
```

---

#### **SLIDE 3: SUCCESS CRITERIA MATRIX**
**Visual**: Midjourney #3 (Black/white starry head) - precision & sophistication
**Animation**: Grid cells flip-in 3D with stagger

```html
<div class="slide matrix-slide">
    <div class="split-visual-data">
        <div class="visual-half">
            <img src="assets/midjourney_bw_stars.png" class="portrait-art">
            <div class="art-caption fade-in-up">
                "Precision-Driven Validation"
            </div>
        </div>

        <div class="data-half">
            <h2 class="matrix-title glitch-effect">5 Success Criteria</h2>
            <p class="matrix-subtitle">Pass/Fail Gates — Need ≥4 to unlock R508.6M</p>

            <div class="criteria-grid-3d">
                <div class="criterion-cell flip-in" data-order="1">
                    <div class="cell-inner">
                        <div class="cell-front">
                            <div class="criterion-number">1</div>
                            <h4>Tech Adoption</h4>
                        </div>
                        <div class="cell-back">
                            <div class="target-huge">≥85%</div>
                            <p>Daily platform usage</p>
                        </div>
                    </div>
                </div>

                <div class="criterion-cell flip-in" data-order="2">
                    <div class="cell-inner">
                        <div class="cell-front">
                            <div class="criterion-number">2</div>
                            <h4>Retention</h4>
                        </div>
                        <div class="cell-back">
                            <div class="target-huge">≥90%</div>
                            <p>Complete 6 months</p>
                        </div>
                    </div>
                </div>

                <div class="criterion-cell flip-in" data-order="3">
                    <div class="cell-inner">
                        <div class="cell-front">
                            <div class="criterion-number">3</div>
                            <h4>Credit Score</h4>
                        </div>
                        <div class="cell-back">
                            <div class="target-huge">≥75%</div>
                            <p>AI accuracy</p>
                        </div>
                    </div>
                </div>

                <div class="criterion-cell flip-in" data-order="4">
                    <div class="cell-inner">
                        <div class="cell-front">
                            <div class="criterion-number">4</div>
                            <h4>Yield Boost</h4>
                        </div>
                        <div class="cell-back">
                            <div class="target-huge">≥30%</div>
                            <p>vs provincial avg</p>
                        </div>
                    </div>
                </div>

                <div class="criterion-cell flip-in" data-order="5">
                    <div class="cell-inner">
                        <div class="cell-front">
                            <div class="criterion-number">5</div>
                            <h4>Default Rate</h4>
                        </div>
                        <div class="cell-back">
                            <div class="target-huge">≤12%</div>
                            <p>Industry benchmark</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="decision-gate-banner pulse-banner">
                <i class="fas fa-shield-check"></i>
                Decision Gate: Pass ≥4 → R508.6M Authorised
            </div>
        </div>
    </div>
</div>
```

**3D Flip Animation CSS**:
```css
.split-visual-data {
    display: grid;
    grid-template-columns: 0.4fr 0.6fr;
    gap: clamp(30px, 5vw, 60px);
    height: 100%;
    align-items: center;
}

.portrait-art {
    width: 100%;
    max-width: 400px;
    height: auto;
    border-radius: 20px;
    box-shadow: 0 20px 60px rgba(0,0,0,0.5);
    animation: floatPortrait 6s ease-in-out infinite;
}

@keyframes floatPortrait {
    0%, 100% { transform: translateY(0) rotate(0deg); }
    50% { transform: translateY(-20px) rotate(2deg); }
}

.criteria-grid-3d {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: clamp(15px, 2.5vw, 25px);
    perspective: 1000px;
}

.criterion-cell {
    position: relative;
    height: 180px;
    cursor: pointer;
}

.cell-inner {
    position: relative;
    width: 100%;
    height: 100%;
    transition: transform 0.8s cubic-bezier(0.68, -0.55, 0.265, 1.55);
    transform-style: preserve-3d;
}

.criterion-cell:hover .cell-inner {
    transform: rotateY(180deg);
}

.cell-front,
.cell-back {
    position: absolute;
    width: 100%;
    height: 100%;
    backface-visibility: hidden;
    border-radius: 15px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 20px;
}

.cell-front {
    background: linear-gradient(135deg, rgba(76,175,80,0.1), rgba(46,125,50,0.1));
    border: 2px solid rgba(76,175,80,0.3);
}

.cell-back {
    background: linear-gradient(135deg, #4CAF50, #2E7D32);
    transform: rotateY(180deg);
    box-shadow: 0 0 30px rgba(76,175,80,0.6);
}

.criterion-number {
    width: 50px;
    height: 50px;
    background: #4CAF50;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.8rem;
    font-weight: 900;
    color: #000;
    margin-bottom: 10px;
}

.target-huge {
    font-size: clamp(2.5rem, 5vw, 4rem);
    font-weight: 900;
    color: #fff;
    line-height: 1;
    text-shadow: 0 5px 15px rgba(0,0,0,0.5);
}

.flip-in {
    opacity: 0;
    transform: rotateX(-90deg) scale(0.5);
    animation: flipInSequence 0.6s cubic-bezier(0.34, 1.56, 0.64, 1) forwards;
}

.flip-in[data-order="1"] { animation-delay: 0.1s; }
.flip-in[data-order="2"] { animation-delay: 0.2s; }
.flip-in[data-order="3"] { animation-delay: 0.3s; }
.flip-in[data-order="4"] { animation-delay: 0.4s; }
.flip-in[data-order="5"] { animation-delay: 0.5s; }

@keyframes flipInSequence {
    0% {
        opacity: 0;
        transform: rotateX(-90deg) scale(0.5);
    }
    60% {
        transform: rotateX(10deg) scale(1.1);
    }
    100% {
        opacity: 1;
        transform: rotateX(0) scale(1);
    }
}

.glitch-effect {
    position: relative;
    animation: glitchPulse 5s infinite;
}

@keyframes glitchPulse {
    0%, 90%, 100% {
        text-shadow: none;
    }
    92% {
        text-shadow:
            -2px 0 #ff00ff,
            2px 2px #00ffff;
    }
    94% {
        text-shadow:
            2px -2px #ff00ff,
            -2px 2px #00ffff;
    }
    96% {
        text-shadow: none;
    }
}
```

---

#### **SLIDE 4: BUDGET BREAKDOWN EXPLOSION**
**Visual**: `03_Agriculture_Crops/hands_golden_wheat_3.png` - hands nurturing growth
**Animation**: Circular burst layout with rotating segments

```html
<div class="slide budget-burst-slide">
    <div class="bg-hands">
        <img src="assets/hands_golden_wheat.png">
        <div class="radial-overlay"></div>
    </div>

    <div class="burst-container">
        <div class="center-total pulse-massive">
            <div class="total-label">Total Budget</div>
            <div class="total-amount counter-massive">R15M</div>
        </div>

        <div class="segment-orbit segment-1" data-angle="0">
            <div class="segment-card hover-expand">
                <i class="fas fa-users segment-icon"></i>
                <h4>Human Capital</h4>
                <div class="amount">R4.8M</div>
                <div class="percentage">32%</div>
            </div>
        </div>

        <div class="segment-orbit segment-2" data-angle="72">
            <div class="segment-card hover-expand">
                <i class="fas fa-laptop-code segment-icon"></i>
                <h4>Technology</h4>
                <div class="amount">R3.6M</div>
                <div class="percentage">24%</div>
            </div>
        </div>

        <div class="segment-orbit segment-3" data-angle="144">
            <div class="segment-card hover-expand">
                <i class="fas fa-seedling segment-icon"></i>
                <h4>Agri Inputs</h4>
                <div class="amount">R4.2M</div>
                <div class="percentage">28%</div>
            </div>
        </div>

        <div class="segment-orbit segment-4" data-angle="216">
            <div class="segment-card hover-expand">
                <i class="fas fa-truck segment-icon"></i>
                <h4>Logistics</h4>
                <div class="amount">R1.8M</div>
                <div class="percentage">12%</div>
            </div>
        </div>

        <div class="segment-orbit segment-5" data-angle="288">
            <div class="segment-card hover-expand">
                <i class="fas fa-chart-line segment-icon"></i>
                <h4>Monitoring</h4>
                <div class="amount">R600K</div>
                <div class="percentage">4%</div>
            </div>
        </div>

        <svg class="connecting-lines">
            <!-- Animated connection lines drawn with JS -->
        </svg>
    </div>
</div>
```

**Circular Burst CSS**:
```css
.burst-container {
    position: relative;
    width: 100%;
    max-width: 900px;
    height: 700px;
    margin: 0 auto;
}

.center-total {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 220px;
    height: 220px;
    background: linear-gradient(135deg, #4CAF50, #2E7D32);
    border-radius: 50%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    box-shadow:
        0 0 50px rgba(76,175,80,0.8),
        0 0 100px rgba(76,175,80,0.4),
        inset 0 5px 20px rgba(255,255,255,0.2);
    z-index: 10;
}

.pulse-massive {
    animation: pulseMassive 2s ease-in-out infinite;
}

@keyframes pulseMassive {
    0%, 100% {
        transform: translate(-50%, -50%) scale(1);
        box-shadow:
            0 0 50px rgba(76,175,80,0.8),
            0 0 100px rgba(76,175,80,0.4);
    }
    50% {
        transform: translate(-50%, -50%) scale(1.08);
        box-shadow:
            0 0 70px rgba(76,175,80,1),
            0 0 140px rgba(76,175,80,0.6);
    }
}

.total-amount {
    font-size: clamp(2.5rem, 5vw, 4rem);
    font-weight: 900;
    color: #fff;
}

.segment-orbit {
    position: absolute;
    top: 50%;
    left: 50%;
    width: 350px;
    height: 350px;
    transform-origin: center;
}

.segment-orbit[data-angle="0"] {
    transform: translate(-50%, -50%) rotate(0deg);
}
.segment-orbit[data-angle="72"] {
    transform: translate(-50%, -50%) rotate(72deg);
}
.segment-orbit[data-angle="144"] {
    transform: translate(-50%, -50%) rotate(144deg);
}
.segment-orbit[data-angle="216"] {
    transform: translate(-50%, -50%) rotate(216deg);
}
.segment-orbit[data-angle="288"] {
    transform: translate(-50%, -50%) rotate(288deg);
}

.segment-card {
    position: absolute;
    top: -60px;
    left: 50%;
    transform: translateX(-50%);
    width: 140px;
    height: 140px;
    background: rgba(0,0,0,0.9);
    border: 2px solid #4CAF50;
    border-radius: 15px;
    padding: 15px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    backdrop-filter: blur(10px);
    cursor: pointer;
    transition: all 0.4s cubic-bezier(0.34, 1.56, 0.64, 1);
    opacity: 0;
    animation: segmentAppear 0.6s ease forwards;
}

.segment-1 .segment-card { animation-delay: 0.2s; }
.segment-2 .segment-card { animation-delay: 0.4s; }
.segment-3 .segment-card { animation-delay: 0.6s; }
.segment-4 .segment-card { animation-delay: 0.8s; }
.segment-5 .segment-card { animation-delay: 1.0s; }

@keyframes segmentAppear {
    from {
        opacity: 0;
        transform: translateX(-50%) scale(0) rotate(-180deg);
    }
    to {
        opacity: 1;
        transform: translateX(-50%) scale(1) rotate(0deg);
    }
}

.hover-expand:hover {
    transform: translateX(-50%) scale(1.15);
    border-color: #8BC34A;
    box-shadow: 0 15px 40px rgba(76,175,80,0.5);
    z-index: 20;
}

.segment-icon {
    font-size: 2rem;
    color: #4CAF50;
    margin-bottom: 8px;
}

.segment-card .amount {
    font-size: 1.2rem;
    font-weight: 700;
    color: #4CAF50;
}

.segment-card .percentage {
    font-size: 0.9rem;
    color: #8BC34A;
    font-weight: 600;
}
```

---

#### **SLIDE 5: TIMELINE JOURNEY MAP**
**Visual**: `05_harvest_field_sunset_golden.jpg` - journey to harvest
**Animation**: Animated path with milestones appearing along journey

```html
<div class="slide timeline-journey">
    <div class="journey-bg" style="background-image: url('assets/harvest_sunset.jpg')"></div>

    <h2 class="journey-title">6-Month Journey Map</h2>

    <div class="journey-path">
        <svg class="path-line" viewBox="0 0 1200 400">
            <path id="journey-curve"
                  d="M 50,350 Q 300,50 600,200 T 1150,100"
                  stroke="#4CAF50"
                  stroke-width="4"
                  fill="none"
                  stroke-dasharray="2000"
                  stroke-dashoffset="2000">
            </path>

            <!-- Animated dots along path -->
            <circle class="journey-dot" r="8" fill="#8BC34A">
                <animateMotion dur="3s" repeatCount="indefinite">
                    <mpath href="#journey-curve"/>
                </animateMotion>
            </circle>
        </svg>

        <div class="milestone mile-1" data-month="Month 1">
            <div class="mile-marker">
                <div class="mile-icon"><i class="fas fa-flag-checkered"></i></div>
                <div class="mile-label">START</div>
            </div>
            <div class="mile-detail">
                <h4>Infrastructure Setup</h4>
                <ul>
                    <li>Deploy IoT sensors</li>
                    <li>Drone fleet activation</li>
                    <li>Platform launch</li>
                </ul>
            </div>
        </div>

        <div class="milestone mile-2" data-month="Month 2-3">
            <div class="mile-marker">
                <div class="mile-icon"><i class="fas fa-users"></i></div>
                <div class="mile-label">ONBOARD</div>
            </div>
            <div class="mile-detail">
                <h4>Farmer Enrollment</h4>
                <ul>
                    <li>100 farmers recruited</li>
                    <li>Training completed</li>
                    <li>First loans disbursed</li>
                </ul>
            </div>
        </div>

        <div class="milestone mile-3" data-month="Month 4">
            <div class="mile-marker">
                <div class="mile-icon"><i class="fas fa-chart-line"></i></div>
                <div class="mile-label">TRACK</div>
            </div>
            <div class="mile-detail">
                <h4>Data Collection</h4>
                <ul>
                    <li>Daily platform usage</li>
                    <li>IoT metrics logged</li>
                    <li>Credit scoring trained</li>
                </ul>
            </div>
        </div>

        <div class="milestone mile-4" data-month="Month 5-6">
            <div class="mile-marker">
                <div class="mile-icon"><i class="fas fa-award"></i></div>
                <div class="mile-label">HARVEST</div>
            </div>
            <div class="mile-detail">
                <h4>Results & Validation</h4>
                <ul>
                    <li>Yield measurements</li>
                    <li>Success criteria evaluated</li>
                    <li>Decision gate review</li>
                </ul>
            </div>
        </div>

        <div class="milestone mile-5" data-month="Post-Pilot">
            <div class="mile-marker glow-success">
                <div class="mile-icon"><i class="fas fa-rocket"></i></div>
                <div class="mile-label">SCALE</div>
            </div>
            <div class="mile-detail highlight-box">
                <h4 class="gradient-text">R508.6M Deployment</h4>
                <p>If ≥4 criteria passed</p>
            </div>
        </div>
    </div>
</div>
```

**Animated Path CSS**:
```css
.journey-path {
    position: relative;
    width: 100%;
    max-width: 1200px;
    height: 500px;
    margin: 0 auto;
}

.path-line {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    overflow: visible;
}

#journey-curve {
    animation: drawPath 3s ease-out forwards;
}

@keyframes drawPath {
    to {
        stroke-dashoffset: 0;
    }
}

.journey-dot {
    filter: drop-shadow(0 0 10px #8BC34A);
}

.milestone {
    position: absolute;
    display: flex;
    flex-direction: column;
    align-items: center;
    opacity: 0;
    animation: milestoneAppear 0.6s ease forwards;
}

.mile-1 {
    top: 300px;
    left: 5%;
    animation-delay: 0.5s;
}

.mile-2 {
    top: 50px;
    left: 25%;
    animation-delay: 1s;
}

.mile-3 {
    top: 180px;
    left: 50%;
    animation-delay: 1.5s;
}

.mile-4 {
    top: 320px;
    left: 72%;
    animation-delay: 2s;
}

.mile-5 {
    top: 80px;
    left: 92%;
    animation-delay: 2.5s;
}

@keyframes milestoneAppear {
    from {
        opacity: 0;
        transform: translateY(30px) scale(0.5);
    }
    to {
        opacity: 1;
        transform: translateY(0) scale(1);
    }
}

.mile-marker {
    width: 80px;
    height: 80px;
    background: linear-gradient(135deg, #4CAF50, #2E7D32);
    border-radius: 50%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    box-shadow: 0 10px 30px rgba(76,175,80,0.4);
    position: relative;
    z-index: 2;
}

.mile-marker::before {
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    border-radius: 50%;
    border: 3px solid #4CAF50;
    animation: ripple 2s infinite;
}

@keyframes ripple {
    0% {
        transform: scale(1);
        opacity: 1;
    }
    100% {
        transform: scale(1.5);
        opacity: 0;
    }
}

.glow-success {
    animation: glowPulseSuccess 1.5s ease-in-out infinite;
}

@keyframes glowPulseSuccess {
    0%, 100% {
        box-shadow: 0 10px 30px rgba(76,175,80,0.4);
    }
    50% {
        box-shadow: 0 10px 60px rgba(76,175,80,0.8),
                    0 0 100px rgba(76,175,80,0.5);
    }
}

.mile-icon {
    font-size: 2rem;
    color: #fff;
}

.mile-label {
    font-size: 0.7rem;
    font-weight: 700;
    color: #fff;
    margin-top: 2px;
}

.mile-detail {
    margin-top: 15px;
    background: rgba(0,0,0,0.9);
    border: 2px solid rgba(76,175,80,0.3);
    border-radius: 10px;
    padding: 15px 20px;
    min-width: 200px;
    backdrop-filter: blur(10px);
}

.milestone:hover .mile-detail {
    border-color: #4CAF50;
    transform: scale(1.05);
}
```

**🎯 CONTINUE THIS PATTERN FOR SLIDES 6-8...**

---

## 🎨 ANIMATION LIBRARY

### **Core Entrance Animations**

```css
/* Explosive Word Entrance */
@keyframes wordExplode {
    0% {
        opacity: 0;
        transform: translateY(50px) rotateX(-90deg) scale(0.5);
    }
    60% {
        transform: translateY(-10px) rotateX(10deg) scale(1.1);
    }
    100% {
        opacity: 1;
        transform: translateY(0) rotateX(0) scale(1);
    }
}

/* 3D Flip Cards */
@keyframes flipIn3D {
    0% {
        opacity: 0;
        transform: perspective(1000px) rotateY(-90deg) scale(0.8);
    }
    50% {
        transform: perspective(1000px) rotateY(15deg) scale(1.05);
    }
    100% {
        opacity: 1;
        transform: perspective(1000px) rotateY(0) scale(1);
    }
}

/* Particle Burst */
@keyframes particleBurst {
    0% {
        transform: translate(0, 0) scale(0);
        opacity: 1;
    }
    100% {
        transform: translate(var(--tx), var(--ty)) scale(1);
        opacity: 0;
    }
}

/* Shimmer Sweep */
@keyframes shimmerSweep {
    0% {
        background-position: -200% center;
    }
    100% {
        background-position: 200% center;
    }
}

/* Glow Pulse */
@keyframes glowPulse {
    0%, 100% {
        box-shadow: 0 0 20px var(--glow-color),
                    0 0 40px var(--glow-color);
    }
    50% {
        box-shadow: 0 0 40px var(--glow-color),
                    0 0 80px var(--glow-color),
                    0 0 120px var(--glow-color);
    }
}
```

---

## 📊 PERFORMANCE OPTIMIZATION

```javascript
// Intersection Observer for Lazy Animation Triggers
const animationObserver = new IntersectionObserver(
    (entries) => {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                entry.target.classList.add('visible');

                // Trigger counters
                if (entry.target.classList.contains('counter-animate')) {
                    animateCounter(entry.target);
                }

                // Trigger progress bars
                if (entry.target.classList.contains('progress-fill')) {
                    entry.target.style.width = entry.target.dataset.width + '%';
                }
            }
        });
    },
    { threshold: 0.3 }
);

// Observe all animated elements
document.querySelectorAll('.animate-on-view').forEach(el => {
    animationObserver.observe(el);
});

// Preload critical images
const criticalImages = [
    'assets/midjourney_exploding_light.png',
    'assets/02_tractor_sunset.jpg',
    'assets/midjourney_bw_stars.png'
];

criticalImages.forEach(src => {
    const img = new Image();
    img.src = src;
});
```

---

## 🚀 NEXT STEPS

1. ✅ Copy all Midjourney images + UAEI images to each presentation's `assets/` folder
2. ✅ Create external `css/styles-cinematic.css` with all animation CSS
3. ✅ Build `js/animations.js` with intersection observers, counters, 3D effects
4. ✅ Implement slide-by-slide HTML with image mappings
5. ✅ Test animations on different screen sizes
6. ✅ Add sound effects (optional): Whoosh on slide change, ping on counter complete

**Estimated build time**: 2-3 days for all 3 presentations
**WOW factor**: 🔥🔥🔥🔥🔥 MAXIMUM

---

Ready to build the most stunning agricultural investment presentations ever created? 🎬✨
