# Taq-asset

Public images for TaqPay's Telegram inline mode (@TaqPayBot).

`inline/v1/` holds the banners sent as the inline message photo and the logo
tiles shown as list thumbnails. Telegram caches images by URL, so a changed
image goes into a new folder (`v2/`, ...) and the bot's base URL setting is
updated, instead of overwriting a file in place.
