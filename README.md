# 🏙️ Urban Korfball Tactics Board

A mobile-friendly tactical board for urban korfball coaches and players, featuring a circular court design and frame-by-frame animation.

## 🎯 Features

- **Drag & Drop**: Move players and ball by dragging
- **Freehand Drawing**: Draw plays, arrows, and annotations
- **Frame Animation**: Create multi-frame play sequences
- **Playback**: Auto-play animations with adjustable speed
- **Color Options**: 5 colors (black, red, blue, green, white)
- **Eraser**: Remove drawings easily
- **Undo/Redo**: Up to 50 steps of history
- **Save/Load**: Export and import plays as JSON
- **PNG Export**: Save current frame as image
- **Double-tap**: Edit player numbers

## 📱 Mobile Optimized

- Touch-friendly interface
- Safe area support (iPhone notch, etc.)
- High DPI display support
- No pinch-zoom interference

## ⭕ Court Specifications

Urban Korfball uses a unique circular court design:

| Zone | Radius | Description |
|------|--------|-------------|
| Outer Circle | 9m | Court boundary |
| Middle Circle | 6m | Mid-range zone (dashed) |
| Inner Circle | 2.5m | Penalty area |
| Center | - | Korf position |

```
        ┌─────────────────┐
       ╱                   ╲
      │    ┌───────────┐    │
     │    ╱             ╲    │
     │   │   ┌───────┐   │   │  ← 9m (outer)
     │   │   │ (2.5m)│   │   │
     │   │   │  ●    │   │   │  ← Korf at center
     │   │   └───────┘   │   │
     │    ╲     6m     ╱    │
      │    └───────────┘    │
       ╲                   ╱
        └─────────────────┘
```

## 👥 Players

- **12 players total** (6 per team)
- **4 on court** (2 male + 2 female) per team
- **2 substitutes** (1 male + 1 female) outside court
- ⭕ Circle = Male player
- ⬜ Square = Female player
- 🔴 Red = Team A
- 🔵 Blue = Team B

## 🎬 Frame Animation

1. Create your first position
2. Tap **＋** to add a new frame
3. Move players to next position
4. Repeat for each step of the play
5. Tap **▶️ Play Animation** in menu to watch

### Frame Controls

| Button | Action |
|--------|--------|
| ◀ | Previous frame |
| ▶ | Next frame |
| ＋ | Add new frame (copy current) |
| 🗑 | Delete current frame |

## 🚀 Usage

1. Open in browser (works offline after first load)
2. Select tool: **Select** / **Draw** / **Erase**
3. Use frame controls to create animations
4. Tap **☰** for menu (playback, save, load, export)
5. Double-tap player to change number

## 🎨 Urban Style

The board features a street-style dark theme with:
- Concrete-like court surface
- Shadow effects for depth
- High contrast lines for visibility
- Zone labels for easy reference

## 📄 License

MIT License

## 👤 Author

**Hajime Shinohara**  
📧 shinohara@korfball.jp

## 🔗 Links

- [Japan Korfball Association](https://korfball.jp)
- [IKF Urban Korfball](https://korfball.sport)
