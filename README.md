<script>
  const userAgent = navigator.userAgent || navigator.vendor || window.opera;

  if (/android/i.test(userAgent)) {
    window.location.replace("https://play.google.com/store/apps/details?id=com.yourapp");
  } else if (/iPhone|iPad|iPod/i.test(userAgent)) {
    window.location.replace("https://apps.apple.com/in/app/yourapp/id1234567890");
  } else {
    window.location.replace("https://visiontek.co.in");
  }
</script>
