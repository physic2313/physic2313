<SCRIPT LANGUAGE=”JavaScript”>
fetch('https://api.ipify.org?format=json')
  .then(response => response.json())
  .then(data => console.log(data.ip));
</script>
