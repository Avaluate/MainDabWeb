## Script contribution guide
Script contribution is relatively easy.

### Scripts.json
If you wish to contribute scripts, simply edit [https://github.com/Avaluate/MainDabWeb/blob/master/UpdateStuff/Scripts.json](https://github.com/Avaluate/MainDabWeb/blob/master/UpdateStuff/Scripts.json) and create a pull request. Make sure you follow the .json format.

```json
{
  "title":"Title of script here",
  "credits": "by your name here",
  "desc" : "Description here",
  "script":"loadstring(game:HttpGet(\"https://raw.githubusercontent.com/Avaluate/MainDabWeb/master/ScriptStorage/SimpleAimbotESP.txt\"))()",
  "imgurl" : "https://raw.githubusercontent.com/Avaluate/MainDabWeb/master/ScriptStorageImages/!DefaultBackground.png"
}
```

### Can I touch anything else here?
No, it's pretty irrelevant. 
