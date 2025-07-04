# My Strudel Music

Just a collection of music I've been making with [Strudel](https://strudel.cc/). Mostly experimenting with live coding and seeing what happens when you throw patterns at the wall.

## What's Here

Some tracks I've been working on - jungle stuff, ambient textures, weird experimental things. Nothing too serious, just having fun with algorithmic music.

## How to Use These

1. Go to [strudel.cc](https://strudel.cc/)
2. Copy whatever pattern looks interesting
3. Paste it in and hit play
4. Mess around with it

Most patterns load their own samples automatically. If something doesn't work, check if the sample links are still good.

## Running the Code

Basic workflow:

```javascript
// Load samples (usually at the top)
samples("github:oscarbeamish/samples")

// Make some noise
s("bd hh sd hh").fast(2)
```

Press `Ctrl+Enter` to start/stop patterns. Use `hush()` if things get too crazy.

## Live Coding Tips

- Start simple, add complexity gradually
- Use sliders for real-time control: `slider(1000, 100, 2000)`
- Save good patterns before experimenting further
- `sometimes()` and `every()` are your friends for variation

## File Structure

- `strudel_patterns_2025-07-04.json` - Main pattern collection
- `heartbeat-remake/` - Specific project folder
- Individual `.js` files for single patterns

## Notes

- These are personal experiments, quality varies
- Feel free to remix/modify anything
- Some patterns are unfinished sketches
- Tempo is usually around 140-170 BPM

Most of this is just me learning Strudel and seeing what it can do. If you use any of these patterns, cool! No need for formal attribution or anything.
