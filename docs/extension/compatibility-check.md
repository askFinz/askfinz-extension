# Device compatibility · the extension

Check in one tap whether your device can run askFinz models locally, and see what happens if it can't. Nothing is installed; no result leaves your browser.

**Canonical page:** [https://askfinz.com/extension/compatibility_check](https://askfinz.com/extension/compatibility_check)

## Key points

### One tap. No install

This is the same check the extension makes when it starts a model, running right here in this page. It reports whether models will run on your graphics processor or fall back to the cloud.

### Nothing breaks. It moves to the cloud

Compatibility decides where the work happens, not whether it happens. A device that can't run models locally still gets every feature of the extension.

### Three lines to look at

If you'd rather see it from the browser's own report than take our word for it.

### Three things worth trying

A software-only result usually means the browser can't reach your graphics card — not that the card is inadequate. That is normally fixable.

### A compatible machine can do more

If the check above came back compatible, the same graphics processor is capable of contributing to the index that askFinz searches — capped, out of your way, on a machine you keep using normally.

## Frequently asked

### Does this check install anything?

No. It runs entirely inside the page you're on, asks your browser about its graphics capability, and shows you the answer. Nothing is downloaded and no result is sent anywhere.

### My device isn't compatible. Is the extension still worth installing?

Yes. Every feature still works — the models simply run on askFinz servers instead of your machine. The only difference is that those requests draw on your account credits rather than being free.

### Why does on-device AI need a graphics processor at all?

Running a model is an enormous amount of parallel arithmetic, which is exactly what a graphics processor is built for. On a general-purpose processor alone the same work would be too slow to be usable, so the extension doesn't attempt it.

### The check says software-only. What does that mean?

Your browser found a graphics adapter, but it's one emulated in software rather than a real card. That's usually a driver problem or a virtualised environment, and the steps on this page fix most cases.

### Will the extension keep checking, or is this a one-off?

The extension makes the same check each time it starts a model, so if you fix a driver or move to a different machine it picks that up on its own. You don't have to tell it anything.

## Related

- [AI browser extension for Chrome, Edge, Firefox](https://askfinz.com/extension)

---

Summary of [https://askfinz.com/extension/compatibility_check](https://askfinz.com/extension/compatibility_check), generated from the page itself. The page is the source of truth. Contact: hello@askfinz.com
