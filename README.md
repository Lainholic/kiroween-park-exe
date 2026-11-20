# PARK.EXE: PARK-TRON 8088

PARK.EXE reimagines the DOS disk-head parking utility as a browser-based CRT office simulation for Kiroween 2026’s Resurrection category. Type `PARK.EXE` and press Enter to hear a synthesized hard-drive parking sequence and reveal a miniature office where four agents follow independent routines.

- [Play PARK.EXE](https://lainholic.github.io/kiroween-chrono-fsm/park.html)
- [Watch the PARK.EXE demo](https://youtu.be/yNSFsaerMOE)

On touch screens, tap the monitor to start. Press `M` to toggle sound. The application needs no account, API key, or runtime dependencies.

## Run locally

From the repository root, serve the static files with Python 3, then open [PARK.EXE on localhost](http://127.0.0.1:8000/park.html).

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Run `npm test` with Node.js 24 or later to check the boot sequence, seeded agent behavior, audio scheduling, and shared-engine integrity. No `npm install` is needed.

The [PARK.EXE Kiro spec](.kiro/specs/park-exe/) and [verification hooks](.kiro/hooks/) document the work. The app code lives in `src/park/` and reuses the unmodified FSM engine from the [original Chrono-FSM repository](https://github.com/Lainholic/kiroween-chrono-fsm/tree/8224589903466a3a3a0917734b41fce896e46bd7).

[MIT License](LICENSE)
