# simplejson-unity
fork from http://wiki.unity3d.com/index.php/SimpleJSON
## V 0.1
the file before my modification still keep the remains of the previous save, after modification there'll be a new file what covers the original file while save.

You can see the "Remarks"-->https://msdn.microsoft.com/en-us//library/system.io.file.openwrite.aspx

line 464:<code>var F = System.IO.File.OpenWrite(aFileName)</code>--><code>var F = new FileStream(aFileName, FileMode.Create, FileAccess.Write)</code>

line 501:<code>var F = System.IO.File.OpenWrite(aFileName)</code>--><code>var F = new FileStream(aFileName, FileMode.Create, FileAccess.Write)</code>


## V 0.2
Add:

    public static JSONNode LoadFromText(string aFileName){}
    
    public void SaveToText(string aFileName){}
