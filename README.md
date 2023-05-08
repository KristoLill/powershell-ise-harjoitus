# powershell-ise-harjoitus

Scripti etsii uusimman teksti tiedoston paikasta "C:\TestFile" ja lukee sen.


Alkuperäinen scripti etsii kaikki tiedostot paikasta "C:\TestFile" ja laittaa ne listaan.
Alkuperäinen scripti:
$directory = "C:\TestFile"
$fileArray = @(Get-ChildItem $directory -File)
$fileArray
