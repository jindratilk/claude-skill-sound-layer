# sound-layer (Claude Code skill)

Adds a real sound-effects layer to a finished, muted motion video (HyperFrames, Remotion, After Effects render, any MP4). Uses real CC0 recordings instead of synthesized beeps, places cues from the animation's own timing and runs a QA loop, because Claude can't hear audio.

## Install

```bash
git clone https://github.com/jindratilk/claude-skill-sound-layer ~/.claude/skills/sound-layer
```

## Credits

This skill is a workflow wrapper around the scripts in [Bodila51/opus-sound-layer](https://github.com/Bodila51/opus-sound-layer) (MIT), based on the video "Sound design for Opus 5.5: no more cheap beeps" by 0xCodila. The skill clones that repository at runtime; none of its code is copied here.

## License

MIT, see [LICENSE](LICENSE).
