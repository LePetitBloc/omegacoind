# FAQ

## The `masternode outputs` return an empty object.
```
{
}
```

You must receive the **1000 OMEGA** for the **masternode** in a single transaction on your **Control Wallet** and wait for at least 1 confirmation.
> If you already have the **1000 OMEGA** but it came from multiple transactions, you can send the **1000 OMEGA** back to yourself:
```
docker exec omegacoin-wallet omegacoin-cli sendfrom "" YoUrAdDr3Ss OMEGA
```

## Running a **wallet** or a **masternode** container result in the following error:
```
No such file or directory
```

Ensure the `data` folder is *writable* for the container.
