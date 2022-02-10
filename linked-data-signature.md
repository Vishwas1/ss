## Linked Data Signature

> Adding digital signatures and digital proofs to existing linked data systems

Adding digital signature to [Linked data](./linked-data-and-json-ld.md) generated in [JSON-ld](./linked-data-and-json-ld.md) format. 


```
{
  "@context": "http://schema.org/",
  "@type": "Person",
  "name": "Jane Doe",
  "jobTitle": "Professor",
  "telephone": "(425) 123-4567",
  "url": "http://www.janedoe.com"
  "proof": {
    "type": "Ed25519Signature2020",
    "created": "2019-09-16T15:22:02Z",
    "verificationMethod": "did:example:123#key1",
    "domain": "website.example",
    "nonce": "fpcwi43io"
    "proofPurpose": "authentication",
    "proofValue": "zj902k...lY7dhH",
  }
}
```


References

- [Linked Data Signatures - Video](https://www.youtube.com/watch?v=QdUZaYeQblY)
- [Deck by w3 community](https://lists.w3.org/Archives/Public/public-credentials/2021May/att-0082/2021-Linked-Data-Security-WG-Charter.pdf)
