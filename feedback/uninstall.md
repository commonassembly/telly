---
title: Telly has been uninstalled.
---

<script>
function getParameterByName(name, url) {
    if (!url) url = window.location.href;
    name = name.replace(/[\[\]]/g, "\\$&");
    var regex = new RegExp("[?&]" + name + "(=([^&#]*)|&|#|$)"),
        results = regex.exec(url);
    if (!results) return null;
    if (!results[2]) return '';
    return decodeURIComponent(results[2].replace(/\+/g, " "));
}
var mp_id = getParameterByName("mp_id");
if (mp_id) { mixpanel.identify(mp_id) };
mixpanel.track("app:uninstallPage")
</script>



# Sad to see you go!

If you have a minute, it'd be great if you could let us know why, so we can improve Telly and make the next person happier. :-)


[Open Telly Feedback form](https://goo.gl/forms/r2QFTsZv32X78LVU2)
