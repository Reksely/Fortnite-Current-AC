# Fortnite-Current-AC
Latest BE and EAC that can be used for hybrid servers to replace after closing

Downloads:

BE - https://raw.githubusercontent.com/Reksely/Fortnite-Current-AC/main/FortniteClient-Win64-Shipping_BE.exe

EAC - https://raw.githubusercontent.com/Reksely/Fortnite-Current-AC/main/FortniteClient-Win64-Shipping_EAC.exe

How to use inside code?

C# :

  Fornite.WaitForExit(); // make it wait for fortnite to exit
            client.DownloadFile("https://raw.githubusercontent.com/Reksely/Fortnite-Current-AC/main/FortniteClient-Win64-Shipping_BE.exe", fnpathfordownload + "/FortniteClient-Win64-Shipping_BE.exe");
            client.DownloadFile("https://raw.githubusercontent.com/Reksely/Fortnite-Current-AC/main/FortniteClient-Win64-Shipping_EAC.exe", fnpathfordownload + "/FortniteClient-Win64-Shipping_EAC.exe");
            
C++ :
        WaitForSingleObject(Fortnite, INFINITE);
DownloadFile("https://raw.githubusercontent.com/Reksely/Fortnite-Current-AC/main/FortniteClient-Win64-Shipping_BE.exe", fnPath + "FortniteClient-Win64-Shipping_BE.exe");
DownloadFile("https://raw.githubusercontent.com/Reksely/Fortnite-Current-AC/main/FortniteClient-Win64-Shipping_EAC.exe", fnPath + "FortniteClient-Win64-Shipping_EAC.exe");
