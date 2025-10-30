# Radar Realtime GUI (Python + PySide6)

High-performance GUI for a radar-like system:
- Realtime visualization of radar targets on a map/canvas
- Interactive target info panel
- Smooth, timer-based updates to keep latency low
- Simulated radar feed (replace with real source later)

## Install
```bash
pip install -r requirements.txt
```

## Run
```bash
python -m src.main
```

## Notes
- Replace `RadarFeed.generate_targets()` in `src/radar_feed.py` with real radar input.
- The map uses a simple 2D coordinate plane (0..1000).

Dr. Ibrahem Almansour
