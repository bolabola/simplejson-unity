# simplejson-unity
fork from http://wiki.unity3d.com/index.php/SimpleJSON
## V 0.1
the file before my modification still keep the remains of the previous save, after modification there'll be a new file what covers the original file while save

line 464:var F = System.IO.File.OpenWrite(aFileName)-->var F = new FileStream(aFileName, FileMode.Create, FileAccess.Write)
line 501:var F = System.IO.File.OpenWrite(aFileName)-->var F = new FileStream(aFileName, FileMode.Create, FileAccess.Write)
