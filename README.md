# MD Sakib Hosen — Network Engineering & Infrastructure Portfolio (V2.1 Optimized)

This package contains the fully tested, mobile-first, zero-bloat portfolio website ready to push directly to your GitHub Pages repository (`https://md-sakib-hosen.github.io`).

## Key Improvements & Bug Fixes in This Release:
1. **Payload Reduced from 2.81 MB to 134 KB (95.2% lighter):**
   - High-resolution portfolio images and portraits extracted into web-optimized external assets in `/images/`.
   - Removed 217 KB dead JavaScript memory buffer (`PORTRAIT_TECH_B64`).
   - Browser caching enabled for all images and PDF CV.
2. **Class Size Accurately Updated:**
   - National Skills Development Authority (NSDA) Level-3 training workshop updated from "60+ candidates" to **"24+ students"** across all sections and modals.
3. **Fixed Contact Discrepancy:**
   - Standardized direct WhatsApp chat link to `+880 1988-169636` (`wa.me/8801988169636`), matching your phone and call links.
4. **Interactive Floating Back to Top Button Fixed:**
   - Added smooth scroll listener that dynamically reveals the floating pill at `scrollY > 280px` with smooth scroll-to-top behavior.
   - Added cyan-to-emerald gradient reading progress bar at the very top of the viewport.
5. **Tablet & Smartphone Ergonomics:**
   - Shifted desktop navbar collapse from `768px` to `1024px` (`lg:flex`), preventing iPad/tablet portrait navbar crowding and wrapping.
   - Project and Competency filter bars now use smooth horizontal touch scrolling (`overflow-x-auto no-scrollbar`), preventing multi-line button clutter on mobile screens.
   - All social icons, menu links, and buttons meet Apple/Android `44×44px` minimum touch target guidelines.
6. **Mobile Touch & Animation Fixes:**
   - Replaced clumsy hover listeners with `@media (hover: hover) and (pointer: fine)` to stop cyan spotlight cards and transforms from sticking on Android and iOS touchscreens.
   - Optimized `#particle-canvas` to 18 nodes on mobile with battery-saver auto-pause on tab hidden/backgrounding.
   - Modal dialog can now be dismissed by clicking anywhere on the dark backdrop or pressing the `Escape` key.

## How to Push to Your GitHub Website:

### On Windows:
Double-click `push_to_git.bat` or run:
```cmd
git add .
git commit -m "Optimize mobile performance, fix training class size, and resolve contact links"
git push origin main
```

### On macOS / Linux / Git Bash:
Run in your terminal:
```bash
chmod +x push_to_git.sh
./push_to_git.sh
```
