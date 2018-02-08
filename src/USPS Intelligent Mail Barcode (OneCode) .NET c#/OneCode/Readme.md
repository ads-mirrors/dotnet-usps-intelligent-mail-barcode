OneCode_Binaries_20071110.rar includes:
binaries for .NET Framework (1.1, 2.0 and 3.5), .NET Compact Framework (2.0 and 3.5) and Mono (1.* and 2.0),
a common asmx file,
and the license file.

OneCode_VS2008_Source_20071110.rar includes:
source code for .NET Framework and Compact Framework (2.0 and 3.5) in C# and VB.NET,
a common asmx file,
and the license file.

Please visit http://ribbs.usps.gov/onecodesolution/ for information and specs.

Sample C# usage:
String bars = OneCode.Bars(zipinfo);

Sample VB.NET usage:
Dim bars As String = OneCode.Bars(zipinfo)

Source code and binaries for .NET Framework and Compact Framework versions 2.0 and 3.5 include support for the ExtensionAttribute.

Sample Extension C# usage:
String bars = zipinfo.OneCodeBars();

Sample Extension VB.NET usage:
Dim bars = zipinfo.OneCodeBars()