## Extracting the assets from the official web port
 How I did it:
 
- First go to their website (https://projects.sappharad.com/s3air_ios/20240202_beta/sonic3air_web.html)
- Right click anywhere and click Inspect
- In the Inspect menu click on Sources

<img width="268" height="139" alt="Screenshot 2026-10-31 164904" src="https://github.com/user-attachments/assets/ac67ca53-5ef6-4277-b46a-308ca1719f66" />

- When you click on sources click on 'worker.js' and find these:
  ```
   var _cacheFiles = [
	'sonic3air_web.html',
	'sonic3air_web.js',
	'sonic3air_web.wasm',
	'loader.js',
	'manifest.json',
	'icon.png',
	'browserfs.min.js',
	'filemanager.js',
	'fileManagerRuntime.js',
	'react.js'

- When you find those get the .html and replace it with one of those files (example: https://projects.sappharad.com/s3air_ios/20240202_beta/sonic3air_web.html -> https://projects.sappharad.com/s3air_ios/20240202_beta/react.js)

 > [!NOTE]
> You will have to do this over and over again until you download every single one of them, and if it doesn't automatically download then right click anywhere and click 'Save as..'

- Once you download all the files your done! Just host it to a server and you can play it ( i dont know how to do it when writing this so just figure it out yourself )
