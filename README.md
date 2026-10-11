# Watch Live Activity review evidence

`board.html` is the supplied HTML design proposal. Download it and open locally; it embeds its image assets.

`watch40` and `watch45` contain nine English native production-view fixture screenshots each: single running, multiple running, waiting with a short title, waiting with a long title, completed, failed, multiple completed, stale and reduced luminance.

These are native verification-host screenshots, not system Smart Stack screenshots. The paired-simulator forwarding check remains blocked: the Watch did not receive the current activity, and the iPhone liveactivitiesd logged a disabled sync engine and IDS errors. Reduced luminance is injected, not physical Always-On verification. No browser-rendered pixel comparison is claimed.

Source commit: a7736056b91d66f160112e6f3637753ae21fec36.

The evidence lives on a separate fork branch so review assets do not enter the upstream product diff.
