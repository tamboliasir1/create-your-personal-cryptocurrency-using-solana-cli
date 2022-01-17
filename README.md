# create-your-personal-cryptocurrency-using-solana-cli
Personal Cryptocurrency - Solana quest 4

- solana-keygen pubkey 
  
  Output: 
    
    FP7Vo6uWe8C9Rzxj3B1Mm3gWZ3hoEn1YmenyJen7QP2g


- solana balance
  
  Output: 
    
    0


- solana airdrop 1 FP7Vo6uWe8C9Rzxj3B1Mm3gWZ3hoEn1YmenyJen7QP2g --url https://api.devnet.solana.com
  
  Output: 
    
    Requesting airdrop of 1 SOL

    Signature: 3QbNi3LwD9AqF9513USYjJNjCS3Zh2y3Je5mSwm8H6WqHxosjudiegJnzgeqBngRHFAxWggXkbbQMxnvVCLpGxQf

    1 SOL


- spl-token create-token
  
  Output:
    
    Creating token 2fZ3JAMRqD8WYLP6bkRkmtrZJYLtnFu2UKp4PJ3ZfLQ6
    
    Signature: 4QiD5bwtJpshW3mDb6Ti31uhWKTpWVz6xnSUxBhQjbvGVgqwtzmh2tyveuxBMmjCqaNKTdr1X2EoECyYEKB1LTrA


- spl-token create-account 2fZ3JAMRqD8WYLP6bkRkmtrZJYLtnFu2UKp4PJ3ZfLQ6 --url https://api.devnet.solana.com
  
  Ouput:
    
    Creating account 4SBoonXWu4rhp7BwhuTS5NhPLbiDBmoWA36bdUowmjZq
    
    Singnature: 5Se3RkwsKQ3wG5ykFNsA9vmcyXVcimcHTwqjUr3ymyb8u1R93erg8iGmWE88KJv91HpuDxdSE9kdmvTD1SM28M6h
    
    
- spl-token balance 2fZ3JAMRqD8WYLP6bkRkmtrZJYLtnFu2UKp4PJ3ZfLQ6 --url https://api.devnet.solana.com
  
  Ouput:
    
    0
    
    
- spl-token mint 2fZ3JAMRqD8WYLP6bkRkmtrZJYLtnFu2UKp4PJ3ZfLQ6 1000
  
  Output:
    
    Minting 1000 tokens
    
    Token: 2fZ3JAMRqD8WYLP6bkRkmtrZJYLtnFu2UKp4PJ3ZfLQ6
    
    Recipient: 4SBoonXWu4rhp7BwhuTS5NhPLbiDBmoWA36bdUowmjZq
    
    Signature: 48myXpUF1H8dindGRh14i42mpLnM9LdpKPgGnrKB2dYLtY7SdLygR9iNcYLWJnFKhxc69PsvMdT1wsz7Ldn3zWBD
    
    
- spl-token supply 2fZ3JAMRqD8WYLP6bkRkmtrZJYLtnFu2UKp4PJ3ZfLQ6
  
  Output:
    
    1000
    
    
- spl-token authorize 2fZ3JAMRqD8WYLP6bkRkmtrZJYLtnFu2UKp4PJ3ZfLQ6 mint –disable
  
  Output:
    
    Updating 2fZ3JAMRqD8WYLP6bkRkmtrZJYLtnFu2UKp4PJ3ZfLQ6
    
    Current mint authority: d5adbd871b455ab10430e3c4697cf3920ab3e1e7856e215dbe8cdf616ed1de51
    
    New mint authority: disabled
    
    Signature: 5tHtA8tGEJiAZSiCi3t7suFPPbyaxjDijazAtuRyvtUj2wk6gsFDcbSz1oDUvP5C7DCqExfpXtUe1RBCTAiKjcei
    
    
- spl-token burn 4SBoonXWu4rhp7BwhuTS5NhPLbiDBmoWA36bdUowmjZq 150
  
  Output:
    
    Burn 150 token
    
    Source: 4SBoonXWu4rhp7BwhuTS5NhPLbiDBmoWA36bdUowmjZq
    
    Signature: 35gsEtxZUuZgNajxJGQqNs8CfAQYf6ErhDek8CocFfWQaAKwHAGRPQf9Ng9ECHtUjTeG5uxsM1Hov6gJDKS5zbuq
    
    
- spl-token transfer 2fZ3JAMRqD8WYLP6bkRkmtrZJYLtnFu2UKp4PJ3ZfLQ6 100 DAu6Do8EhV3Jp6cXvgDAHbtYDFV1NvPbp9LAxMcWWuSy --allow-unfunded-recipient --fund-recipient --url https://api.devnet.solana.com 
  
  Output:
    
    Transfer 100 tokens
    
    Sender: 4SBoonXWu4rhp7BwhuTS5NhPLbiDBmoWA36bdUowmjZq
    
    Recipient: DAu6Do8EhV3Jp6cXvgDAHbtYDFV1NvPbp9LAxMcWWuSy
    
    Recipient associated token account: HD4AykyZediALyPohhotftuwFFnmm4UUy24Ykqtzruky
    
    Funding recipient: HD4AykyZediALyPohhotftuwFFnmm4UUy24Ykqtzruky (0.00203928 SOL)

    Signature: 4XHdFbkirJ2etqvaEqdVWTPGYyyMq2AosJ1S9PRScPjkFA1jp4z46Yxodsvudbno2pKo7kCFJLo6bB9K279E4TPP
