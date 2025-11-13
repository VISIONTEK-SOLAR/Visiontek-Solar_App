<script>
  const userAgent = navigator.userAgent || navigator.vendor || window.opera;

  if (/android/i.test(userAgent)) {
    window.location.replace("https://play.google.com/store/apps/details?id=com.visiontek.solar&pcampaignid=web_share");
  } else if (/iPhone|iPad|iPod/i.test(userAgent)) {
    window.location.replace("https://apps.apple.com/in/app/visionteksolar/id6751489602");
  } else {
    window.location.replace("https://visiontek.co.in");
  }
</script>
