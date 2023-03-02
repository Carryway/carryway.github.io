<!DOCTYPE html>
<html lang="id" data-theme="dark">

<head>
  <!-- Meta tags  -->
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport"
    content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0" />
  <meta name="referrer" content="same-origin" />

  <title>Carryflix</title>
  <script src="https://cdn.jsdelivr.net/gh/Carryway/file@master/shaka-player.ui.js"></script>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Carryway/file@master/controls.css" />
  <style>
    body {
      background-color: #242424;
    }
  </style>
</head>

<body>
  <div>
    <div data-shaka-player-container="" shaka-controls="true" class="shaka-video-container"
      data-shaka-player-cast-receiver-id="8D8C71A7">
      <video poster="https://i.ibb.co/LpbbsYm/Untitled-1.png" data-shaka-player="" id="video"
        style="width: 100%; height: 100%" class="shaka-video"></video>
    </div>

    <script>
      const youtube_theme_manifestUri =
        "https://anevi-live-channel-cdn.mncnow.id/live/eds/RCTI-DD/sa_dash_vmx/RCTI-DD.mpd";

      async function init() {
        const video = document.getElementById("video");
        const ui = video["ui"];
        const config = {
          'seekBarColors': {
            base: "#fff",
            buffered: "#fff",
            played: "#0078FF",
          },
          'volumeBarColors': {
            base: 'rgba(255, 255, 255, 0.5)',
            level: 'rgb(0, 119, 255)',
          }
        }
        ui.configure(config);

        const controls = ui.getControls();
        const player = controls.getPlayer();

        player.configure({
          drm: {
            clearKeys: {
              // 'key-id-in-hex'                : 'key-in-hex',
              '9ba3e153ef8956d6e2b0684fcf74f58f': 'dbc28cb5c6426080f984a5b6d436bb30',

            }
          }
        });

        controls.addEventListener('caststatuschanged', onCastStatusChanged);

        function onCastStatusChanged(event) {
          const newCastStatus = event['newStatus'];
          // Handle cast status change
          console.log('The new cast status is: ' + newCastStatus);
        }

        try {
          await player.load(youtube_theme_manifestUri);
        } catch (error) { }

        // TODO find a way to do this without jquery. -___- or find a way to replace them CSS. maybe usering :after
        $(".shaka-overflow-menu-button").html("settings");
        $(".shaka-back-to-overflow-button .material-icons-round").html(
          "arrow_back_ios_new"
        );
      }
      document.addEventListener("shaka-ui-loaded", init);
    </script>
</body>

</html>
