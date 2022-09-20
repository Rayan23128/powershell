# powershell 2 

 PS C:\FolderTest1> Set-Location -Path C:\OddFolder

PS C:\OddFolder> Get-ChildItem


    Répertoire : C:\OddFolder


Mode                 LastWriteTime         Length Name                                                                                                                                                                                                     
----                 -------------         ------ ----                                                                                                                                                                                                     
-a----        20/09/2022     17:31              0 file1                                                                                                                                                                                                    
-a----        20/09/2022     17:31              0 File3                                                                                                                                                                                                    
-a----        20/09/2022     17:31              0 file5                                                                                                                                                                                                    
-a----        20/09/2022     17:31              0 File7                                                                                                                                                                                                    
-a----        20/09/2022     17:31              0 File9                                                                                                                                                                                                    



PS C:\OddFolder>  Set-Location -Path C:\EvenFolder

PS C:\EvenFolder> Get-ChildItem


    Répertoire : C:\EvenFolder


Mode                 LastWriteTime         Length Name                                                                                                                                                                                                     
----                 -------------         ------ ----                                                                                                                                                                                                     
-a----        20/09/2022     17:31              0 File10                                                                                                                                                                                                   
-a----        20/09/2022     17:31              0 file2                                                                                                                                                                                                    
-a----        20/09/2022     17:31              0 File4                                                                                                                                                                                                    
-a----        20/09/2022     17:31              0 File6                                                                                                                                                                                                    
-a----        20/09/2022     17:31              0 File8                                                                                                                                                                                                    



PS C:\EvenFolder>  
