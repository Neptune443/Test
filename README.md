# Test
Test
0. Lite test
0. Lite test
0. Lite test
0. Lite test

[WIKI](../../wiki)

```powershell
do {
    $res = $udpClient.BeginReceive($null,$null)
    while(-not $res.IsCompleted){Start-Sleep -Milliseconds 50}
    $r = $udpClient.EndReceive($res,[ref]$senderAddress)
    $r|Format-Hex
    $senderAddress
} while ($true)
```

