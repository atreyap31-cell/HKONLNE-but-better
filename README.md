This is stuf

Use

Download index.html and open it in Chrome (double-click works; needs internet, the game streams from the CDN). On first launch, slot 1 gets a premade Godseeker save (full map, 2400 essence); slots 2-4 are empty.

Press F2 for the debug panel:

    Perf: game FPS / frame times / 1% lows, 30s benchmark
    Display: render scale (default 1.0 = window resolution, skips high-DPI supersampling), pixelated mode, fullscreen
    Cheats
        Live (while playing): invincible, auto-heal, infinite soul, refill health/soul, +1000 geo, warp to Dream Gate
        Save slot (applies on reload, every box toggles both ways): bench warp (49 benches), infinite double jump, all charms, 0-cost charms, equip every charm, all abilities, max stats, full map, Hall of Gods statues, all Pantheons, Kingsoul/Void Heart, Grimmchild level, geo/essence/masks/nail damage/notches
    Saves: import/download userN.dat (same format as Steam 1.5.78), delete a slot, add the premade Godseeker save to a free slot
    System: GPU/browser info, copyable perf report, clear the game cache

Loading streams the 884 MB data file into Unity part by part (from cache or network), so peak memory during load is ~1.7 GB instead of ~3.1 GB.
