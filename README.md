# EzzyFx Receipt Studio

Buildless PWA for manually recording buy, sell, swap, and currency exchange transactions. Run `python3 -m http.server 4187 --directory dist` for local use. Production requires HTTPS for installation and file sharing.

PNG generation uses the same canvas as the live preview. Customer sends and receives are entered explicitly; the agreed rate is a recorded quote, not an automatic calculation. No live trade or payment verification is performed. Drafts and up to 50 receipts are stored in browser localStorage, without cross-device sync. Clearing browser storage removes these records. Private hosting controls online access; offline records remain accessible on the owner's device.

Share uses the native file share menu where supported, otherwise downloads the PNG for attaching manually. Select WhatsApp yourself in the share menu. PWA shell is cached after the first successful load. Install prompts depend on the browser; manual Safari instructions are provided.
