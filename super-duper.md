---
title: Document Center
---
# Hello

```powershell
do {
    $res = $udpClient.BeginReceive($null,$null)
    while(-not $res.IsCompleted){Start-Sleep -Milliseconds 50}
    $r = $udpClient.EndReceive($res,[ref]$senderAddress)
    $r|Format-Hex
    $senderAddress
} while ($true)
```

0. Todo #0
0. Todo #1 
0. Todo #2 
0. Todo #3
