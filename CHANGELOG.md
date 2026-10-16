# Changelog

## 0.1.0rc22

- Publish the native integration and bundled dashboard cards in their own
  HACS-compatible repository.
- Add HACS/manual installation and migration instructions, CI validation and
  versioned release ZIPs.
- Point integration documentation and issue reporting to this repository.
- Keep the `open_fume_extractor` domain, device identities, entity unique IDs
  and polling behavior unchanged from 0.1.0rc21. No additional master/module
  flash is needed when already running Master 2.0.53.

## 0.1.0rc21

- Remove JBC USB station-specific entities after two confirmed reports of no
  connected station from an online module. Preserve module diagnostics and
  connection/Work/Stand indicators; restore supported entities on reconnect.
- Remove obsolete native devices already deleted from the master inventory.
- Prevent old station counters being resurrected from raw cached data.
