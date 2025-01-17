<!DOCTYPE html>
<html>
<head>
<title>EaglercraftX</title>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<meta name="robots" content="noindex, nofollow, noarchive">
<script type="text/javascript" src="classes.js"></script>
<script type="text/javascript" src="fix-webm-duration.js"></script>
<script type="text/javascript">
			window.addEventListener('load', function () {
				window.focus();
				document.body.addEventListener('click',function(e) {
					window.focus();
				},false);
			});	
			window.addEventListener("load", () => {
				if(document.location.href.startsWith("file:")) {
					alert("HTTP please, do not open this file locally, run a local HTTP server and load it via HTTP");
				}else {
					window.eaglercraftXOpts = {
						container: "game_frame",
						assetsURI: "assets.epk",
						localesURI: "lang/",
						servers: [
							{ addr: "wss://mc.arch.lol/", name: "ArchMC" },
							{ addr: "wss://mc.asspixel.net", name: "AssPixel" },
							{ addr: "wss://sus.shhnowisnottheti.me", name: "Ayunboom" },
							{ addr: "wss://aeon-network.net/1.8", name: "Aeon" },
							{ addr: "wss://zentic.org/", name: "Zentic" }
						]
					};
					main();
				}
			});
		</script>
</head>
<body style="margin:0px;width:100vw;height:100vh;" id="game_frame">
</body>
</html>