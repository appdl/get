---
title: Now Desktop
---

<script>
    if (/(x64|WOW64)/i.test(navigator.userAgent)) {
        window.location.href = "http://now-desktop-releases.zeit.sh/download/win32";
    }
    if (/(x86_64)/i.test(navigator.userAgent)) {
        window.location.href = "http://now-desktop-releases.zeit.sh/download/win32";
    }
    if (/(Macintosh)/i.test(navigator.userAgent)) {
        window.location.href = "http://now-desktop-releases.zeit.sh/download/osx";
    }
    if (/(iPhone|iPod)/i.test(navigator.userAgent)) {
        alert("This app does not work on your device.");
    }
    if (/(iPad)/i.test(navigator.userAgent)) {
        alert("This app does not work on your device.");
    }
    if (/(Android)/i.test(navigator.userAgent)) {
        alert("This app does not work on your device.");
    }
</script>