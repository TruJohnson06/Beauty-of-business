# Project: The Quantum Ledger

## Vision
A high-end, interactive educational website built with Streamlit and Plotly. 
The goal is to show the "Beauty of Math" by connecting natural fractals 
(Mandelbrot) to financial engineering (Black-Scholes).

## Target Aesthetic
- **Theme:** Dark Mode, "Cyberpunk Quant" vibe.
- **Colors:** Neon Purples, Deep Blues, Gold accents.
- **Interactivity:** Smooth sliders, animated transitions, and hover-tooltips that explain the math.

## Instructions for Claude Code (Enhancement Phase)
1. **Refine UI:** Use Streamlit's `st.tabs` to organize sections better. Add custom CSS for a glowing "Glassmorphism" look.
2. **Add Stochastic Motion:** Create a new page for "Brownian Motion" where 50 particles walk randomly in real-time. This is the "bridge" between the Fractal and the Option Price.
3. **Black-Scholes 2.0:** Add the "Greeks" (Delta, Gamma, Theta) as secondary graphs below the main 3D surface.
4. **Educational Layer:** Use LaTeX to render every formula beautifully. When a user hovers over a variable like $\sigma$, show a "What is this?" pop-up explaining Volatility.
5. **Optimization:** Cache the heavy math functions using `@st.cache_data` so the app doesn't lag.