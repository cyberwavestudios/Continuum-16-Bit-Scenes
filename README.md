# Continuum 16-Bit Scenes

A standalone 16-bit cinematic experience for the concept album *We Never Met, But I Remember You*. This is the new replacement for the older Album Companion app; it is not the Continuum comic reader.

## Deployment

Serve `index.html` and `album.mp3` together from the root of an HTTPS website. There is no build step, database, or password. The viewer presses **Press to Play** to start the film and album audio. The intended future address is `https://continuum.cyberwavestudios.com`, but DNS and the prior apps’ album links have **not** been changed; wait until the owner confirms deployment there.

The original two files were verified byte-for-byte against a ZIP downloaded back from this private repository. Local playback started in a browser, but the owner should test the entire film, audio, scrubbing, fullscreen, and phone layout after deployment.
