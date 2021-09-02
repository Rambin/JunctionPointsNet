# Manipulating NTFS Junction Points in .NET

[中文](README_CN.md)

## 1 Source code from

**[Here](https://www.codeproject.com/Articles/15633/Manipulating-NTFS-Junction-Points-in-NET)**

Thanks to **jeff.brown**

## 2 Modification

Modified data wroten to **Reparse Points**, to make the behavior same as **mklink /j** when creating a junction to a volume guid path (such as "\\\\?\\Volume{4bceaf62-786d-446d-a09a-8d95b9b0ff5b}")

Besides, modified parsing method to data read from **Reparse Points**, presenting same as what **dir /a** do.

## 3 License

There is no explicit license attached. Treat it as **Public Domain**
