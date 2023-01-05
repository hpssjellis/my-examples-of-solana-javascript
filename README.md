# my-examples-of-solana-javascript


Solana Javascript npm at   https://www.npmjs.com/package/@solana/web3.js

API at  https://solana-labs.github.io/solana-web3.js/

and https://solana.com/




Presently version 1.73.0

```
<!-- Development (un-minified) -->
<script src="https://unpkg.com/@solana/web3.js@latest/lib/index.iife.js"></script>

<!-- Production (minified) -->
<script src="https://unpkg.com/@solana/web3.js@latest/lib/index.iife.min.js"></script>


So best to use 

<script src="https://unpkg.com/@solana/web3.js@1.73.0/lib/index.iife.js"></script>

and then update it as new releases are proved to work


```



This is what ChatGPT says about the library

What are the main methods and properties in the solana javascript library at  ```https://unpkg.com/@solana/web3.js@1.73.0/lib/index.iife.js```

The Solana JavaScript library is a collection of functions that allow you to interact with the Solana blockchain from a JavaScript environment, such as a web browser or Node.js server. Here are some of the main methods and properties that are available in the library:

new Client(url: string, options?: object): This constructor function creates a new Client object that you can use to send transactions and queries to the Solana network.

Client.sendTransaction(transaction: Transaction): Promise<TransactionResult>: This method sends a transaction to the Solana network. The Transaction object should contain all the necessary information for the transaction, such as the signer and the program to execute. The method returns a promise that resolves to a TransactionResult object, which contains the result of the transaction.

Client.getAccountInfo(address: PublicKey): Promise<AccountInfo>: This method retrieves information about an account on the Solana network, including its balance and the data stored in its storage. The address parameter should be a public key that identifies the account. The method returns a promise that resolves to an AccountInfo object.

Client.getSignatureStatus(signature: Signature): Promise<SignatureStatus>: This method retrieves the status of a transaction signature on the Solana network. The signature parameter should be the signature of the transaction. The method returns a promise that resolves to a SignatureStatus object, which indicates whether the transaction has been processed and whether it was successful.

There are many other methods and properties available in the Solana JavaScript library, so you should consult the documentation for a complete list.
  
  
