# test-keyboard

# Run node http-server
 npx http-server -p 3344

 # Run index.html with cobalt
 adb shell am force-stop tv.smartlabs.cobalt.demo; adb shell am start -n "tv.smartlabs.cobalt.demo/tv.smartlabs.framework.MainActivity" -a android.intent.action.MAIN --esa args --url="http://localhost:3344/?t=1231223"