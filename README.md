Crystal Arrow Crusher
� 
Description
Crystal Arrow Crusher is a simple, addictive HTML5 game built with Canvas, where players control an arrow at the bottom of the screen to shoot projectiles at falling crystal stones. Destroy the stones to earn points, collect special gems for bonuses, and avoid letting stones reach the bottom to prevent game over. The game features increasing difficulty levels, multipliers, and particle effects for an engaging experience.
This game is optimized for performance on both mobile (touch) and desktop (keyboard/mouse) devices. It uses no external frameworks beyond Font Awesome for icons (loaded via CDN).
Key features:
Falling stones with different types (Quartz, Obsidian, Jade, Amethyst, Diamond) offering varying points and effects.
Special effects: Amethyst activates a 5x multiplier; Diamond clears the screen.
Particle explosions and glowing effects for visual feedback.
Responsive design with touch controls on mobile and keyboard/mouse on desktop.
Pause functionality and FPS logging for debugging.
Installation
No installation is required! This is a single-file HTML game.
Download the index.html file (or copy the provided code into a new file named index.html).
Open the file in any modern web browser (e.g., Chrome, Firefox, Safari).
For mobile: Open in a mobile browser for touch controls.
For desktop: Open in a desktop browser for keyboard/mouse controls.
Dependencies:
Font Awesome (loaded via CDN: https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/js/all.min.js).
Internet connection is required for the CDN on first load; after that, it may cache.
If you want to run offline:
Download Font Awesome JS and host it locally, then update the <script> src in the HTML.
Usage
Open index.html in your browser.
Click "Start Game" on the main menu.
Play the game:
Mobile/Touch:
Drag in the left movement area to move the arrow left/right.
Tap the shoot button (lightning icon) on the right to fire projectiles.
Desktop:
Use Arrow Left/Right keys to move.
Or move the mouse horizontally over the canvas to position the arrow.
Press Spacebar or click the canvas to shoot.
Press 'P' to pause/resume.
Destroy falling stones to score points. Avoid letting them reach the bottom.
Game over when a stone hits the bottom—restart or return to menu.
To pause the game:
On desktop: Press 'P'.
The game auto-pauses when the tab is hidden (via visibility change).
For development/debugging:
FPS is logged to the console every second during gameplay.
Resize the browser window to see responsive adjustments.
Features
Levels and Progression: Difficulty increases over time with faster stones and higher spawn rates.
Multipliers and Bonuses: Collect Amethyst for temporary 5x scoring; Diamond for screen clear.
Visual Effects: Particle explosions, rotating stones, glowing arrow, twinkling stars background.
Optimizations:
Object pooling for particles to reduce garbage collection.
Throttled resize events.
Cached static star background in an offscreen canvas.
Smoothed movement with delta-time normalization for consistent 60fps feel.
Cross-Device Compatibility: Detects touch devices to show/hide controls and adjust canvas height.
Accessibility: Simple controls; keyboard support for desktop.
Controls
Mobile/Touch:
Move: Touch and drag in the left control area.
Shoot: Tap the shoot button (right side).
Pause: Switch tabs (auto-pause); no manual pause button yet.
Desktop:
Move Left: Arrow Left key.
Move Right: Arrow Right key.
Move (Alternative): Hover mouse over canvas.
Shoot: Spacebar or mouse click on canvas.
Pause: 'P' key.
Contributing
Contributions are welcome! Fork the repository (if hosted on GitHub) or modify the code directly.
Improve performance further (e.g., add web workers for heavy computations).
Add sound effects using Web Audio API.
Implement high scores with localStorage.
Report issues or suggest features via email or comments.
Please ensure changes maintain compatibility with both touch and desktop.
License
© 2023 Rasin. All rights reserved.
This game is provided as-is for educational and personal use. Do not redistribute commercially without permission.
Built with ❤️ using HTML5 Canvas, JavaScript, and CSS. Optimized as of August 11, 2025.
